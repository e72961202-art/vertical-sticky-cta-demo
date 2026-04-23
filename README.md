# Sticky CTA Demo

アンケートLP用の追従CTAプロトタイプ集。3つのバリエーションを用意。

## バリエーション一覧

| ファイル | 配置 | 構成 | デモURL |
|---|---|---|---|
| `index.html` | 右端・上下中央（縦型タブ） | 購入＋詳細（2ボタン） | [2ボタン縦型](https://e72961202-art.github.io/vertical-sticky-cta-demo/) |
| `single.html` | 右端・上下中央（縦型タブ） | 購入のみ（1ボタン） | [1ボタン縦型](https://e72961202-art.github.io/vertical-sticky-cta-demo/single.html) |
| `header.html` | 画面上部（追従ヘッダー） | 購入＋詳細（2ボタン） | [追従ヘッダー](https://e72961202-art.github.io/vertical-sticky-cta-demo/header.html) |

## 共通仕様

- `position: fixed` で画面に固定・スクロール追従
- 右から / 上から slide-in アニメーション
- GTM dataLayer 計測イベント内蔵
- スマホ / PC 両対応（viewport-fit=cover・セーフエリア対応）
- 動作モード `'always'`（常時表示）/ `'scroll'`（200pxスクロール後出現）切替可

## 見比べ観点

| | 縦型タブ | 追従ヘッダー |
|---|---|---|
| LP本体への干渉 | 右端のみ・軽微 | 上部を常時占有・やや強い |
| 主CTA/副CTAの存在感 | 縦2段で控えめ | 横並びで明確な選択 |
| 向き | 長尺アンケートLP | 記事型LP・検討層多いLP |

## ライセンス

内部プロトタイプ用途。
