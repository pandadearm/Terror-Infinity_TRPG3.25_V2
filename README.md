# 無限流 TRPG 3.25 網頁 V2.2

將本資料夾內全部檔案與子資料夾上傳至 GitHub Pages 發佈目錄，保留目錄結構與 `.nojekyll`。首頁為 `index.html`，生命計算器為 `life-calculator.html`。

規則資料經 gzip 壓縮後分成 `library-data/part-*.js`，首頁按順序載入；請勿省略任一分檔。初始化不依賴資料 fetch 或開發伺服器，`library/` 另保留分批原始 JSON 供核對。所有檔案嚴格小於 20,000,000 bytes（20 MB）。
