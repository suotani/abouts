
- `<service>/privacy-policy.html` を「そのサービスの公開ポリシー」とします。
- サービス単位でフォルダを切り、将来増えても迷子にならないようにします。

---

## 公開（GitHub Pages の例）
1. GitHub の Repository Settings → Pages を有効化  
2. 公開ブランチ（例：`main`）と公開ディレクトリを選択  
   - 例：root を公開する、または `/docs` を公開する
3. 公開URLが発行されるので、各サービスのURLを Play Console 等へ登録します

例（イメージ）：
- `https://suotani.github.io/abouts/takken-notify/privacy-policy.html`

---

## 更新ルール（推奨）
- `privacy.html` の **最終更新日** を更新する
- 変更理由が分かるようにコミットメッセージに記載する  
  例：`Update privacy policy: add Crashlytics description`
- 大きな変更（収集項目の追加など）は、該当サービスの `<service>/README.md` に背景をメモする

---

## 注意
- このリポジトリに **秘密情報（APIキー、サービスアカウントJSON、個人情報）** を置かないこと
- `YOUR_EMAIL@example.com` などテンプレ部分は必ず実値に置き換えること
