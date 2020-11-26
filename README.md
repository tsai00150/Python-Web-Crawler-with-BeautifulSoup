# Python-Web-Crawler-with-BeautifulSoup
This program can search for the titles of articles on the Applefans website. You can also filter the titles that interest you.
該程式可以在Applefans網站上搜索文章標題。您還可以過濾您感興趣的標題。
Website: https://applefans.today/category/news/

## Prerequisites
* Jupyter Notebook
Install: https://jupyter.org/install
* BeautifulSoup
Install: https://pypi.org/project/beautifulsoup4/

## Filter Function
The "filter' function can help filter the titles that you want to see. For this case, we want to filter the articles that only includes "iPhone" but not "iPhone 12" for the output. You can also switch up the keywords. 
If you want to filter nothing (return every title from the page), simply ```return title```:
```py
def filter (title):
    #'title' is tag element type, titletext is string, need to convert before filtering
    titlestr = str(title)
    return title
   ```
“filter”功能可以幫助過濾您要查看的標題。在這種情況下，我們要過濾僅包含 “iPhone” 的標題，但不包含 “iPhone 12”。您也可以任意切換關鍵字。
如果您不想過濾任何內容（頁面中的每個標題都會出現），只需補上```return title```即可。


## Output
The output includes:
* The pages of the title it is on
* The title name
* The link to the title
```
Page:0
《iOS 14 捷徑》iPhone 機型浮水印 2020
https://applefans.today/shortcuts-iphone-models-watermark-ios-14
Page:0
iPhone 又能玩「要塞英雄 Fortnite」遊戲？
https://applefans.today/fortnite-back-to-iphones-via-nvidia-cloud-gaming-service
Page:1
用 iPhone 自製鈴聲 零失敗技巧教學
https://applefans.today/make-iphone-ringtone-by-iphone
```
輸出包括：
* 標題所在的頁面
* 標題名稱
* 標題連結
