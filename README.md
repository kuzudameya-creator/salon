# 美容室「atelier nui」サイト

HTMLとCSSだけで作っています（JavaScriptは使っていません）。
すべてのファイルを同じ場所に置く構成なので、フォルダを作らずにそのままアップロードできます。

## ページ
- index.html … トップ
- menu.html … メニュー・料金
- stylist.html … スタイリスト
- gallery.html … スタイルギャラリー（CSSの :has() で絞り込み）
- reserve.html … WEB予約
- thanks.html … 予約完了

## GitHub Pagesでの公開手順
1. GitHubで新しいリポジトリを作る（名前の例：salon、Public）
2. 「Add file」→「Upload files」で、全ファイル（HTML・CSS・SVG）をまとめてアップロード
3. Settings → Pages で Branch を main、フォルダを / (root) にして Save
4. 数分後に https://ユーザー名.github.io/salon/ で表示される

## 予約フォームについて
GitHub Pagesでは送信内容を受け取れないため、送信すると完了ページに移動するだけのデモです。
実際に受け取る場合は、Formspreeなどで発行したURLを reserve.html の action に入れ、method="post" に変更してください。
