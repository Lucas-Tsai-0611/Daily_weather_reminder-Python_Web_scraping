# Daily_weather_reminder-Python_Web_scraping

## Introduction
This is a simple web scaping code combine Line Notify and crontab to tell the user how the weather today at 7:00am every day.

## Step
1. Go to https://pweb.cwb.gov.tw/CWBMEMBER3/ apply for membership.
2. Login to https://opendata.cwb.gov.tw/user/authkey find API authorization code and get the authorization code to instead authorization code in notify.py.
3. Go to Line Notify https://notify-bot.line.me/zh_TW/ to issue token and instead token in notify.py
4. Open terminal and key crontab -e to set rutine to run notify every day.
5. After enter crontab -e key    0 7 * * * Path Of Your Python Environment  Path of notify.py

## Features
![IMG_2098](https://github.com/Lucas-Tsai-0611/Daily_weather_reminder-Python_Web_scraping/assets/81616595/6b53974c-97f8-46ad-93df-d81c94e762e9)


## Reference Site
1. https://zhuanlan.zhihu.com/p/109739540
