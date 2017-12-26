# ZSCNSD-OfficialWebsite-Low(Deprecated)

The old ZSCNSD official website.

The project is deprecated. Please see [the new one](https://github.com/ZSCNetSupportDept/ZSCNSD-OfficialWebsite).

本项目已经废弃，请看新的[项目](https://github.com/ZSCNetSupportDept/ZSCNSD-OfficialWebsite)

中山学院网络维护科官网，因为后端和[另一个项目](https://github.com/ZSCNetSupportDept/ZSCNSD-AnnualMeeting)结合，构建前请将该项目加入public文件夹，存放方式参照routes的index.js的/annual路由的文件路径

## 前端

### 简介
* bower_components文件夹是bower引入的组件的文件夹（安装依赖后出现）
* images文件夹是存放图片的文件夹
* widget文件夹是存放各个js和css组件的文件夹
* 主目录是各个html和fis-conf.js之类的文件  

### 构建方法
1. 用命令行切换到frontEnd文件夹
2. 安装相关构建所需依赖,运行`npm i`
3. 运行`fis3 release -d ../sys` 或 `npm start` 构建

## 后端

### 简介
* 基于Express实现

### 运行方法
1. 用命令行切换到sys文件夹
2. 运行`npm start`