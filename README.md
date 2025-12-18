# Blue Monk Consulting - 公式Webサイト

## プロジェクト概要

株式会社ブルーモンクコンサルティングの公式Webサイトです。DXコンサルティングサービスを提供する企業として、企業情報やサービス内容を紹介する静的Webサイトです。

## 現在実装済みの機能

### ✅ 完成している機能

1. **レスポンシブデザイン**
   - デスクトップ、タブレット、スマートフォンに対応
   - ハンバーガーメニューによるモバイルナビゲーション

2. **ページセクション**
   - ヒーローセクション（トップビジュアル）
   - サービス紹介（4つのサービスカード）
   - 会社概要
   - お問い合わせフォーム

3. **インタラクティブ機能**
   - スムーススクロール
   - ハンバーガーメニューの開閉
   - スクロール時のヘッダー変化
   - サービスカードのフェードインアニメーション

4. **お問い合わせフォーム**
   - フォームバリデーション
   - 送信処理（仮実装）

## ファイル構成

```
.
├── index.html          # メインHTMLファイル
├── css/
│   └── style.css      # スタイルシート
├── js/
│   └── main.js        # JavaScript機能
└── README.md          # このファイル
```

## 機能エントリーポイント

### メインページ
- **パス**: `/index.html` または `/`
- **セクション**:
  - `#home` - ホーム（ヒーロー）
  - `#services` - サービス紹介
  - `#about` - 会社概要
  - `#contact` - お問い合わせ

## 技術スタック

- **HTML5**: セマンティックHTML構造
- **CSS3**: 
  - カスタムプロパティ（CSS変数）
  - Flexbox / Grid レイアウト
  - メディアクエリによるレスポンシブデザイン
  - スムーズなトランジション・アニメーション
- **JavaScript (Vanilla)**:
  - DOM操作
  - イベントハンドリング
  - Intersection Observer API
  - スムーススクロール
- **Google Fonts**: Noto Sans JP

## GitHub Pagesでの公開方法

### 1. GitHubリポジトリの作成
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### 2. GitHub Pagesの設定
1. GitHubのリポジトリページにアクセス
2. **Settings** タブをクリック
3. 左メニューから **Pages** を選択
4. **Source** で `main` ブランチを選択
5. **Save** をクリック

### 3. 公開URL
設定後、以下のURLでアクセス可能になります：
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## 未実装の機能

### 🔜 今後実装が推奨される機能

1. **お問い合わせフォームのバックエンド連携**
   - Formspree、Netlify Forms、またはGoogle Formsとの統合
   - メール送信機能の実装

2. **ブログセクション**
   - 技術記事やコンサルティング事例の掲載

3. **実績紹介ページ**
   - 過去のプロジェクト実績の追加

4. **多言語対応**
   - 英語版サイトの作成

5. **SEO最適化**
   - メタタグの最適化
   - sitemap.xmlの追加
   - robots.txtの作成

6. **アクセス解析**
   - Google Analyticsの導入

7. **OGP対応**
   - SNSシェア時の表示最適化

## 推奨される次のステップ

1. **お問い合わせフォームの実装**
   - Formspreeなどの無料サービスを利用してメール送信機能を実装
   - または、Netlify Formsでサーバーレス対応

2. **コンテンツの充実**
   - 実際の会社情報に更新
   - サービス詳細ページの追加
   - 実績・事例の追加

3. **GitHub Pagesへのデプロイ**
   - リポジトリ作成と公開設定
   - カスタムドメインの設定（必要に応じて）

4. **SEO対策**
   - メタディスクリプション、OGPタグの追加
   - Google Search Consoleへの登録

5. **アクセシビリティの向上**
   - ARIA属性の追加
   - キーボードナビゲーションの最適化

## ローカル開発

このサイトは静的HTMLなので、以下の方法で簡単に確認できます：

### 方法1: ブラウザで直接開く
```bash
# index.htmlをブラウザで開く
open index.html  # macOS
start index.html # Windows
```

### 方法2: ローカルサーバーを起動（推奨）
```bash
# Python 3の場合
python -m http.server 8000

# Node.jsのhttp-serverの場合
npx http-server -p 8000
```

その後、ブラウザで `http://localhost:8000` にアクセスします。

## ライセンス

© 2024 Blue Monk Consulting Co., Ltd. All rights reserved.

## 制作情報

- 制作日: 2024年
- 使用技術: HTML5, CSS3, JavaScript (ES6+)
- GitHub Pages対応: ✅
