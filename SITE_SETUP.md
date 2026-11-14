# 公式ホームページの公開設定（GitHub Pages）

**公開処理の状態（2026-11-15確認）:** `main /docs` のPagesデプロイは[GitHub Actionsで成功](https://github.com/kawamurashingo/open-steward-business/actions/runs/43654075009)しました。GitHubが提示したURL: **https://kawamurashingo.github.io/open-steward-business/**。外部からの表示およびモバイル実機確認は未完了です。

ホームページの静的ファイルは **[docs/index.html](docs/index.html)** と **[docs/assets/](docs/assets/)** にあります。

## GitHub Pages を有効化する

1. [リポジトリの Settings → Pages](https://github.com/kawamurashingo/open-steward-business/settings/pages) を開く。
2. **Build and deployment → Source** を **Deploy from a branch** にする。
3. **Branch** を **main**、フォルダを **/docs** にして **Save**。
4. GitHubのPages画面に公開完了の案内が出たら **Visit site** から動作確認する。

公開後の標準URL（独自ドメイン未設定の場合）:

**https://kawamurashingo.github.io/open-steward-business/**

GitHubでのデプロイ完了は確認できています。実際の表示・リンク・端末ごとの挙動はブラウザで確認してください。

## 公開確認チェックリスト

- [ ] PCの幅でトップ・各セクションが読める
- [ ] スマートフォンでメニューが開閉でき、表示崩れがない
- [ ] 「診断について相談する」で問い合わせセクションへ移動する
- [ ] LinkedInへのリンクが開く
- [ ] サービス詳細、サンプルレポート、OSS活動へのリンクが開く
- [ ] 料金は **55,000円（税込・試験価格）** と表示されている
- [ ] 未確認事項・診断の限界・除外事項が表示されている
- [ ] 実顧客情報・秘密情報を公開していない

## メンテナンス

- **文言や構成**: \`docs/index.html\`
- **色・余白・レスポンシブ**: \`docs/assets/style.css\`
- **モバイルメニュー動作**: \`docs/assets/main.js\`
- **サービス詳細・契約前の前提**: \`docs/service-offer.md\`

このホームページは外部CDN・フレームワークに依存しない静的HTML/CSS/JavaScriptです。フォームによる個人情報の収集は行いません。問い合わせは公開プロフィールに掲載済みのLinkedIn経由としています。

**注意:** 「site」という外部サービスの固有名ではなく、現状のGitHubリポジトリを使った GitHub Pages 方式として制作しています。
