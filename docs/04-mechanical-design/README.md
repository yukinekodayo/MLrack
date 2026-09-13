# 機構設計

歯車のみで動作する演算部分（重み付け・加算・閾値判定）と、そのCAD化方針をまとめています。

| ドキュメント | 内容 |
| --- | --- |
| [01-weight-unit.md](./01-weight-unit.md) | 重み付けユニット（完全固定式） |
| [02-input-unit.md](./02-input-unit.md) | 入力用ユニット（16段階・モータ8個） |
| [03-planetary-adder.md](./03-planetary-adder.md) | 遊星歯車7段（加算機構） |
| [04-threshold-unit.md](./04-threshold-unit.md) | 閾値判定機構（カム＋フラグ） |
| [05-cad-plan.md](./05-cad-plan.md) | CAD化方針（Fusion 360） |

## 未解決のクロスカット課題

- モジュール0.5（重み・入力ユニット）とモジュール1.0（遊星歯車）の接続部の設計
- 入力用ユニットのスリーブ機構の詳細設計

→ どちらも [../07-open-questions.md](../07-open-questions.md) 参照

