# python-stock-chart-scraper #

## 專案介紹 ##

本專案為Python網頁爬蟲，爬取[Yahoo奇摩股市](https://tw.stock.yahoo.com/)網站的美股大盤行情圖表資料，包含「美股指數」、「成交量」及「時間」，並且整合Pandas套件，將Python網頁爬蟲取得的圖表資料存入Pandas DataFrame，呈現爬取的結果，可以搭配[[Python爬蟲教學]你該學會的Python網頁爬蟲取得網頁圖表數據方法](https://www.learncodewithmike.com/2020/12/scraping-web-charts-with-python.html)部落格文章來進行學習。

## 前置作業 ##

將專案複製(Clone)下來後，假設沒有pipenv套件管理工具，可以透過以下指令來進行安裝：

`$ pip install pipenv`

有了pipenv套件管理工具後，就可以執行以下指令，來安裝專案所需的套件：

`$ pipenv install --ignore-pipfile`

接著，登入虛擬環境：

`$ pipenv shell`

登入後，就能夠執行chart_scraper.py範例程式。