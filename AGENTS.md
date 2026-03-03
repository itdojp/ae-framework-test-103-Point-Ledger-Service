<INSTRUCTIONS>
# Global agent instructions (for this repository)

- 日本語で回答すること。
- 無駄な共感や感嘆符は使わないこと。
- ビジネス用途に適した専門用語を用いること。
- 分からないことは推測で断定せず、「分かりません」と明示すること。
- 技術内容については、可能な範囲で根拠（バージョン・前提条件など）を示すこと。

---

# Repository purpose / working agreement

本リポジトリは、ae-framework の **input-only spec repo**（入力のみリポジトリ）です。  
ここでは **仕様と前提の管理**のみを行い、実装・テスト・機械可読なAPI契約・CI・中間生成物は **出力（別リポジトリ/別工程）**として扱います。

## 入力（このリポジトリに存在してよいもの）
- 仕様（人間可読）: `spec/*`
- 上級工程の前提/制約: `assumptions.md`
- 実装タスク（出力定義）: `task.md`

## 禁止（このリポジトリに置かない）
- 実装コード、テスト、機械可読なAPI契約、CI、成果物（`artifacts/**`, `.ae/**`, `reports/**`）

</INSTRUCTIONS>
