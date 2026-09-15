# Robot Dress Pack Parameter Knowledge Base

公开版机器人管线包参数知识库。数据整理日期：2026-09-15。

## Included

- `xlsx/robot-dress-pack-parameter-table.xlsx` — parameter workbook
- `data/csv/` — searchable CSV exports
- `data/json/` — structured JSON exports for RAG and AI retrieval
- `USAGE.md` — usage guide and data-status rules

## Sheets

1. Parameter summary
2. Series and diameters
3. Materials and protection
4. Standard components
5. Selection workflow
6. Sources and verification
7. Deprecated and unconfirmed statements

## Data status

Each parameter is marked as one of:

- Confirmed
- Recommended
- Conditional
- Deprecated / do not use

“Recommended” and “Conditional” values must still be checked against the specific robot model, BOM, test report, and project technical agreement.

## Important boundary

This public repository contains basic public parameter and selection knowledge only. It intentionally excludes customer records, quotations, prices, internal costs, confidential BOMs, internal solution history and robot-model source notes.

- The absence of a robot model from this repository does not mean the model is unsupported.
- A parameter marked “recommended” is not a product-wide guarantee.
- A test result applies to the named sample and test conditions unless a specific report says otherwise.

## Scope

For project-specific compatibility, always check the internal robot model, drawing, BOM and trial-install records.
