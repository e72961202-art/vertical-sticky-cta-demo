# Vertical Sticky CTA Demo

縦型追従CTA（画面右端・上下中央固定）のプロトタイプ。

## 2つのバリエーション

| ファイル | 構成 | デモURL |
|---|---|---|
| `index.html` | 購入はこちら ＋ もっと詳しく知りたい方はこちら（2ボタン） | [2ボタン版](https://e72961202-art.github.io/vertical-sticky-cta-demo/) |
| `single.html` | 購入はこちら のみ（1ボタン） | [1ボタン版](https://e72961202-art.github.io/vertical-sticky-cta-demo/single.html) |

## 共通仕様

- 画面右端の上下中央に固定
- 縦書きタブ型ボタン（`writing-mode: vertical-rl`）
- 右から slide-in アニメーション
- GTM dataLayer 計測イベント（impression / click / detail_click）
- セッション内dismiss機能（sessionStorage）
- スマホ / PC 両対応

## 動作モード

JS冒頭 `MODE` 変数で切替：

| 値 | 挙動 |
|---|---|
| `'always'` | ページ読み込み直後から常時表示（デフォルト） |
| `'scroll'` | 200pxスクロール後にフェードイン表示 |

## ライセンス

内部プロトタイプ用途。
