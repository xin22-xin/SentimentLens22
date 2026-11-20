---
title: 多語言情感分析
emoji: 💬
colorFrom: blue
colorTo: purple
sdk: static
pinned: false
---

# 多語言情感分析

輸入一段中文或英文，判斷情感為正面、中性或負面。

- 模型：`Xenova/distilbert-base-multilingual-cased-sentiments-student`（與 GroundingPI 不同）
- 以純 HTML + [transformers.js](https://huggingface.co/docs/transformers.js) 製作，模型在瀏覽器中執行，不需要 Python 或後端。

## 本機執行

不需安裝 Python。在 VS Code 安裝 Live Server 擴充功能後，對 `index.html` 按右鍵 →
Open with Live Server；或直接雙擊 `index.html` 以瀏覽器開啟（需要網路以下載模型）。
