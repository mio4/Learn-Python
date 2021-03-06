

# prepare work

- [x] 安装Anaconda：C:\ProgramData\Anaconda3
- [x] 安装Python：Python 3.5.4
- [x] 安装pip 3.5
- [x] 安装MongoDB 3.4：C:\MongoDB\Server\3.4\
- [x] 安装 robo3t（MongoDB可视化工具）： C:\Program Files\Robo 3T 1.2.1
- [x] 安装Reids ： C:\Program Files\Redis\
- [x] 安装Redis Desktop Manager （Redis可视化工具）： C:\Program Files (x86)\RedisDesktopManager


### MongoDB

>MongoDB是非关系型数据库

 - 配置

```cmd 
mongod --bind_ip 0.0.0.0 --logpath C:\MongoDB\Server\3.4\data\logs\mongo.log --logappend --dbpath C:\MongoDB\Server\3.4\data\db --port 27017 --serviceName "MongoDB" --serviceDisplayName "MongoDB" --install
```

 ### Python库

  - [x] 更换pip源
  - [x] urilib re
  - [x] request
  - [x] selenium + ChromeDriver(已放在Anaconda目录下)
  - [x] phantomjs（相对于ChromeDiver没有视图界面）
  - [x] lxml
  - [x] beautifulsoup （网页解析库，依赖于lxml）
  - [x] pyquery（类似于jQuery的解析库）
  - [x] pymysql （连接MySQL）
  - [x] pymongo
  - [x] redis
  - [x] flask
  - [x] django
  - [x] jupyter （支持Markdown，可以在线运行Python代码）


 # Spider

 ## 爬虫步骤

 - 通过Http库发送Request请求
 - 获取Response相应
 - 解析内容 
    - json
     - 正则表达式
     - beautifulsoup
     - pyquery
     - xpath

### 解决JavaScript渲染

 - 分析Ajax请求（返回结果为JSON）
 - Selenium/WebDriver
 - Splash
 - PyV8、Ghost.py

### 数据存储

 - 纯文本、JSON、XML、
 - MySQL
 - 非关系型数据库
 - 二进制文件（图片视频）
