# scrape_selenium

這是一個使用 Python 爬取電影資料的專案，用於練習 selenium 爬取動態網頁的方法。

## 功能介紹

- 使用 `Selenium`  自動化瀏覽器操作
- 從動態渲染的網頁獲取電影列表及詳細資訊
- 解析 `HTML` 元素獲取所需數據
- 將數據寫入 `Excel` 檔案
- 防止重複數據
- 使用隨機延遲來避免被封鎖

## 使用套件

- `selenium` : 模擬使用者在瀏覽器的操作行為
- `fake_useragent` : 生成隨機 User-Agent
- `webdriver_manager` : 自動根據你的Chrome下載正確的版本
- `openpyxl` : 操作 Excel 檔案

## 如何使用

1. 安裝必要的套件:
   
   ```bash
   pip install fake_useragent selenium webdriver_manager openpyxl
   ```
2. 確保你的系統上安裝了Chrome瀏覽器。

3. 運行腳本:
   
   ```bash
   python scrape_selenium.py
   ```
4. 自動爬取網站的所有頁面，並將結果保存在 `scrape_selenium.xlsx` 文件中。

## 注意事項

- 本爬蟲專案僅供學習和研究使用
- 請遵守網站的 `robots.txt` 規則和使用條款
- 爬取速度已經設置了隨機延遲,但仍需注意不要對目標網站造成過大負擔
