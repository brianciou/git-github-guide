# Git & GitHub 新手入門指南

> 給 Vibe Coder 的對話式 Git 與 GitHub 教學

一份用「對 Claude Code 說的話」串起來的入門指南，讓你不用硬背指令，也能放心地用 Git 做版本控制、用 GitHub 做雲端備份與協作。

🔗 **線上閱讀**：（部署後補上連結）

---

## 這份指南是什麼

- **Part 1：Git 入門** — 從 Repo、Commit、Branch、Merge 到 `.gitignore`，學會在本機放心嘗試任何改動
- **Part 2：GitHub 基礎概念** — 從 push/pull/clone、Fork 到 Pull Request，把專案搬上雲端、也能跟世界協作
- **附錄：推薦學習資源** — 進一步深入的延伸閱讀

每一節都附上「對 Claude Code 說」的對話範例，看完就能直接拿來用。

---

## 適合誰

- 用 Claude Code、Cursor 等 AI 工具寫 code 的 **Vibe Coder**
- 從來沒用過 Git、看到指令會慌的人
- 知道一點點 Git、但對 GitHub 的 fork / PR 沒有信心的人

完全不需要任何 Git 基礎，看著看著就會了。

---

## 在本機預覽

這是一份純靜態網站（HTML + CSS，沒有任何 build step），下載下來開 `index.html` 就能看：

```bash
git clone https://github.com/brianciou/git-github-guide.git
cd git-github-guide
open index.html
```

或起一個本地 server（推薦，這樣相對路徑、字型載入都會正常）：

```bash
python3 -m http.server 8000
# 瀏覽器打開 http://localhost:8000
```

---

## 怎麼貢獻

這份指南本身就在教 fork / clone / Pull Request，**最棒的練習就是直接來貢獻一筆**。歡迎：

- 🐛 抓錯字、修錯誤連結
- ✏️ 改善敘述、補充更清楚的比喻
- 📚 補充新的學習資源
- 💡 提案新的章節主題

貢獻流程跟細節都寫在 [CONTRIBUTING.md](./CONTRIBUTING.md)，第一次貢獻開源的人也能照著做。

---

## License

[MIT](./LICENSE) — 可自由使用、修改、衍生創作，唯一要求是保留原作者標示。
