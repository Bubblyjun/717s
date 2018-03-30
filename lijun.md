717项目总结

* 项目简单说明
仿717APP电商项目 实现首页、分类、购物车和登录注册等详情页界面
1、React实现，用组件层实现项目结构搭建；
2、webpack脚手架的配置；
3、redux组件之间数据共享
4、react-router跳转路由


* 项目实现
有路由跳转、轮播图、点击分类、数据下拉刷新、登录注册、配置地址、购物车、跳转详情页等
1、首页利用swipper实现轮播图并进行了数据渲染
2、分类页实现tab切换
3、购物车页先判断用户是否登录    实现添加选购商品并计算价格的功能
4、我的页面实现登录注册 可以退出登录

* 项目重难点-关键处
在项目构建过程中遇到的难点在于添加购物车并且实现购物车功能还有添加编辑地址


配置webpack
Entry：入口，定义打包文件
Output：出口，定义打包输出文件
Module：主要定义loaders
Resolve：定义被打包的文件
Plugins：定义额外的插件
总共用到的loaders
样式：sass-loader、style-loader、css-loader，将 sass 转成 css
图片：url-loader.
js： babel-loader，babel-preset-react
使用 webpack-dev-server 启动服务器
webpack.config.js: webpack常规配置，配置入口文件，输出文件，loaders等
package.json: 自定义启动命令
components 都是redux相关的配置
componentDidMount方法获取数据


