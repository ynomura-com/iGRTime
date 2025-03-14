# IGRTime
IGRTime は、[岩手銀河鉄道（IGR）](https://igr.jp/)の[時刻表](https://igr.jp/timetable)のうち、短距離運行の電車などを除いて、盛岡〜一戸間を走る列車のみを抽出した時刻表です。

## 個人用に作ったもの
　私は、盛岡市に住んでいて職場のある一戸町に電車で通勤しているので、そのための時刻表として作成したものです。
 単にスプレッドシートに置き換えるのではなく、カウントダウン機能と、抜粋した時刻表の両方を見られるようにしました。
 盛岡駅、一戸駅と、岩手県立大学のある滝沢駅の時刻も追加しています。

 ## プログレッシブウェブアプリ (PWA) 
  2024年度までは HTML形式の単体ファイルにして、個人サイトにおいていましたが、プログレッシブウェブアプリ (PWA) にすれば、
  パケットを使わずに（通信ができない場合でも）利用できるので、PWA対応にしてここで公開することにしました。
  （PWA実装の勉強を兼ねて）
  
## 使い方
背景が黒い部分内の下に並んだボタンで、駅（時刻表）を切り替えます。
選択された時刻表と現在時刻で次の便の時刻を選び、残り時間を上部の背景が黒のところに表示します。
また、次の手順でインストールすることで PWA としてネット接続無しでも利用できるようになります。

## スマホのホーム画面へインストール
　https://ynomura-com.github.io/IGRTime/
 にアクセスして、画面が表示されたらホーム画面に登録するだけ。
 PCの場合は、アドレスバーにインストールできるボタンが表示されますので、それを利用してインストール。
 
 !["QR code"](QR_IGRTime.png)　　← WebアプリにアクセスするQRコードです。

 ## 時刻表データ
 この時刻表データは 2025年3月15日改正のものです。
 
