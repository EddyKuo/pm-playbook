# PM Playbook — 產品經理決策手冊 2026

> 一本給在現場做決策的 PM 看的戰場筆記。43 章，覆蓋從問題探索到 AI 時代的完整 PM 工作週期。

---

## 這本書是什麼

PM Playbook 是一本**決策導向**的產品管理手冊。它不講方法論的定義，也不重複課本裡的 Agile 框架——它講的是那些在現場讓 PM 卡住的時刻：roadmap 被插單時怎麼辦、工程師說「規格不清楚」時真正的問題在哪、OKR 達成了但用戶流失了該怎麼覆盤。

每章遵循同一個弧線：

```
冷觀察         真問題         決策框架        踩坑 + 交付
──────         ──────         ──────          ──────
現場衝突        根因分析        可抄走的工具     模板 + 範例
```

章節裡的 Mermaid 工作流程圖、決策表、if-then 框架都可以直接拿去用。

---

## 誰應該讀這本書

### 主要讀者

| 讀者 | 適合的原因 |
|---|---|
| **初中階 PM（1–4 年）** | 補上從「做功能」到「做決策」的思維跳轉 |
| **轉職 PM（工程師/設計師背景）** | 快速建立 PM 的問題框架與跨職能溝通語言 |
| **Senior PM / Lead PM** | 作為團隊對齊的共同語言，或新 PM onboarding 教材 |

### 延伸讀者

| 讀者 | 適合的原因 |
|---|---|
| **SA / 系統分析師** | 搭配 SA/SD Playbook，理解 PM 端的決策邏輯與接口需求 |
| **Engineering Lead** | 理解 PM 的排序框架，減少需求衝突 |
| **Startup 創辦人** | Part I–III 可作為早期產品決策的快速參考 |

### 不適合的讀者

- 想了解 Agile 定義或 Scrum 認證考題 → 這本書不是教科書
- 想看純理論框架介紹 → 每章的核心是場景，不是定義

---

## 怎麼看這本書

### 原則：不必從頭讀

本書的 43 章設計為**可獨立閱讀**。每章章首有「前置閱讀」，章末有「Cross-References」，可以按需跳讀。

### 建議閱讀路徑

根據你的當前情境，選擇最適合的起點：

---

#### 路徑 A：全新 PM，建立基本功
> 適合：剛轉職或剛接手第一個產品的 PM

```
Ch 6（日常節奏）→ Ch 1（問題探索）→ Ch 2（Stakeholder）→ Ch 5（排序）
→ Ch 11（寫 Spec）→ Ch 16（Sprint 儀式）→ Ch 17（Release）→ Ch 28（向上匯報）
```

預計閱讀時間：8 章，約 6–8 小時

---

#### 路徑 B：正在做功能規劃的 PM
> 適合：即將開始一個新功能週期、需要從探索到交付的完整流程

```
Ch 1（問題探索）→ Ch 7（用戶研究）→ Ch 10（JTBD）→ Ch 11（寫 Spec）
→ Ch 12（AC 定義）→ Ch 13（MVP 邊界）→ Ch 14（Roadmap）→ Ch 18（GTM 協調）→ Ch 33（上線後覆盤）
```

預計閱讀時間：9 章，約 7–9 小時

---

#### 路徑 C：在跨職能協作卡住的 PM
> 適合：與工程師、設計師、SA、QA 溝通有摩擦

```
Ch 22（PM × SA）→ Ch 23（PM × 工程師）→ Ch 24（PM × 設計）
→ Ch 25（PM × QA）→ Ch 27（Escalation）→ Ch 28（向上匯報）
```

預計閱讀時間：6 章，約 4–5 小時

---

#### 路徑 D：需要改善指標和數據的 PM
> 適合：OKR review 時說不出產品影響了什麼

```
Ch 3（OKR）→ Ch 29（North Star）→ Ch 31（Product Analytics）→ Ch 30（A/B 實驗）
→ Ch 32（Retention）→ Ch 33（Post-Launch Review）
```

預計閱讀時間：6 章，約 5–6 小時

---

#### 路徑 E：正在規劃 AI 功能的 PM
> 適合：老闆要求加 AI 功能，或正在評估 LLM 產品策略

```
Ch 1（問題探索）→ Ch 10（JTBD）→ Ch 39（AI 功能決策）→ Ch 40（LLM 產品）
→ Ch 41（AI 倫理）→ Ch 37（隱私合規）
```

預計閱讀時間：6 章，約 5–6 小時

---

#### 路徑 F：完整閱讀（建議順序）
> 適合：系統性建立 PM 知識體系

按 Part I → VII 順序，每個 Part 之間休息後再繼續。
Part 之間有明確的銜接邏輯：

```
Part I  基礎（誰是 PM、日常是什麼、怎麼問問題）
   ↓
Part II 探索（怎麼做研究、怎麼寫得讓工程師信任）
   ↓
Part III 規劃（Roadmap、Sprint、上線前的所有事）
   ↓
Part IV 協作（和每個角色的接口語言）
   ↓
Part V  決策（大的戰略性選擇）
   ↓
Part VI 指標（怎麼知道自己做對了）
   ↓
Part VII AI 時代（下一個五年的新挑戰）
```

---

## 書的結構

| Part | 章節 | 主題 |
|---|---|---|
| I　產品基礎 | Ch 1–6 | 問題探索、Stakeholder、OKR、需求、排序、**PM 日常節奏** |
| II　探索與規格 | Ch 7–13 | 用戶研究、**競品情報**、**VoC 回饋**、JTBD、Spec、AC、MVP |
| III　規劃與路線圖 | Ch 14–21 | Roadmap、估算、風險、Release、**GTM 協調**、Sprint 儀式、Dual-Track |
| IV　跨職能協作 | Ch 22–28 | PM × SA/工程/設計/QA/Data、Escalation、**向上匯報** |
| V　產品決策 | Ch 29–33 | Build/Buy/Partner、技術債、平台思考、定價、Say No |
| VI　指標與成果 | Ch 34–38 | North Star、A/B 實驗、Analytics、Retention、Post-Launch |
| VII　AI 時代 | Ch 39–43 | AI 功能決策、LLM 產品、AI 倫理、隱私合規、Augmented PM |

粗體為相較傳統 PM 書籍新增的章節。

---

## 如何使用每章的工具

每章的 **§X.3 決策框架** 包含兩張圖和兩個工具，可以直接拿走：

1. **PM 工作流程圖**（Mermaid）— 複製到你的 Notion/Confluence 作為 SOP
2. **決策樹**（Mermaid）— 用於和團隊對齊決策邏輯
3. **決策表** — 貼進會議記錄或 PRD
4. **§X.5.1 填好範例** — 參考格式，替換成你自己的數字

---

## 與 SA/SD Playbook 的關係

本書與 [SA/SD Playbook](../book/SUMMARY.md)（系統分析與設計手冊）是配套關係：

| 同一個問題 | SA/SD 問 | PM Playbook 問 |
|---|---|---|
| 需求 | 系統邊界怎麼劃？ | 這個需求值不值得做？ |
| 架構 | 技術上怎麼實現？ | 怎麼跟 CEO 說為什麼要還技術債？ |
| 上線 | 系統能否穩定運行？ | Marketing/Sales/Support 準備好了嗎？ |

每章的 **Cross-References** 末尾都有對應的 SA/SD 章節連結。

---

## 聯絡作者

Eddy Kuo — `eddy_kuo@chiconypower.com`
