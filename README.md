# MyRepository_2

HTML, JavaScript, Node.js を用いた簡単なアプリケーションです。<br>
「特にネットワークの方を」というお話でしたので、通信の確立を中心とし、アプリの内容そのものはごく単純なものです。

# Features

【Web アプリ】<br>
サーバーには「PaizaCloud」という無料サービスを利用し、サーバー構築には Node.js を用いています。<br>
［アプリ画面上段］<br>
Ajax の非同期通信を用いてサーバーで処理するもの（テキストの文字数カウントアプリ）<br>
アプリ画面下段）］<br>
WebSocket プロトコルの双方向通信として、Node.jsのsocket.IOライブラリを用いたもの（チャット）
<br><br>
【ブラウザアプリ】<br>
個人公開されている WebAPI を用いて、公開サーバー上の人物データを収集するもの。
(公開元は[こちら](https://www.umayadia.com/Note/Note028WebAPISample.htm))<br>
API によって、GET リクエスト及び JSON 文字列のレスポンスを行っています。

# Usage

【Web アプリ】<br>
URL:[https://practiceserver.paiza-user-free.cloud:3000/index.html](https://practiceserver.paiza-user-free.cloud:3000/index.html)<br>
アプリ画面上段ではテキストを記入し「Count」ボタンを。下段のチャットはブラウザを２つ起動させて試してみてください。<br>
ソースファイルは「WebApp」にあります。<br>
【ブラウザアプリ】<br>
アプリケーションファイル（HTML）は「BrowserApp」にあります。
<br><br>
※HTML ファイル内に css, JavaScript を直接記入しました。

# Note

サーバーは無料プランのため、サーバー作成後24時間でリセットされる等、継続条件があります。<br>
Webアプリにて「サーバーが見当たりません。」などと表示されましたら連絡ください。すぐに再開設します。
