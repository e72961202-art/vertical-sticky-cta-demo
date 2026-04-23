# Vertical Sticky CTA Demo

縦型追従CTA（画面右端・上下中央固定）のプロトタイプ。2種類のCTA（主CTA + 副CTA）を縦に並べ、スクロール時も画面右端中央に追従します。

## 機能

- 画面右端の上下中央に固定
- 縦書きタブ型ボタン（`writing-mode: vertical-rl`）
- 主CTA（塗り）＋ 副CTA（白＋枠線）の2段構成
- 右から slide-in アニメーション
- GTM dataLayer 計測イベント（impression / click / detail_click）
- セッション内dismiss機能（sessionStorage）
- スマホ/PC 両対応

## 動作モード

JS冒頭 `MODE` 変数で切替：

| 値 | 挙動 |
|---|---|
| `'always'` | ページ読み込み直後から常時表示（デフォルト） |
| `'scroll'` | 200pxスクロール後にフェードイン表示 |

## デモ

index.html をブラウザで開くだけで動作確認できます。

## ライセンス

内部プロトタイプ用途。
