# 貢獻指南

歡迎來貢獻這份指南！這份文件本身就是「fork → 改 → PR」流程的練習範例，第一次貢獻開源也沒關係，照著做就會了。

---

## 適合貢獻的內容

✅ **歡迎的改動**
- 抓錯字、修錯誤連結
- 改善敘述、讓比喻更清楚
- 補充學習資源（書籍、教學、影片）
- 修正過時的 GitHub 介面說明
- 提案新章節（先開 Issue 討論方向）

⚠️ **建議先開 Issue 討論**
- 大規模重寫某一節
- 改動設計系統（顏色、字型、版面）
- 新增章節

---

## 第一次貢獻？跟著做

### 1. Fork 這個 repo

點右上角 **Fork** 按鈕，把專案複製一份到你自己的 GitHub 帳號下。

### 2. Clone 到本機

```bash
git clone https://github.com/<你的帳號>/git-github-guide.git
cd git-github-guide
```

### 3. 開一條新分支

```bash
git checkout -b fix/typo-in-part1
# 命名建議：fix/xxx（修錯）、feat/xxx（新增）、docs/xxx（文件）
```

### 4. 改你想改的地方

- 內容調整：編輯 `index.html`
- 樣式調整：編輯 `styles.css`

在瀏覽器打開 `index.html` 或起一個 local server 預覽：

```bash
python3 -m http.server 8000
```

### 5. Commit

請用 [Conventional Commits](https://www.conventionalcommits.org/) 格式：

```bash
git add .
git commit -m "fix: 修正 Part 1 第三節錯字"
```

常用前綴：`feat`（新功能）、`fix`（修錯）、`docs`（文件）、`style`（樣式）、`refactor`（重構）。

### 6. Push 到你的 fork

```bash
git push origin fix/typo-in-part1
```

### 7. 開 Pull Request

回到 GitHub 你的 fork 頁面，會出現「Compare & pull request」按鈕，點下去。

PR 的標題與說明請包含：
- **改了什麼**：一句話描述
- **為什麼**：背景或動機（可選但加分）
- **截圖**：如果是視覺改動（強烈建議）

---

## 寫作風格

這份指南有幾個一致性原則，麻煩盡量沿用：

- **對象是 Vibe Coder**：預設讀者用 Claude Code / Cursor 等 AI 工具寫 code，不熟悉指令
- **語氣親切但不浮誇**：像跟朋友解釋，不要用「超讚！」「神器！」這類用語
- **多用生活比喻**：抽象概念盡量類比成日常經驗（拼圖、相機、Google 文件）
- **附「對 Claude Code 說」對話範例**：每個操作後盡量補一句用戶可以直接複製的提問
- **CJK 與英數之間留空格**：例如「使用 Git 來做版本控制」、「commit 一次」

---

## Code Style

- HTML 縮排 2 spaces
- CSS 縮排 2 spaces，class 命名走 kebab-case
- 中文標點用全形（，、。「」）
- 中英之間留半形空格

---

## 有問題想討論？

直接開一個 [Issue](../../issues/new/choose) 提問或回報問題就好，沒有問太蠢的問題這種事。

謝謝你來貢獻 🙌
