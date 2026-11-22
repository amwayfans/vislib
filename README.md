# 視覺素材庫（已停止維護）

**正式站在靈犀週拾：https://lingxi-weekly.pages.dev/vislib/**

2026-11-22 起，這個獨立站只保留一個導向頁（`index.html`），內容全部移到靈犀週拾的「素材庫」分頁：

- 風格庫 24 種（含起源、視覺重點、冷知識、中英文提示詞）
- 混搭實驗 10 組
- 動態詞彙 240 條（卡片式）

## 為什麼收掉

兩個入口會讓資料分岔——真正的問題不是「哪個好看」，而是「改了一份、另一份沒改」。
現在單一真相源在本機 `/data/Hermes/border/work/vislib`，
透過 `weekly-site/tools/sync_vislib.py` 同步進靈犀週拾，只有一個站要維護。

## 檔案說明

- `index.html`：導向頁（唯一還在服務的檔案）
- `index-board.html.bak`：舊的單檔看板（保留下來對照，不再部署）
- `img/`：舊看板用的圖（新站用 `site/public/vislib-img/` 的 WebP）
- `LICENSE-motion-prompt.txt`：動態詞彙來源 motion-prompt 的 MIT 授權（© 2026 Shohei Ohtaki）

## 授權

- 詞彙：[motion-prompt](https://github.com/showheyohtaki/motion-prompt)，MIT License © 2026 Shohei Ohtaki
- 風格樣張：以同一張基準圖經 fal 生成，供風格比較用（原檔在本機素材庫）
