# Liquid Glass Header Spec 規則

- 本 repo 是 Module Spec git
- 產品為 LiquidGlassHeaderTemplate
- module id 為 `no1_liquid_glass_header`
- 本 repo 是已註冊空殼

## 多層配對

- Product git 承載產品元資訊
- Design git 尚未建立
- 本 repo 承載公開行為規格
- Impl git 承載 React Native 模板
- 配對以 `decision_framework_router` 的註冊表為準

---

## 內容邊界

- 空殼狀態屬於預期
- 公開 API 變動時補規格
- 使用方式變動時補規格
- 元件行為變動時補規格
- Model 規格放入 `no1_data_models/`
- View 規格放入 `no2_screens/`
- Logic 規格放入 `no3_logics/`

---

## 原生工作規則

- 任何改動先使用 `decision_framework_router`
- 所有 Spec 改動使用 `spec_writer`
- Markdown 改動使用 `universal_writing_linter`
- 行為變動要檢查 Impl
- 跨層 branch 名稱必須一致
- 配對 commit 內容必須一致

---

## 相容與漂移控制

- `AGENTS.md` 是本目錄的規則真相
- `CLAUDE.md` 只保留 Claude Code 入口
- 產品規則不得複製回相容入口
- 漂移檢查確認相容入口只含導向規則
