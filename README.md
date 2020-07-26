# Store
vue + mongodb + nodejs全栈商城
## Src
### src---assets
- 存放静态文件，基础css样式
### src---components
- 存放公共组件
### srrc---util
- 存放金额格式化的封装代码
### src---views
- 存放商品列表、购物车、地址、提交订单、提交订单成功五个主要页面

## server
- 该文件夹存放的是后台接口和数据库
### models
- 数据库模型
### router
- 后台接口文件

## mock
- 该文件是还未写接口前定义的商品数据

## build和config
配置文件

## 运行项目
- 1.在store项目下运行命令行窗口，通过npm install安装项目依赖
- 2.在store项目文件下运行 node server/bin/www
- 3.在store项目文件下运行 npm run dev
- 4.通过本地localhost:8080访问
