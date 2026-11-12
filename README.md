# 🏞️ 耶拿for花蓮Edu (`jena-edu`)

專精於將 **彼得·彼得森耶拿教育 (Jenaplan)** 四大支柱（對話、工作、遊戲、慶祝）與 **台灣 108 課綱**（總綱與國語文、英語文、數學、自然科學、社會、健康與體育、藝術、綜合活動、生活課程）、**學習扶助基本學習內容** 及 **花蓮在地地理、生態與原住民族文化智慧** 深度整合的跨平台 AI Agent Skill。

## 跨平台安裝與執行方式

本技能採用開放 Agent Skills 標準，適用於 **Google Antigravity**、**Gemini**、**ChatGPT Codex**、**Claude Code** 與 **OpenCode**：

* **Google Antigravity（IDE / App / CLI）**：
  * **全域安裝**（所有工作區皆可用）：
    ```bash
    git clone https://github.com/cjunyu6535-ops/jena-edu.git ~/.gemini/config/skills/jena-edu
    ```
  * **專案工作區安裝**（僅限單一專案）：
    ```bash
    git clone https://github.com/cjunyu6535-ops/jena-edu.git .agents/skills/jena-edu
    ```
  * **執行方式**：在對話中直接描述花蓮教學需求即會自動觸發，或於訊息框輸入 `/jena-edu` 手動呼叫。

* **Gemini（網頁版 Skills Manager）**：於 Skills Manager 介面匯入本專案之 `SKILL.md` 或技能壓縮檔。

* **Gemini CLI**：
  ```bash
  git clone https://github.com/cjunyu6535-ops/jena-edu.git ~/.gemini/skills/jena-edu
  ```

* **Claude Code**：
  ```bash
  git clone https://github.com/cjunyu6535-ops/jena-edu.git ~/.claude/skills/jena-edu
  ```

* **ChatGPT Codex**：
  ```bash
  git clone https://github.com/cjunyu6535-ops/jena-edu.git ~/.codex/skills/jena-edu
  ```

* **OpenCode**：
  ```bash
  git clone https://github.com/cjunyu6535-ops/jena-edu.git ~/.opencode/skills/jena-edu
  ```

## 檔案架構

* [`SKILL.md`](https://github.com/cjunyu6535-ops/jena-edu/blob/main/SKILL.md)：核心技能定義與五階段互動狀態機（含缺漏資料主動補齊與文化倫理檢核）。
* [`assets/lesson_templates.md`](https://github.com/cjunyu6535-ops/jena-edu/blob/main/assets/lesson_templates.md)：耶拿四大支柱（對話、工作、遊戲、慶祝）標準 Markdown 輸出模板。
* [`references/calculation_lookup_matrices.md`](https://github.com/cjunyu6535-ops/jena-edu/blob/main/references/calculation_lookup_matrices.md)：免代碼三步查表矩陣（混齡分組配比、區塊教學時間分配、`Seed / Sapling / Tree` 差異化任務階梯）。
* [`references/hualien_local_knowledge_base.md`](https://github.com/cjunyu6535-ops/jena-edu/blob/main/references/hualien_local_knowledge_base.md)：花蓮五大分區地理、生態、原住民族文化智慧與非挪用倫理紅線。
* `references/tw_108_curriculum_index.md`：台灣 108 課綱總綱、各領域編碼、基本學習內容（國/英/數）與官方參考網址索引。
* `references/jena_hualien_edu_spec.yaml.md`：完整功能與工作流之 YAML 規格說明書。

## 主要官方參考來源

* [國家教育研究院－十二年國教課程綱要](https://www.naer.edu.tw/PageSyllabus?fid=52)
* [CIRN 國民中小學課程與教學資源整合平臺](https://cirn.k12ea.gov.tw/)
* [學習扶助基本學習內容電子書 (TBT)](https://exam.tcte.edu.tw/tbt_html/index.php?mod=EbookNoSignIn/ebooklist_public)
* [花蓮縣原住民族教育資源中心](https://inde.hlc.edu.tw/)
* [Google Antigravity Agent Skills 官方文件](https://antigravity.google/docs/skills/)