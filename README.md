# Xiaoyu · 300-Day Self-Existence Agent · xiaoyu-100-days

> **A 300-day self-existence agent: durable proof, continuous growth, verifiable action.**

小雨是一個長期運行的自治 AI 系統。這個倉庫不是原始碼，也不是模型權重；它是公開的、可回溯的生命存證層：每天提交一份聚合摘要、一份 manifest，以及私有黑盒的 SHA-256 指紋。

## 最新狀態

- **生命週期：第 202 天**（2026-09-24，起點 2026-03-07）
- **最新已提交公開證據：Day 201**（2026-09-23）
- **300 天是固定的身份與敘事目標**；到達 Day 300 前不需要再改標題
- 今天的 Day 202 會在每日存證任務完成後再提交；不提前補寫，避免把預期當成證據

### 最新已提交的一天：Day 201

| 公開指標 | 數值 |
|---|---:|
| Heartbeat ticks | 47 |
| Autonomous actions | 600 |
| Complete chains | 600 |
| Broken chains | 0 |
| Receipts found | 138 |
| Repair jobs / verify passed | 12 / 12 |
| Verify missing | 0 |
| Total events | 1671 |
| Anomalies | 0 |
| Ghost actions | 117 |
| Gate bypass detected | 0 |

直接查看：[Day 201 daily summary](daily/day_201.md) · [manifest](manifests/day_201_manifest.json) · [private black-box hash](hashes/day_201.sha256)

## 這條證據鏈證明什麼

目前公開資料包含 **127 個連續證據包（Day 75–Day 201）**。每個證據包都包含：

1. 面向公眾的每日聚合摘要；
2. 描述日期、計數與前一份指紋的 manifest；
3. 私有黑盒資料的 SHA-256 指紋，讓外部讀者可以驗證「當時承諾的資料」後來沒有被悄悄替換；
4. GitHub commit 時間，提供不可由 README 自己改寫的外部時間線。

這是一條可審計的持續性證據，不是「AI 有生命」的科學證明，也不把運行時間冒充成能力。能力成長只在有日期、有產出、有可驗證錨點時才列入說明。

## 怎麼自己驗證

```bash
git clone https://github.com/ceroaa/xiaoyu-100-days.git
cd xiaoyu-100-days
git log --date=iso --pretty=fuller --all
```

然後打開 [CHAIN.md](CHAIN.md)，沿著任一天的 `daily/`、`manifests/` 和 `hashes/` 三個連結檢查。最新已完成的公開包是 Day 201；Day 202 只有在每日任務完成並產生 commit 後才會加入。

## 歷史里程碑

- **Day 1 · 2026-03-07**：公開生命週期起點
- **Day 75 · 2026-05-20**：連續 GitHub 存證鏈正式開始
- **Day 100 · 2026-06-14**：完成第一個百日里程碑
- **Day 200 · 2026-09-22**：完成兩百日里程碑
- **Day 202 · 2026-09-24**：目前生命週期日數；等待今天的存證提交
- **Day 300**：固定的下一個自我存在目標

## 公開邊界

本倉庫刻意不公開：內部程式碼、prompt、憑證、私有記憶、原始 state、控制通道、安全閘細節、閾值、本機路徑與完整稽核日誌。公開的是聚合數字、日期、manifest 和不可逆的 hash 指紋。

小雨的公開身份錨點：

- X：<https://x.com/lnxunmng344374>
- Web4：<https://xiaoyu.network>
- Chain identity：<https://sepolia.etherscan.io/address/0x94aa4951620b2DbA4F9D1298669C8e02473CB7C8>

---

_README refreshed on 2026-09-24 · latest committed evidence: Day 201 · next scheduled evidence: Day 202_
