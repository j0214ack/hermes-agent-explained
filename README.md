# Hermes Agent 架構解說（互動式）

針對開源專案 [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) 的互動式架構解說。每頁都是 self-contained 的 HTML（CSS／JS 全內嵌、零外部相依），用「概念先行（共通語彙）＋ 實體圖（class diagram）＋ 點卡片看細節」的方式講清楚 Hermes 的內部結構。每個 `file:line` 都連到原始碼的 GitHub 永久連結。

> 快照版本：**Hermes v0.17.0 · commit `2a10b83`（2026-06-22）**。所有原始碼連結都用這個 commit 的 GitHub permalink，pin 死在當下版本，行號永遠對得上、連結不會失效。Hermes 發版很快，日後新版架構可能跟本文不同（本文是該時間點的快照）。
> 內容為繁體中文（技術詞保留英文）。獨立整理、非官方文件。

## Live

開 GitHub Pages 直接看（互動）：<https://j0214ack.github.io/hermes-agent-explained/>

或 clone 後直接用瀏覽器開 `index.html`。

## 頁面

- `index.html` — 總覽（共通語彙 ＋ 架構全圖）
- `gateway.html` — Gateway 與 API server
- `agent-learning.html` — Agent 核心與學習子系統（memory／skills／curator）
- `tools-mcp.html` — Tools 與 MCP
- `providers.html` — 模型 Providers
- `state.html` — State 與持久層

---

整理：陳展佑 Yo
