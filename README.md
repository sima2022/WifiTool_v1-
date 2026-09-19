# WifiTool_v1ß
Wi-Fi network tool for Android - prototype (UDP/TCP_TCP client /TCP server)
visual studio2022 MAUI .net8

Androidスマホ  でUDP TCP Sender&Receiverの様な動作を目指したAPKのみの試作版です。
実機でのTestは、Samsung SCV43(Android 10.0-API29)で行いました。
(Android17では、Fontサイズ変更してあると、Entryで文字がはみ出るみたいです。)

Android 10.0-API29以前のOSには、対応してません。


仕様。

UDP,TCPserver 2ch。TCPclient 1chの送受信+ping確認。
スライドメニューから、Dark Mode,接続出来るアクセスポイントの表示だけです。


使い方。

接続するPort番号と、IPアドレスの入力と、
接続ボタンを押すと受信開始、送信ボタンで送信。
送受信と接続状況等は、Listviewで表示します。

切断、ListviewのクリアとTabでUDP,TCPの通信開始時は、切断ボタン押さないと
Tabが切り替わらない様にしました。

その他、不足や間違った入力等あれば、DisplayAlertで表示します。

Entryの入力確定時のみカーソルが消え、ナビゲーション戻るボタンでは、残ったままでした。
Dark時Entryのアンダーライン黒とかぶり表示見えてない。

初めてのMAUI試作なので、もし不具合とか、連絡ありましたら修正したいと思ってます。
