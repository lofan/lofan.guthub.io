# PromptGen (Stable Verion R17, R25)
This is a single html file helping Prompt gen. Remember click the AI button, Ctrl-V Paste the prompt in new broser window.
* 🔗 AI-Bridge 跳板：點擊任何 AI 平台按鈕，系統會先幫你複製當前編輯器內容，然後直接開新視窗讓你黏貼測試。
* 📂 多維度分類：新增零件時，只要輸入相同的「分類名稱」（例如：👤 角色），系統就會自動把它們歸類到同一個手風琴文件夾中。
* 📦 摺疊式介面：左側分類預設可以點擊展開，讓你在擁有數十個零件時，介面依然清爽。
* 🔧 管理器一體化：底部直接提供分類、名稱、內容三個欄位，輸入完即刻「入庫」。
* 完全自定義：下方設有新增區，隨時填入標籤名（標題）同 Prompt 內容，按一下就永久保存。
* 標籤化刪除：每個零件右上角都有個細細嘅 ✕，撳一下就可以將舊零件踢走，保持介面簡潔。
* 持久化儲存：所有零件都直接存喺你部電腦嘅 Browser 度，即使你關閉網頁再開，你嘅個人庫存都仲喺度。
* 🌍 六國語言翻譯列：重新加入繁中、英、日、德、韓、法翻譯功能，方便跨語言優化 Prompt。
* 時光機 + 零件庫：左側同時管理版本紀錄與 v1.4 的零件模板。
* AI 快速跳板：中上方六大 AI 按鈕，點擊即複製並跳轉測試。
* 🛡️ 市場與備份：具備 Delete 刪除功能，並支援跨裝置 JSON 導入/導出。
* 🌗 智能環境切換：完整的 Dark Mode / Light Mode，保護長時間工作的視力。
* [Good Prompt Guide ](promptguide.md)  Chatbot - R.T.C.R.O.S. Image - F.R.A.M.E. Video - S.A.M.E.

# 比較六個LLM: Claude、Perplexity、Grok、ChatGPT、DeepSeek、Gemini
下面用 2026 年的大致情況，幫你用中文比較這六個系統：Claude、Perplexity、Grok、ChatGPT、DeepSeek、Gemini。  

## 一句總結  
- 個人聊天 /寫作體驗：Claude、ChatGPT、Gemini 比較均衡。  
- 搜尋與研究：Perplexity、Grok（尤其是 X 上的即時資訊）。  
- 價格效能比：DeepSeek 非常便宜、算力強，研究圈很熱門。  
- 多模態創作（圖、影片）：Grok、Gemini、ChatGPT 都有很強方案。  

***

## 1. 基本定位與優勢  

| 產品 | 公司/來源 | 核心定位 (2026) | 代表優勢 |
| --- | --- | --- | --- |
| Claude | Anthropic | 通用聊天、寫作、程式、文件處理 | 對話溫和穩健、長文理解很好 [glbgpt](https://www.glbgpt.com/hub/claude-ai-plans-2026/) |
| Perplexity | Perplexity AI |「帶搜尋」的 AI 助理 / 研究工具 | 強網路搜尋 + 多模型並行檢驗 (Model Council、Deep Research) [datastudios](https://www.datastudios.org/post/perplexity-new-features-and-use-cases-in-march-2026) |
| Grok | xAI | 與 X（Twitter）深度整合的即時 AI | 即時追蹤 X 上資訊、口吻較直白、有影像/影片生成 Grok Imagine [skywork](https://skywork.ai/skypage/en/grok-ai-real-time-model-guide/2032304113992433664) |
| ChatGPT | OpenAI | 大眾化聊天 / 創作 / 程式 | GPT-5 系列、多插件與自訂 GPT、生態最大 [eesel](https://www.eesel.ai/blog/chatgpt-pricing) |
| DeepSeek | DeepSeek-AI (中國) | 高性價比、強推理/程式 | V3/V3.2 在數學、程式、推理上追平或超過 GPT-4.5，成本低 [zilliz](https://zilliz.com/blog/why-deepseek-v3-is-taking-the-ai-world-by-storm) |
| Gemini | Google | 深度整合 Google 服務的 AI | 和 Gmail/Docs/Drive/Search、Android 整合，1M token 長上下文 [crazyrouter](https://crazyrouter.com/en/blog/gemini-advanced-review-worth-it-2026) |

***

## 2. 價格＆方案（以個人用戶為主）  

> 註：實際地區價格可能有差異，下面是主流報價級距。  

| 產品 | 免費版 | 個人付費主力方案 | 大致價格 (月) | 亮點 |
| --- | --- | --- | --- | --- |
| Claude | 有 Free | Claude Pro | 約 20 美元，可用最新 Claude 4.x 系列 [glbgpt](https://www.glbgpt.com/hub/claude-ai-plans-2026/) |
| Perplexity | 有 Free | Perplexity Pro / Max | 類似 20 美元起（依地區），可用 GPT‑5.x、Claude、Gemini 等多模型 [datastudios](https://www.datastudios.org/post/perplexity-new-features-and-use-cases-in-march-2026) |
| Grok | 有部分免費（視 X 方案） | SuperGrok 類方案 | 約 30 美元級距，被定位為 X 高階訂閱的一部分 [gamsgo](https://www.gamsgo.com/blog/google-gemini-pro) |
| ChatGPT | 有 Free | Plus / Pro | Plus 約 20 美元，Pro 約 200 美元，Team 約 25–30/人/月 [eesel](https://www.eesel.ai/blog/chatgpt-pricing) |
| DeepSeek | 有免費 Web & API | API 為主 | 單價遠低於 GPT 同級，主打「GPT‑4 級但便宜很多」 [zilliz](https://zilliz.com/blog/why-deepseek-v3-is-taking-the-ai-world-by-storm) |
| Gemini | 有 Free | Gemini Advanced / Google One AI Premium | 約 19.99 美元/月，含 Gemini 2.5 Pro/3 Pro，1M token 上下文 [crazyrouter](https://crazyrouter.com/en/blog/gemini-advanced-review-worth-it-2026) |

***

## 3. 功能側重（聊天、搜尋、研究、程式、文件）  

### 日常聊天 / 寫作  
- Claude：語氣自然、偏溫和，長篇寫作、改稿、總結表現很**穩定**。 [glbgpt](https://www.glbgpt.com/hub/claude-ai-plans-2026/)
- ChatGPT：創意寫作、角色扮演、教學資源豐富，插件 / 自訂 GPT 生態完整。 [eesel](https://www.eesel.ai/blog/chatgpt-pricing)
- Gemini：和 Google 帳號、Android、Chrome 配合，用起來很順手。 [crazyrouter](https://crazyrouter.com/en/blog/gemini-advanced-review-worth-it-2026)

### 搜尋 / 研究  
- Perplexity：問問題時自動幫你搜尋網路、整合多個來源做報告，有 Deep Research、Model Council，會標來源。 [datastudios](https://www.datastudios.org/post/perplexity-new-features-and-use-cases-in-march-2026)
- Grok：重點是「即時」和 X 內容，追蹤熱門新聞、社群輿論特別方便。 [skywork](https://skywork.ai/skypage/en/grok-ai-real-time-model-guide/2032304113992433664)
- Gemini：有 Deep Research、與 Google Search 結合的功能，對學術/技術資料也不錯。 [finout](https://www.finout.io/blog/gemini-pricing-in-2026)

### 程式 / 推理 / 數學  
- DeepSeek：V3 / V3.2 對數學、競賽題、程式、工具調用非常強，在多個官方 benchmark 上超過 GPT-4.5，同時計價很低。 [zilliz](https://zilliz.com/blog/why-deepseek-v3-is-taking-the-ai-world-by-storm)
- ChatGPT：GPT‑5 系列在程式輔助、debug、生態工具（Code Interpreter 類功能）仍然很好用。 [intuitionlabs](https://intuitionlabs.ai/articles/chatgpt-plans-comparison)
- Claude：在閱讀大型程式碼庫、長文件 + 程式混合任務上也有優勢。 [glbgpt](https://www.glbgpt.com/hub/claude-ai-pricing-2026-the-ultimate-guide-to-plans-api-costs-and-limits/)

### 多模態（圖像/影片）  
- Grok：有 Grok Imagine，可生成高解析度影像與影片，並規劃未來 AI 影片、機器人整合等。 [en.wikipedia](https://en.wikipedia.org/wiki/Grok_(chatbot))
- Gemini：支援圖片理解、影片、以及 Veo 等多媒體模型，放在 Google AI Pro/Ultra 中。 [crazyrouter](https://crazyrouter.com/en/blog/gemini-advanced-review-worth-it-2026)
- ChatGPT：隨 GPT‑5 系列有穩定的圖片理解與生成（依地區開放程度而定）。 [userjot](https://userjot.com/blog/chatgpt-pricing-2025-plus-pro-team-costs)

***

## 4. 適合什麼類型的用戶？  

| 需求 | 比較適合的選擇 | 說明 |
| --- | --- | --- |
| 想要「問了就幫我找資料+附來源」 | Perplexity | 內建搜尋、引用來源、深度報告模式，很適合寫報告或技術研究 [datastudios](https://www.datastudios.org/post/perplexity-new-features-and-use-cases-in-march-2026) |
| 常追 X/Twitter 熱點、關心即時輿論 | Grok | 和 X 深度綁定，能看到平台最新動態與貼文脈絡 [skywork](https://skywork.ai/skypage/en/grok-ai-real-time-model-guide/2032304113992433664) |
| 長篇文字整理、閱讀 PDF、寫作 | Claude | 長文處理能力與語氣體驗好，中文英文都不錯 [glbgpt](https://www.glbgpt.com/hub/claude-ai-plans-2026/) |
| 想要一個「什麼都能玩」的大眾款 | ChatGPT | 生態最大，自訂 GPT 多，教學資源極多 [eesel](https://www.eesel.ai/blog/chatgpt-pricing) |
| 想省錢又要強推理/程式 | DeepSeek | 高推理表現 + 低價格，目前在技術圈很熱門 [zilliz](https://zilliz.com/blog/why-deepseek-v3-is-taking-the-ai-world-by-storm) |
| 深度使用 Google 生態 (Gmail/Docs/Drive/Android) | Gemini | 與 Google 服務整合最緊密 [crazyrouter](https://crazyrouter.com/en/blog/gemini-advanced-review-worth-it-2026) |

***

## 5. 依你情境給建議  

如果你只是一般個人使用、預算有限，可以考慮：  
1. 日常聊天 + 創作：用 ChatGPT Free/Plus 或 Claude Free/Pro。ChatGPT 生態比較大，Claude 寫作體驗比較柔和。 [screenapp](https://screenapp.io/blog/claude-ai-pricing)
2. 找資料 / 寫報告：搭配 Perplexity 免費版先試，有需要再升級 Pro，因為它會自動幫你搜尋並附上連結。 [youtube](https://www.youtube.com/watch?v=mbKuAXrmrPU)
3. 程式 / 理工科：如果有機會用 DeepSeek（例如透過 API 或特定平台），它在數學和程式的表現與價格都非常有優勢。 [siliconflow](https://www.siliconflow.com/articles/en/the-best-deepseek-ai-models-in-2025)
4. 重度 Google 使用者：考慮 Gemini Advanced（Google One AI Premium），一個訂閱同時給你雲端空間和高階模型。 [gamsgo](https://www.gamsgo.com/blog/google-gemini-pro)


