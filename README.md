# memedb
通用迷因数据库计划

## 缘起
看过的迷因经常几天后就找不到，想建一个数据库方便随时调用

## 主要模块
###  1. 自动化爬虫
自动定时爬取多个来源的迷因。
#### 技术栈
- TG Crawler
- PTT Crawler
- Reddit Crawler
- Instagram Crawler
- Mainland Media Crawler (strongly not suggest due to potential risks of lyushihan)

###  2. 内容识别
识别迷因的屬性（Type、来源、语言、文字、内容标籤、模版等）。
#### 技术栈
- Fucking Deep Learning
- Fucking Deeper Learning

###  3. 分类存储
保存迷因档案本身与迷因识别结果
#### 技术栈
- Object Storage
- Cloudlare Workers KV
- Strapi

###  4. API
对数据库进行操作并返回结果
#### 技术栈
- GraphQL

###  5. 前端
#### 技术栈
- Vue 3.0 + Vuex + Vuetify 3.0

## 开发计划
- [x] 完成企划书
