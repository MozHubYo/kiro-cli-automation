# Kiro CLI Automation

Kiro CLI Headless Mode 課程教材 — 從 Demo 到真實業務自動化。

## 線上教材

👉 **<https://mozhubyo.github.io/workshop/kiro-cli/>**

## 快速開始

```powershell
git clone https://github.com/MozHubYo/kiro-cli-automation.git
cd kiro-cli-automation
```

確認已安裝 Kiro CLI 並設定好 API Key 後，即可開始操作。

## 檔案說明

### 唐詩 Demo（1 ~ 5）

| 檔案 | 用途 |
|---|---|
| `1_poetry-demo.ps1` | 唐詩產生器，呼叫 Kiro CLI 寫三首唐詩 |
| `2_schedule-with-window.ps1` | 註冊排程（執行時會彈出視窗） |
| `3_unschedule-with-window.ps1` | 移除「有視窗版」排程 |
| `4_schedule-hidden.ps1` | 註冊排程（完全靜默執行） |
| `5_unschedule-hidden.ps1` | 移除「隱藏版」排程 |

### LLM 對話 Demo（6a ~ 6c）

| 檔案 | 用途 |
|---|---|
| `6a_fixed.py` | 固定 Prompt，單次呼叫 |
| `LLM Demo/6a_fixed.py` | 同上（放在子資料夾，示範上下文差異） |
| `LLM Demo/6b_stateless.py` | 互動對話，但每次都是無狀態 |
| `LLM Demo/6c_context.py` | 互動對話，累積歷史訊息 |

## 授權

MIT License
