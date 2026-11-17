# 課題解消ミーティングのご案内 LP（動物病院 2027 時流予測セミナー参加者向け）

GitHub Pages で公開するためのファイル一式です。

- `index.html` : LP本体
- `images/` : 講師写真（kitano.png / kanbara.png / aida.png / fukunaga.png）
- `.nojekyll` : GitHub Pages の自動処理を無効にするための空ファイル

## 公開方法

### A. 既存のセミナーLPと同じリポジトリ（snc_2027）に置く場合
1. リポジトリのルートに `consultation` などのフォルダを作り、このフォルダの中身（index.html・images・.nojekyll）を入れる
2. 公開URL: https://k-snc.github.io/snc_2027/consultation/

### B. 新しいリポジトリで公開する場合
1. このフォルダの中身を、リポジトリのルートに置く
2. Settings > Pages で「Deploy from a branch」、ブランチ `main`、フォルダ `/ (root)` を選ぶ
3. 公開URL: https://k-snc.github.io/リポジトリ名/

## 計測（GA4）
セミナーLPと同じ Google タグマネージャー（GTM-5N86LG4L）を埋め込んでいます。
GTM内のGA4タグの配信トリガーが「All Pages」なら、追加設定なしでこのページもGA4で計測されます。
特定のページだけに配信する設定になっている場合は、このページのURLをトリガーに追加してください。

## 検索エンジン
参加者限定のページのため、`noindex` を指定して検索結果に出ないようにしています。
