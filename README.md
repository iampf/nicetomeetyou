# nice to meet you
1. 抓取 https://nba.udn.com/nba/index?gr=www 中的焦點新聞。
2. 使用 [Django](https://www.djangoproject.com/) 設計恰當的 Model，并將所抓取新聞存儲至 DB。
3. 使用 [Django REST Framework](http://www.django-rest-framework.org/) 配合 AJAX 實現以下頁面：
  * 焦點新聞列表
  * 新聞詳情頁面
4. 以 Pull-Request 的方式將代碼提交。

## 進階要求
1. 實現爬蟲自動定時抓取。 (目前使用crontab實作)
2. 每當抓取到新的新聞時立即通知頁面。 
3. 将本 demo 部署至服务器并可正确运行。 （因無server所以還沒有接上wsgi）

## 使用
1. 主頁面於 http://localhost/index下
2. 須先執行updateDB.py來更新資料庫
