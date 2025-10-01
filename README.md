# アプリ開発ランディングページ

高級感のあるデザインのアプリ開発サービス向けランディングページです。

## デモ

[GitHub Pages でデモを見る](https://yossy0812.github.io/app-development-landing/app-development.html)

## 特徴

- **ラグジュアリーなデザイン**: ゴールドアクセントと洗練されたタイポグラフィ
- **高品質な画像**: Unsplashの厳選された写真を使用
- **パフォーマンス最適化**: 画像の遅延読み込み (Lazy Loading) 実装
- **スムーズなアニメーション**: スクロールに連動したフェードイン効果
- **レスポンシブデザイン**: モバイル、タブレット、デスクトップに対応
- **SEO対応**: セマンティックなHTML構造

## 技術スタック

- HTML5
- CSS3 (カスタムプロパティ、Grid、Flexbox)
- Vanilla JavaScript (Intersection Observer API)
- Google Fonts (Cormorant Garamond, Noto Serif JP)

## セクション構成

1. **ヒーローセクション**: キャッチコピーとCTAボタン
2. **選ばれる理由**: 4つの強み（ワイヤーフレーム提供、直接コミュニケーション、一気通貫サポート、適正価格）
3. **Webシステム**: マッチング、予約、e-ラーニング、ポータルサイト
4. **業務システム**: 顧客管理、在庫管理、受注管理、予約管理
5. **モバイルアプリ**: iOS/Android、LINE、ハイブリッド、Webアプリ
6. **開発の流れ**: 5ステップのプロセス説明
7. **ターゲット顧客**: DX推進企業、技術知識がない方、カスタムソリューション希望者
8. **お問い合わせ**: CTAセクション

## ローカルで実行

```bash
# リポジトリをクローン
git clone https://github.com/yossy0812/app-development-landing.git

# ディレクトリに移動
cd app-development-landing

# HTMLファイルをブラウザで開く
open app-development.html
# または
start app-development.html  # Windows
xdg-open app-development.html  # Linux
```

## カスタマイズ方法

### 色の変更

CSS変数を編集することで、サイト全体の色を簡単に変更できます:

```css
:root {
    --gold: #D4AF37;           /* ゴールドアクセント */
    --dark-gold: #B8941E;      /* ダークゴールド */
    --charcoal: #1a1a1a;       /* メインの暗色 */
    --light-charcoal: #2a2a2a; /* ライトチャコール */
    --cream: #FAF8F3;          /* クリーム背景 */
    --silver: #C0C0C0;         /* シルバー */
    --white: #FFFFFF;          /* ホワイト */
}
```

### 画像の変更

各セクションの画像は`<img>`タグで指定されています。URLを変更することで別の画像に差し替え可能:

```html
<img src="https://your-image-url.com/image.jpg"
     alt="説明テキスト"
     class="hero-image"
     loading="lazy">
```

### コンテンツの編集

- 見出し、説明文は各セクションのHTML内で直接編集
- フォントは`<head>`内のGoogle Fontsリンクで変更可能
- レイアウトはCSSのGrid/Flexboxで調整

## パフォーマンス

- **Lighthouse スコア目標**: Performance 90+
- **画像最適化**: WebP形式推奨、適切なサイズにリサイズ
- **遅延読み込み**: Intersection Observer APIを使用
- **Critical CSS**: インライン化を検討

## ブラウザ対応

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## デプロイ

### GitHub Pages

```bash
# gh-pagesブランチを作成してデプロイ
git checkout -b gh-pages
git push origin gh-pages
```

Settings > Pages > Source で `gh-pages` ブランチを選択

### Netlify / Vercel

1. GitHubリポジトリを接続
2. ビルド設定不要（静的HTML）
3. `app-development.html` をルートに設定

## ライセンス

MIT License

## クレジット

- **フォント**: Google Fonts (Cormorant Garamond, Noto Serif JP)
- **画像**: Unsplash (商用利用可能)
- **開発**: Claude Code

## お問い合わせ

ご質問や改善提案は [Issues](https://github.com/yossy0812/app-development-landing/issues) からお願いします。
