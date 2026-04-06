# Ninkki Legal Pages

Ninkki アプリの利用規約・プライバシーポリシー・サポート・特定商取引法に基づく表記の
公開用HTMLです。GitHub Pagesで配信されます。

## 公開URL（予定）

GitHubにpushしてPagesを有効化すると、以下のURLでアクセス可能になります:

- `https://ym0320.github.io/ninkki-legal/` — 日本語トップ
- `https://ym0320.github.io/ninkki-legal/terms.html` — 利用規約（日本語）
- `https://ym0320.github.io/ninkki-legal/privacy.html` — プライバシーポリシー（日本語）
- `https://ym0320.github.io/ninkki-legal/support.html` — サポート（日本語）
- `https://ym0320.github.io/ninkki-legal/tokushoho.html` — 特定商取引法に基づく表記
- `https://ym0320.github.io/ninkki-legal/index-en.html` — English top
- `https://ym0320.github.io/ninkki-legal/terms-en.html` — Terms of Service (English)
- `https://ym0320.github.io/ninkki-legal/privacy-en.html` — Privacy Policy (English)
- `https://ym0320.github.io/ninkki-legal/support-en.html` — Support (English)
- `https://ym0320.github.io/ninkki-legal/index-ko.html` — 한국어 홈
- `https://ym0320.github.io/ninkki-legal/terms-ko.html` — 이용약관 (한국어)
- `https://ym0320.github.io/ninkki-legal/privacy-ko.html` — 개인정보처리방침 (한국어)
- `https://ym0320.github.io/ninkki-legal/support-ko.html` — 지원 (한국어)

## ファイル構成

```
ninkki-legal/
├── index.html           日本語トップ
├── index-en.html        English top
├── index-ko.html        한국어 홈
├── terms.html           利用規約（日本語）
├── terms-en.html        Terms of Service (English)
├── terms-ko.html        이용약관 (한국어)
├── privacy.html         プライバシーポリシー（日本語）
├── privacy-en.html      Privacy Policy (English)
├── privacy-ko.html      개인정보처리방침 (한국어)
├── support.html         サポート（日本語）
├── support-en.html      Support (English)
├── support-ko.html      지원 (한국어)
├── tokushoho.html       特定商取引法に基づく表記
├── style.css            共通スタイル
└── README.md            このファイル
```

## GitHub Pages 公開手順

1. **GitHub で新規リポジトリ作成**
   - リポジトリ名: `ninkki-legal`
   - 公開タイプ: **Public**（Publicでないと無料プランではGitHub Pagesが使えません）

2. **このフォルダをリポジトリにプッシュ**
   ```bash
   cd "ninkki-legal"
   git init
   git add .
   git commit -m "Initial commit: Ninkki legal pages"
   git branch -M main
   git remote add origin https://github.com/ym0320/ninkki-legal.git
   git push -u origin main
   ```

3. **GitHub Pages 有効化**
   - リポジトリの **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)** を選択
   - **Save**

4. **数分後**、上記URLでアクセス可能になります

5. **App Store Connect に登録する URL**
   - プライバシーポリシーURL: `https://ym0320.github.io/ninkki-legal/privacy.html`
   - サポートURL: `https://ym0320.github.io/ninkki-legal/support.html`
   - ※ サポートURLは日本語/英語/韓国語 それぞれのロケールで対応するURLを入力

## 更新方法

HTMLを編集して `git push` すれば、数秒で公開内容が更新されます。

## 販売業者情報

- 販売業者名: Yuta Nakayama
- お問い合わせ: ninkki.support@proton.me
- 所在地/電話: 特商法第11条第2項に基づき、消費者からの請求に応じて遅滞なく開示
