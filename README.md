# AI to Agent ・ VAC 任務九卡

> 企業導入 AI Agent 的九種任務地圖 —— 一套 8 步驟骨架，套進每一種工作場景。

以視覺化任務卡（Visual Agent Card）呈現九種常見企業任務中，AI Agent 的完整工作流程、
所需工具、以及**人必須接手的那一步**。

---

## 線上瀏覽

開啟 `index.html` 即可，或啟用 GitHub Pages 後訪問：

```
https://<your-username>.github.io/ai-to-agent-vac-task-9cards/
```

啟用方式：Repository → Settings → Pages → Source 選 `main` 分支的 `/ (root)`。

---

## 共通骨架

不管是剪影片、做簡報、跑報表還是查法規，Agent 的工作邏輯完全一樣：

| 階段 | 步驟 | 內容 |
|---|---|---|
| 🔵 Phase 1 前置理解 | 01–02 | 搞懂要做給誰、有什麼料 |
| 🟣 Phase 2 決策／處理 | 03–04 | 排結構、對齊資料 |
| 🟠 Phase 3 產出製作 | 05–06 | 生成內容與視覺 |
| 🟢 Phase 4 整合驗收 | 07–08 | 預覽、把關、人工核准 |

換的只是工具與產出物，骨架不變。

---

## 九張任務卡

| # | 任務 | 類型 | 檔案 |
|---|---|---|---|
| 00 | 系列總覽目錄 | 總覽 | `cards/00-series-index.html` |
| 01 | 剪影片 | 內容生成 | `cards/01-video-editing.html` |
| 02 | 行銷簡報 | 內容生成 | `cards/02-marketing-deck.html` |
| 03 | 短影音腳本 | 內容生成 | `cards/03-short-video-script.html` |
| 04 | 財務月報表 | 數據彙整 | `cards/04-finance-monthly.html` |
| 05 | 營運數據週報 | 數據彙整 | `cards/05-ops-weekly.html` |
| 06 | 競品分析 | 檢索稽核 | `cards/06-competitive-analysis.html` |
| 07 | 法規合規查核 | 檢索稽核 | `cards/07-regulatory-compliance.html` |
| 08 | 品質 QA 稽核 | 檢索稽核 | `cards/08-quality-qa-audit.html` |
| 09 | 研究配方輔助 | 研發探索 | `cards/09-formulation-research.html` |

---

## 導入判斷：Agent 該做到哪裡就停

| 任務類型 | Agent 負責 | 人一定要接手的地方 |
|---|---|---|
| **內容生成型** | 發想、草稿、套版、大量產出 | 品牌調性、療效與廣告用語把關 |
| **數據彙整型** | 取數、計算、比對、標記異常 | **歸因判斷**與對外數字的簽核 |
| **檢索稽核型** | 廣度蒐集、逐項比對、分級整理 | **來源查證**與合格與否的判定 |
| **研發探索型** | 文獻檢索、候選整理、風險提示 | **最終配方決策**、實驗與法規驗證 |

> Agent 越往下走越不能自己做決定。
> 導入 AI 的成敗，不在於 Agent 能做多少，而在於你有沒有把「人該接手的那一步」設計進流程裡。

---

## 技術說明

- 純靜態 HTML，**零相依套件**、零建置流程，開啟即可瀏覽
- 每張卡為單一自足檔案，可獨立分享、列印或轉存 PDF
- 響應式版面，桌機雙欄 / 行動裝置單欄
- 字型使用系統與 Google Fonts fallback，離線亦可正常顯示

### 轉存為圖片或 PDF

瀏覽器開啟卡片 → 列印（Ctrl / Cmd + P）→ 目的地選「另存為 PDF」，
或使用瀏覽器開發者工具的完整頁面截圖功能。

---

## 目錄結構

```
ai-to-agent-vac-task-9cards/
├── index.html          # 首頁（卡片索引）
├── README.md
├── .nojekyll           # 讓 GitHub Pages 直接輸出靜態檔
└── cards/
    ├── 00-series-index.html
    ├── 01-video-editing.html
    ├── 02-marketing-deck.html
    ├── 03-short-video-script.html
    ├── 04-finance-monthly.html
    ├── 05-ops-weekly.html
    ├── 06-competitive-analysis.html
    ├── 07-regulatory-compliance.html
    ├── 08-quality-qa-audit.html
    └── 09-formulation-research.html
```

---

## ⚠️ 使用聲明

本系列為**流程設計與教學參考**，非法律、醫療、財務或配方建議。
卡片中的工具名稱僅為示意，實際導入請依自身系統環境評估。

涉及**財報簽核、法規遵循、品質判定與產品開發**時，
務必由具資格之專業人員審查確認。第 09 張（研究配方輔助）
明列 Agent 的能與不能，請務必完整閱讀後再參考使用。

---

## 授權

尚未指定授權條款。若要開放他人使用，建議於 GitHub 建立 repo 時一併選擇
（教學素材常見選擇為 CC BY-NC-SA 4.0，程式碼部分則常用 MIT）。

---

**AI Coach 益力康陳董｜2026 AI to Agent**
用 AI 放大創意・用 Agent 輕鬆執行
