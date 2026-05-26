# 株式会社新日本ツール × CHANEL Style — テストモック

https://www.sntool.ne.jp/ のサイトコンセプトを、[CHANEL.com/jp](https://www.chanel.com/jp/) のデザイン言語で
作り直したトップページ単体モック。

## 概要
- **クライアント**: 株式会社新日本ツール（埼玉県川越市）
- **元サイト**: https://www.sntool.ne.jp/
- **トーン**: 純白×モノクロ／大胆な余白／英文セリフ + 和文セリフ
- **構成**: HERO → PHILOSOPHY → COLLECTION(4) → NUMBERS → EDITORIAL → PORTFOLIO → JOURNAL → CTA → FOOTER
- **画像**: Unsplash 直リンク（プレースホルダー・HTTP 200 確認済み）

## ローカルプレビュー
```bash
cd assets/products/sntool-chanel-style
open index.html
```

## デプロイ先
- **Vercel**: https://sntool-chanel-style.vercel.app
- **GitHub**: https://github.com/kazui0907/sntool-chanel-style

## デザインのポイント

| 要素 | 取り入れ方 |
|------|----------|
| 純白×モノクロ | 背景白／テキスト #1a1a1a／アクセント黒のみ |
| 大胆な余白 | 各セクション上下 100〜140px |
| 二段組タイポ | Cormorant Garamond + Noto Serif JP |
| 斜体イタリック | 強調語のみ斜体 |
| ナンバリング | N°.01 / 01〜04 |
| 大判ビジュアル | フルスクリーン Hero + 4:5縦長カード |
| EDITORIAL | 左フル画像 + 右テキスト構成 |

## 注意
これは **テストモック** であり、本番運用前提ではありません。
画像はすべて Unsplash プレースホルダー。本制作時は実際の写真に差し替えること。

## 制作
- 制作日: 2026-05-26
- 制作: WEBクリエイティブ部「アオ」（LTSグループ AI社員システム）
- クライアントID: `sntool`
