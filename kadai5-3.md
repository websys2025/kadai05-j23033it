## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
"https://zipcloud.ibsnet.co.jp/api/search"
郵便番号から住所の取得

* リクエストとレスポンスのフォーマット
リクエスト
HTTPメソッド: GET
データ形式: URLエンコード
レスポンス
データ形式: JSON
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
openweatherapi
https://openweathermap.org/api
* エンドポイントと機能
https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key}
天気情報の取得
* リクエストとレスポンスのフォーマット
リクエスト
HTTPメソッド: GET
クエリパラメータ: `q`: 都市名
                `appid`: APIキー
データ形式: URLエンコード
レスポンス
データ形式: JSON

### Q3-3. 感想
* 今回の課題で苦労したこと
資料のプログラムからapiを使ったプログラムの作成をする際の記述や構造の理解をすること
* 演習を通して理解できたこと
apiを利用したプログラム作成の雰囲気
* Web APIの利便性や課題など
使いたい機能を外部から持ってこれる点
