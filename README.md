<h1 align="center">嗨，我是 ozakboy 👋</h1>

<p align="center">
  <b>全端工程師</b> · C# / .NET 10 × TypeScript / Vue / Nuxt<br/>
  從一句商業構想到正式上線維運，一個人扛起完整產品落地。
</p>

<p align="center">
  <a href="https://ozakboy.github.io/CareerPortfolio/"><img src="https://img.shields.io/badge/個人履歷-CareerPortfolio-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="個人履歷"/></a>
  <a href="mailto:ozakboy@ozakboy.life"><img src="https://img.shields.io/badge/Email-ozakboy@ozakboy.life-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://line.me/ti/p/~chengxun0729"><img src="https://img.shields.io/badge/LINE-聯絡我-06c755?style=for-the-badge&logo=line&logoColor=white" alt="LINE"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ozakboy&label=Profile%20views&color=0e75b6&style=flat" alt="profile views"/>
</p>

---

## 🧑‍💻 關於我

```csharp
public sealed record Engineer
{
    public string Name      { get; } = "ozakboy";
    public string Role      { get; } = "全端工程師 / Full-Stack Engineer";
    public string Location  { get; } = "台灣 🇹🇼";

    public string[] Backend  { get; } = ["C#", ".NET 10", "ASP.NET Core", "EF Core", "Nuxt (Nitro)"];
    public string[] Frontend { get; } = ["TypeScript", "Vue 3", "Nuxt 4", "Pinia", "Tailwind CSS"];
    public string[] Database { get; } = ["PostgreSQL + PostGIS", "MSSQL", "SQLite"];
    public string[] DevOps   { get; } = ["Docker", "GitHub Actions", "AWS EC2 (Graviton)", "Nginx", "Cloudflare"];
    public string[] AI       { get; } = ["Claude Code", "MCP Server", "本地 LLM", "ComfyUI", "Gemini API"];

    public string Motto { get; } = "能上線、能維運、能長期活下去的系統，才是好系統。";
}
```

- 🔭 能獨立完成 **需求分析 → 架構設計 → 前後端開發 → 資料庫設計 → 容器化部署 → 雲端維運** 的完整產品週期
- 💼 實戰領域：**CRM 客戶經營、線上預約、社群評價平台、IoT 記錄型 PWA、品牌官網與 CMS**
- 🔗 深度整合 **LINE、Telegram、Meta (Facebook / IG / Threads)、Google、Gemini** 等外部生態
- 📈 具備 **微服務架構、高頻交易系統、即時報價串接（股票 / 期貨 / 虛擬貨幣）** 開發經驗
- 🤖 把 AI 帶進開發與產品：用 **Claude Code** 拆需求、寫程式、做 code review；開發 **MCP Server** 讓 AI Agent 直接操作業務系統，並堅持「人在迴圈」的審核設計
- 📦 持續維護 **20+ 個 .NET 開源套件**，堅持零第三方相依、完整測試與中英雙語文件

---

## 🛠️ 技術棧

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,ts,js,vue,nuxtjs,vite,tailwind,sass,bootstrap&perline=10" alt="語言與前端"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,sqlite,prisma,nodejs,docker,githubactions,aws,nginx,cloudflare,linux&perline=10" alt="資料庫與維運"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=windows,visualstudio,vscode,git,github,discord,py&perline=10" alt="工具"/>
</p>

| 類別 | 技術 |
| --- | --- |
| **後端** | C# / .NET 10、ASP.NET Core MVC / Web API、EF Core 10、BackgroundService、Nuxt Nitro |
| **前端** | Vue 3、Nuxt 3 / 4 (SSR / SSG)、Pinia、Vite、PrimeVue、Naive UI、Tailwind / DaisyUI、PWA (Workbox) |
| **資料庫** | PostgreSQL 16（PostGIS 地理查詢）、MSSQL、SQLite、Prisma、Drizzle ORM |
| **認證 / 安全** | JWT、Cookie、OAuth 2.0、DataProtection、bcrypt / argon2、DPAPI、AES-GCM |
| **DevOps** | Docker 多階段建置、Docker Compose、GitHub Actions → GHCR、AWS EC2（ARM64）、Nginx Proxy Manager、Let's Encrypt |
| **通訊整合** | LINE（Login / Messaging / LIFF / Rich Menu / Webhook）、Telegram Bot、Discord Bot、Web Push、SMTP、Gmail API |
| **AI 應用** | Claude Code、MCP Server（Model Context Protocol）、本地 LLM、ComfyUI、Gemini API |

---

## 📦 開源套件 · .NET 生態

> 全部以 **.NET 10** 為主、追求 **零第三方相依**、**`TreatWarningsAsErrors`** 零警告、離線測試全綠、**中英雙語 XML 文件**。

### 🧱 基礎建設

| 套件 | 說明 |
| --- | --- |
| [**Ozakboy.Core.Abstractions**](https://github.com/ozakboy/Ozakboy.Core.Abstractions) | 零相依基礎積木：精確 `decimal` 運算與明確的 `Result` / `Result<T>` 錯誤處理 |
| [**Ozakboy.Http**](https://github.com/ozakboy/Ozakboy.Http) | `HttpClient` 管線：簽章、限流、重試與日誌遮罩，只用 Microsoft 官方套件 |
| [**Ozakboy.WebSockets**](https://github.com/ozakboy/Ozakboy.WebSockets) | 為「連續跑好幾週」而生的 WebSocket 用戶端，只建在 BCL `ClientWebSocket` 上 |
| [**Ozakboy.Security**](https://github.com/ozakboy/Ozakboy.Security) | 憑證與敏感資料保護：DPAPI 加密、日誌遮罩、AES-GCM 設定檔加密 |
| [**OzaLog**](https://github.com/ozakboy/OzaLog) | 輕量本地檔案 logger，HFT 等級非同步管線，為加密貨幣 tick 流設計 |
| [**Ozakboy.Mvvm**](https://github.com/ozakboy/Ozakboy.Mvvm) | 精簡 MVVM 積木：`ObservableObject`、`RelayCommand`、防重複送出的 `AsyncRelayCommand` |

### 💬 通訊與通知

| 套件 | 說明 |
| --- | --- |
| [**Ozakboy.Line**](https://github.com/ozakboy/Ozakboy.Line) | LINE Login + Messaging API + Webhook，附 ASP.NET Core 認證方案與 **MCP 工具組** |
| [**Ozakboy.Notify.Telegram**](https://github.com/ozakboy/Ozakboy.Notify.Telegram) | Telegram Bot 告警：分級訊息、節流、429 處理，Bot Token 絕不進日誌 |
| [**Ozakboy.Gmail**](https://github.com/ozakboy/ozakboy.Gmail) | 輕量純非同步的 Gmail REST + Google OAuth 用戶端，不依賴 `Google.Apis` |
| [**Ozakboy.Mail**](https://github.com/ozakboy/ozakboy.Mail) | 一段設定、一次呼叫，應用程式寄信就這麼簡單 |

### 📈 TradeKit · 量化交易

| 套件 | 說明 |
| --- | --- |
| [**Ozakboy.TradeKit.Abstractions**](https://github.com/ozakboy/Ozakboy.TradeKit.Abstractions) | 交易所中立的衍生品交易抽象：訂單、倉位、K 線、訂單簿與交易規則 |
| [**Ozakboy.TradeKit.Binance**](https://github.com/ozakboy/Ozakboy.TradeKit.Binance) | 幣安 USDⓈ-M 永續合約用戶端，無第三方相依 |
| [**Ozakboy.TradeKit.Indicators**](https://github.com/ozakboy/Ozakboy.TradeKit.Indicators) | 技術指標：每個指標都有批次版與 **常數記憶體串流版**，全程 `decimal` |
| [**Ozakboy.Wpf.Charting**](https://github.com/ozakboy/Ozakboy.Wpf.Charting) | 高效能 WPF 金融圖表：萬根 K 線 60 FPS 平移縮放、指標線、交易標記 |

### 🇹🇼 TaiwanKit · 在地化工具

| 套件 | 說明 |
| --- | --- |
| [**Ozakboy.TaiwanKit.Ganzhi.NET**](https://github.com/ozakboy/Ozakboy.TaiwanKit.Ganzhi.NET) | 農曆、二十四節氣與干支四柱轉換（1901–2100），完全離線 |
| [**Ozakboy.TaiwanKit.TaiwanHolidays**](https://github.com/ozakboy/Ozakboy.TaiwanKit.TaiwanHolidays) | 台灣國定假日與補班日查詢，內嵌 2017–2027 政府行政機關辦公日曆，完全離線 |
| [**Ozakboy.TaiwanKit.TwIdValidator**](https://github.com/ozakboy/Ozakboy.TaiwanKit.TwIdValidator) | 身分證字號、統一編號、手機號碼驗證，附正規化與測試資料產生 |

### 🤖 AI

| 套件 | 說明 |
| --- | --- |
| [**Ozakboy.Ai.Abstractions**](https://github.com/ozakboy/Ozakboy.Ai.Abstractions) | 供應商中立的 LLM 抽象：問一個問題，拿回強型別物件 |
| [**Ozakboy.Ai.ClaudeCli**](https://github.com/ozakboy/Ozakboy.Ai.ClaudeCli) | 透過本機已安裝的 Claude Code CLI 取得結構化輸出，免 API Key |

### 🧰 其他工具

| 套件 | 說明 |
| --- | --- |
| [**DirectoryTreeGenerator**](https://github.com/ozakboy/DirectoryTreeGenerator) | 把任意目錄結構產生成帶圖示的 Markdown 樹狀文件 |
| [**Ozakboy.PageData**](https://github.com/ozakboy/ozakboy.PageData) | 支援 `List<T>` / `IQueryable<T>` / `IEnumerable<T>` 的彈性分頁 |
| [**Taiwan-news-crawlers**](https://github.com/ozakboy/Taiwan-news-crawlers) | C# 台灣新聞爬蟲，新聞資料物件化 |

---

## 🚀 精選作品

| 專案 | 說明 | 技術 |
| --- | --- | --- |
| 🌱 **Sower** | AI 驅動的多平台社群發文與商品上架平台：FB / IG / Threads / TikTok 排程發布，MCP Server 讓 AI 產稿送審、人工核准才上線 | .NET 10、Vue 3、PostgreSQL、MCP |
| 🚦 **幼明燈** | 幼兒園避雷與評價社群：政府開放資料管線、裁罰永久保存庫、PostGIS 地圖三色燈號、Gemini 白話摘要 | ASP.NET Core、PostGIS、Gemini、LINE |
| 🤝 **Cohort CRM** | 客戶經營平台：Meta 廣告名單 → LINE / Messenger 自動觸客 → 業務輪詢分配，微服務化並從 .NET 6 遷至 10 | .NET 10 微服務、Vue 3、PostgreSQL |
| 🌸 **Cellenya 妍雅** | 美容品牌官網 + 自助預約：時段計算引擎、多據點排班衝突檢測、LIFF 會員與分眾推播 | Nuxt 4、PrimeVue、Prisma、LINE |
| 🍼 **小奶瓶日記** | 新生兒共同照護 PWA：餵奶 / 睡眠 / 生長紀錄，Telegram 機器人快速記錄與定時提醒 | Nuxt 4 PWA、Drizzle、Web Push |
| 💰 [**LoanInsight 智貸見解**](https://loaninsight.ozakboy.life) | 全前端貸款試算與財務診斷，揭露真實 APR 並評估 DSR，零後端、不蒐集個資 | Nuxt、TypeScript |
| 🕹️ [**ArcadePin**](https://arcadepin.ozakboy.life) | 復古霓虹街機彈珠台，Canvas + ES6 模組，雲端 + IndexedDB 雙軌排行榜 | HTML5 Canvas、Serverless |

> 📄 更完整的專案細節與履歷，請見 👉 **[ozakboy.github.io/CareerPortfolio](https://ozakboy.github.io/CareerPortfolio/)**

---

## 📊 GitHub 統計

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ozakboy&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&locale=zh-tw" alt="GitHub Stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ozakboy&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&locale=zh-tw" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ozakboy&theme=tokyonight&hide_border=true&locale=zh_Hant" alt="GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ozakboy&theme=tokyo-night&hide_border=true" alt="Activity Graph" width="100%"/>
</p>

---

## 🤝 合作方式

- 🏗️ **從 0 到 1 打造產品**：聽懂商業需求，一手包辦前端、後端、資料庫與部署
- 🔄 **行銷自動化**：串起「廣告 → 名單 → 觸客 → 成交」，LINE / Telegram / Email 全通路
- 🧠 **導入 AI**：內容分類摘要、MCP 讓 AI Agent 接上你的系統、本地 LLM 讓資料不外流
- 🛡️ **穩定上線與長期維運**：Docker + CI/CD、反向代理、SSL 與監控
- 🔧 **老系統升級**：框架升版、資料庫遷移、效能優化

有想法想聊聊？歡迎透過 [Email](mailto:ozakboy@ozakboy.life) 或 [LINE](https://line.me/ti/p/~chengxun0729) 找我 ☕

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:6366f1&height=120&section=footer" alt="footer" width="100%"/>
</p>
