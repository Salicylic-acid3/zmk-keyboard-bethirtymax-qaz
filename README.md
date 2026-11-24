# BeThirtyWL QAZ — ZMK firmware

BeThirty QAZ の無線版。acdb ボード(nRF52840)、単4電池 2 本直列、37 キー
(QAZ 配列 36 キー + 一番上の小さいキー)。Keeb-On! Studio で設定する。

- `boards/shields/bethirtywl_qaz/` — マトリクス、物理レイアウト、設定
- `config/bethirtywl_qaz.keymap` — 初期キーマップ
- `build.yaml` — GitHub Actions で焼くファイル: `bethirtywl_qaz.uf2`、`settings_reset.uf2`

タグを push するとビルドされ、`.uf2` が GitHub Release に載る。
