# 模型可以下載，學習不能外包

深度導讀 Andrew Ng 與 Susan Athey 在世界銀行《World Development Report 2026》場合的 46 分鐘爐邊對談（YouTube：[World Development Report 2026: Fireside Chat with Andrew Ng - Making AI Work for Development](https://www.youtube.com/watch?v=WmgPAOIhrko)）。對談談開放權重模型、聊天機器人與學習、可驗證任務、任務拆解，以及給開發中國家的政策建議。

**狀態：已發布（2026-10-11）。** 公開 repo：https://github.com/lushinshang/andrew-ng-wdr-2026-ai-for-development　線上閱讀：https://lushinshang.github.io/andrew-ng-wdr-2026-ai-for-development/

## 200字介紹

Andrew Ng 與 Susan Athey 在世界銀行《World Development Report 2026》場合的 46 分鐘對談，談 AI 對開發中國家的意義。Ng 認為開放權重模型讓資源不多的國家也能擁有、調整、不被斷供；聊天機器人擅長把事情做完，卻不擅長讓人學會，教學要從一對多走向一對一；AI 在可驗證任務上進步很快，需要判斷的任務差距可能更大；工作拆成任務後，被自動化的部分變便宜，剩下需要人的部分更值錢。導讀把 Ng 的看法與一手資料分開標示，並對照 OpenAI 與 Hugging Face 事件的官方報告。

## 檔案

| 檔案 | 說明 |
|---|---|
| `andrew-ng-wdr-2026-ai-for-development.md` | 正式導讀 Markdown |
| `index.html` | 獨立網頁，可直接雙擊開啟；CSS／JS 內嵌，圖片為相對路徑，不依賴外部函式庫 |
| `images/web/` | 網頁用 WebP：4 組導讀示意圖，每組 16:9＋9:16；另有社群預覽圖 `og_1200x630.png` |
| `share_post.md` | 社群分享文 |

圖片說明：4 組圖為導讀者依對談內容整理繪製的示意圖，不是對談現場投影片；圖中比例（「約三到四成」「約六成」）是 Ng 的口頭舉例，不是統計數字。

## 原始資料

- 類型：影片（對談）
- 標題：World Development Report 2026: Fireside Chat with Andrew Ng - Making AI Work for Development
- 網址：https://www.youtube.com/watch?v=WmgPAOIhrko
- 長度：約 46 分 42 秒；英文

## 重要來源

導讀中 Ng 與 Athey 的說法皆出自上述影片；本文另補的一手資料如下，每項在文中都有連結：

- 世界銀行：[WDR 2026: The Promise of Artificial Intelligence](https://www.worldbank.org/en/publication/wdr2026)（2026-08-04 發表）
- Stanford GSB：[WDR 2026 活動頁](https://www.gsb.stanford.edu/events/world-development-report-2026-promise-artificial-intelligence)（列出 Athey 為學術共同負責人之一）
- OpenAI：[OpenAI–Hugging Face Incident Technical Report](https://cdn.openai.com/pdf/67869394-cb91-4c12-888c-5cbd85c7814c/OpenAI-Hugging-Face%20Incident-Technical-Report.pdf)
- Hugging Face：[Anatomy of a Frontier Lab Agent Intrusion](https://huggingface.co/blog/agent-intrusion-technical-timeline)（2026-07-27）
- Coursera：[Coursera invests in LearnVector](https://blog.coursera.org/coursera-invests-in-learnvector-to-build-the-future-of-ai-native-learning/)（2026-07-28）
- 新加坡 GovTech：[AI and Data in Singapore's Government](https://www.tech.gov.sg/about-us/what-we-do/govtech-role-in-digital-transformation-for-the-public-sector/ai-and-data-in-singapore-government/)
- PNAS（本文補充，非 Ng 所引）：Bastani 等人，[doi.org/10.1073/pnas.2422633122](https://doi.org/10.1073/pnas.2422633122)

## 查證限制

- Ng 與 Athey 的多數論點是個人看法與觀察（遊說動機、職缺上升、研究結果、可驗證任務的差距），導讀照此標示，沒有替他們背書。
- Ng 沒有點名的書與研究，導讀不代為補上。
- Athey 提到的 Stanford 助教口頭報告實驗，她說尚未發表，導讀只轉述她的描述。
- 「約 1,200 個 agent」是 Ng 提到的媒體標題數字；OpenAI 技術報告中找不到這個數字，各家報導的數量也不一致，導讀未採用。
