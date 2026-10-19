TimeNote スマホ対応版（PWA）

【大切】ZIPをスマホに保存するだけではアプリとしてインストールできません。
このフォルダの中身をHTTPS対応の静的サイトに公開してください。

無料公開の例：GitHub Pages
1. GitHubで新しい公開リポジトリを作る（例：timenote）
2. ZIPを展開し、index.html / sw.js / manifest.webmanifest / iconsフォルダをリポジトリの最上位へアップロード
3. Settings → Pages → Deploy from a branch → main / (root) → Save
4. 発行された https://...github.io/timenote/ のURLをスマホで開く
5. iPhone: Safariの共有メニュー → ホーム画面に追加
   Android: Chromeのメニュー → アプリをインストール または ホーム画面に追加

【注意】
・公開リポジトリのソースコードは他人に見えます。個人情報やパスワードをソースに書かないでください。
・勤務記録は各端末のブラウザ保存領域に保存され、同期されません。ブラウザデータを消すと記録が失われます。CSVで定期的にバックアップしてください。
・この試作版は実際の勤怠・給与の正式記録として使用する前に十分に確認してください。
・インターネットなしでも、初回オンライン読み込み後はキャッシュ済み画面を使えます（端末設定等により例外あり）。
・App StoreやGoogle Playへの登録は不要です。
