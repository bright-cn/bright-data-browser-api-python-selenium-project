# 使用 Selenium 的 Bright Data 酒店搜索抓取器

本项目演示如何将 Bright Data 的 Browser API 与 Selenium 结合使用，在 Booking.com 上搜索酒店。它提供了一个使用 Selenium 进行自动化浏览器控制的网页抓取实用示例。

<a href="https://codesandbox.io/p/devbox/github/brightdata/bright-data-browser-api-python-selenium-project?file=%2Fbooking_hotel_scraping.py" target="_blank" rel="noopener">在 CodeSandbox 中打开</a>，使用 GitHub 账号登录，然后 fork 该仓库以开始修改。

### 开始使用

1. 在 `booking_hotel_scraping.py` 中将 `YOUR_BRIGHT_DATA_BROWSER_API_ENDPOINT` 替换为你实际的 Bright Data 浏览器 API HTTP 端点
2. 运行 `python booking_hotel_scraping.py` 开始抓取

## 💻 使用方法

1. 在 `booking_hotel_scraping.py` 中修改搜索参数：
   ```python
   SEARCH_LOCATION = "New York"  # 修改为你想要的地点
   CHECK_IN_DAYS_FROM_NOW = 1    # 调整入住日期（距离今天的天数）
   CHECK_OUT_DAYS_FROM_NOW = 2   # 调整退房日期（距离今天的天数）
   ```

2. 运行脚本：
   ```bash
   python booking_hotel_scraping.py
   ```

## 📊 示例输出

```
📊 搜索结果:
==================

#1
酒店名称: Hotel Name 1
价格: $100
评分: 8.5
--------------------------------------------------

#2
酒店名称: Hotel Name 2
价格: $150
评分: 9.0
--------------------------------------------------

#3
酒店名称: Hotel Name 3
价格: $200
评分: 8.8
--------------------------------------------------

✅ 共找到 3 家酒店
```
