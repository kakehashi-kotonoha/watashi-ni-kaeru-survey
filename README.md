# 『わたしに還る』お茶会 アンケート

4問だけのシンプルな事後アンケートです。`index.html` を GitHub リポジトリに置けば GitHub Pages で公開できます。

## 公開方法
1. GitHubで新しいリポジトリを作成
2. `index.html` をアップロード
3. Settings → Pages を開く
4. Deploy from a branch を選び、main / root を指定

## 回答の保存について
GitHub Pages は静的サイトなので、そのままでは回答を運営者へ保存・送信できません。
`index.html` 内の `ENDPOINT` に Google Apps Script、Formspree等の送信URLを設定してください。
未設定の場合は送信時に回答をブラウザの localStorage に保存し、完了画面を表示します。
