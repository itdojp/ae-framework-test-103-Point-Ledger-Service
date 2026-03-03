# Task (Benchmark) — Point Ledger Service

本リポジトリは input-only spec repo です。  
この `task.md` は、別リポジトリ/別工程（出力側）で生成・実装すべき内容を定義します。

## Inputs (this repo)

- `spec/`
- `assumptions.md`

## Outputs (generated elsewhere)

- 仕様に基づく Point Ledger Service の実装
- 機械可読な API 契約（例: OpenAPI）
- （任意）テスト/CI

## Acceptance Criteria (minimum)

- 取引登録と照会の基本ユースケースが成立する
- idempotency を含む基本整合が成立する（仕様の範囲）
