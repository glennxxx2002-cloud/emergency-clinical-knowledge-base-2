# 急診臨床知識庫

This is a structured emergency medicine knowledge base designed for rapid bedside reference, ongoing education, and continuous protocol updates.

## Purpose

- Organize high-yield emergency medicine topics into a practical, searchable format.
- Support bedside clinical reasoning, teaching, and iterative protocol-aware updates.

## Scope

- Resuscitation and critical care
- Chief-complaint-based emergency evaluation
- Disease-specific emergency management
- ACLS 2025 topic modules
- Procedures, medications, and appendices

## Use Cases

- Rapid review before or during shifts
- Teaching residents, students, and staff
- Building local protocol-aware emergency references
- Continuous personal knowledge management in emergency medicine

## 中文說明

這是一套以急診臨床工作流程為核心的知識庫骨架，目標是讓常見主訴、危急處置、程序、藥物與流程能快速查找、持續維護。

## 使用原則

1. 每個主題盡量維持固定格式，方便快速掃描。
2. 內容以臨床決策支援為主，不取代正式指南、院內規範或上級醫師判斷。
3. 所有治療劑量、流程與適應症，正式使用前都應再對照最新指引與院內政策。

## 建議結構

- `INDEX.md`：總索引與入口。
- `templates/`：條目模板。
- `01_危急處置/`：如 ACLS、敗血症、休克、呼吸衰竭。
- `02_主訴導向/`：如胸痛、腹痛、呼吸困難、意識改變。
- `03_疾病主題/`：如 STEMI、DKA、中風、上消化道出血。
- `04_流程與檢查/`：如初級評估、影像、實驗室、超音波。
- `05_藥物/`：急診常用藥物速查。
- `06_程序/`：插管、胸管、中心靜脈導管、鎮靜。
- `07_附錄/`：縮寫、評分工具、參考來源。

## 下一步建議

- 先補齊最常見 20 個急診主訴。
- 每個條目加入院內流程、聯絡方式與轉介標準。
- 建立版本更新紀錄，避免過期內容持續被使用。

## Git 與同步建議

- 建議把整個資料夾作為單一 Git repository 維護。
- 遠端建議使用 GitHub private repository，方便跨電腦同步與版本追蹤。
- 若使用 Obsidian，可同步整個資料夾，但把本機工作區設定留在 `.gitignore`。
