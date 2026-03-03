# Point Ledger Service — Input Spec Repo

本リポジトリは、ae-framework の **input-only spec repo** パターンに基づくテスト入力です。
ここには **仕様（人間可読）と上級工程で固定した前提**のみを保持し、実装・テスト・機械可読なAPI契約・CI・中間生成物は **出力（別リポジトリ/別工程）**として生成します。

方針のSSOT（一次情報）:
- `itdojp/ae-framework` の `docs/product/INPUT-ONLY-SPEC-REPO-PATTERN.md`

## Inputs (this repo)

- 仕様: `spec/`
- 実装タスク（出力定義）: `task.md`
- 前提/制約（上級工程）: `assumptions.md`

## Outputs (generated elsewhere)

- 実装コード、テスト、機械可読なAPI契約、CI、成果物（`artifacts/**`, `.ae/**`, `reports/**`）
