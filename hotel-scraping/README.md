# 使用 Selenium 的 Bright Data 酒店搜索抓取工具

本项目演示如何将 Bright Data Browser API 与 Selenium 搭配使用，在 Booking.com 上搜索酒店。它提供了一个使用 Selenium 自动控制浏览器进行网页爬虫的实用示例。

<a href="https://codesandbox.io/p/devbox/github/bright-cn/bright-data-browser-api-python-selenium-project?file=%2Fbooking_hotel_scraping.py" target="_blank" rel="noopener">在 CodeSandbox 中打开</a>，使用 GitHub 账号登录，然后复刻此存储库即可开始修改。

### 快速入门

1. 在 `booking_hotel_scraping.py` 中，将 `YOUR_BRIGHT_DATA_BROWSER_API_ENDPOINT` 替换为你实际的 Bright Data Browser API HTTP 端点
2. 运行 `python booking_hotel_scraping.py` 开始抓取

## 💻 使用方法

1. 修改 `booking_hotel_scraping.py` 中的搜索参数：
   ```python
   SEARCH_LOCATION = "New York"  # Change to your desired location
   CHECK_IN_DAYS_FROM_NOW = 1    # Adjust check-in date
   CHECK_OUT_DAYS_FROM_NOW = 2   # Adjust check-out date
   ```

2. 运行脚本：
   ```bash
   python booking_hotel_scraping.py
   ```

## 📊 输出示例

```
📊 Search Results:
==================

#1
Hotel Name: Hotel Name 1
Price: $100
Rating: 8.5
--------------------------------------------------

#2
Hotel Name: Hotel Name 2
Price: $150
Rating: 9.0
--------------------------------------------------

#3
Hotel Name: Hotel Name 3
Price: $200
Rating: 8.8
--------------------------------------------------

✅ Found 3 hotels
```