# Site settings
title: 独立写生
header-img: "img/green.jpg"
tagline: "cn"  
description: "陈素封|读而立·写而生"  
baseurl: ""
url: "http://cnfeat"  

# About/contact
owner: 
  name: " CnFeat"
  email: CnFeat@gmail.com
  bio: "写就是写的报酬"

# Data
gavatar: http://dreamofbook.qiniudn.com/Az..png
favicon: img/favicon.png

douban_username:  
twitter_username: 
github_username: 
facebook_username: 
weibo_username: 
zhihu_username: 

# Build settings  
# use Github Flavored Markdown !important  
# document: http://jekyllrb.com/docs/configuration/#kramdown  
markdown: kramdown
highlighter: rouge
permalink: pretty
paginate: 8
exclude: ["less","node_modules","Gruntfile.js","package.json","README.md"]

# http://en.wikipedia.org/wiki/List_of_tz_database_time_zones
timezone: Asia/Shanghai

# Defaults for posts
defaults:
  -
    scope: 
      path: ""
      type: "posts"
    values:
      layout: "post"
      author: "CnFeat"
      header-img: "img/green.jpg" # We don't want posts without a header image, that whould mean white on white

# Comments 
comments :
  provider : duoshuo
  duoshuo :
    short_name : 
  disqus :
      short_name : 

# Analytics and webmaster tools stuff goes here
google_analytics: 
google_verify:
# https://ssl.bing.com/webmaster/configure/verify/ownership Option 2 content= goes here
bing_verify:

# Links to include in footer navigation
