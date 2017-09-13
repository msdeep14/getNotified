# getNotified

a python script that sends SMS to mobile when price of product on Amazon lowers down to expected price

## Installation
  1. clone the repo : git clone https://github.com/msdeep14/getNotified.git
  2. edit mobile number, app_key, app_secret, amazon URL in getNotified.py
  3. execute in terminal : python getNotified.py

## Requirements
  1. python 2.7
  2. lxml
  3. requests
  4. sched
  5. sinchsms : get app_key and app_secret by registering app at [https://www.sinch.com/](https://www.sinch.com/)
