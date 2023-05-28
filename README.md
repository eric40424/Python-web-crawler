# Python爬蟲程式碼

此專案主要放置我寫過的Python爬蟲程式碼

## 104人力銀行爬蟲程式(104_job_search.py)
此程式是在104人力銀行輸入職缺關鍵字後，將返回的職缺資訊蒐集回來。
程式執行完後會整理出以下資料欄位：
* 爬蟲執行的時間
* 搜尋關鍵字
* 搜尋最大頁數
* 職缺日期
* 職缺名稱
* 職缺公司名稱
* 職缺公司網址簡介(104人力銀行頁面)
* 職缺公司所屬產業
* 職缺內容
* 職缺職業類別
* 職缺薪水
* 職缺地點
* 職缺要求年資
* 職缺要求教育程度
* 職缺要求系所
* 職缺要求技能
* 職缺其他條件
* 職缺詳細資訊(104人力銀行頁面)

## Google股票新聞爬蟲程式(google_real_time_news.py)

此程式主要是透過Google RSS的搜尋功能，來下載股票的新聞資訊。
由於有不同家媒體的新聞來源，所以裡面只針對比較偏向財金新聞的網站進行擷取，共有下列9個網站：
* 聯合新聞網
* 自由財經
* Yahoo奇摩股市
* 經濟日報
* 中時新聞網
* 工商時報
* 鉅亨網
* ETtoday
* EBC東森財經新聞

程式執行完後會整理出以下資料欄位：
* 執行時間
* 搜尋關鍵字
* 新聞標題
* 新聞網址
* 新聞日期
* 新聞摘要
* 新聞來源及新聞內容

## 公開資訊觀測站-重大訊息爬蟲程式(materialInfo.py)

此程式為至公開資訊觀測站下載歷史重大訊息資料(包含上市、上櫃及DR公司)，並且有做防呆處理。程式執行完後會整理出以下資料欄位：
* 股票名稱
* 股票代碼
* 公告日期
* 公告時間
* 主旨
* 公告序號
* 事實發生日
* 重訊內容

## 上市上櫃股價爬蟲程式(stockPrice.py)

此程式至證交所及櫃買中心下載當日各檔股價資訊，程式執行完後會整理出以下資料欄位：
* 日期
* 市場別
* 股票代號
* 股票名稱
* 開盤價
* 最高價
* 最低價
* 收盤價
* 成交股數
* 成交金額(元)

## Accupass搜尋活動結果爬蟲程式(accupass_search.py)

此程式為簡單範例，至Accupass活動通網站爬取關鍵字搜索後的活動資訊，並輸出csv檔案。

## 期交所台指期爬蟲程式(taifex_tx.py)

此程式為簡單範例，爬取期交所台指期指定日期的價格資訊。

## Google搜尋(google_search.py)

此程式為簡單的範例，用Google關鍵字搜尋並找出返回結果的網站標題。

## 樂透彩爬蟲(lottery.py)

此程式為簡單範例，爬取台彩網站威力彩及大樂透最近一期的開獎結果。

## 證券商盤後資料專區-外資上市/上櫃買超排行(concords.py)

此程式為簡單範例，爬取康和證券盤後資料專區-外資上市/上櫃買超排行資訊。但建議若有三大法人資料需求，可至證交所/櫃買中心取得資料，因為是第一手資料資訊會最正確，且資料取得方式更佳便民。


