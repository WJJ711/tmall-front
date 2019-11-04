项目初始化步骤

1.安装nodejs环境
    下载地址 : https://nodejs.org/download/release

2.全局安装webpack v2.x
    命令: sudo npm install -g webpack

3.全局安装webpack-dev-server
    命令: sudo npm install -g webpack-dev-server

4.clone源码

5.在项目根目录执行npm初始化
    命令: npm install --registry=https://registry.npm.taobao.org

```
  output: {
        path        : __dirname + '/dist/',
        publicPath  : 'dev' === WEBPACK_ENV ? '//s.wjjlucky.top/tmall-front/dist/' : '//s.wjjlucky.top/tmall-front/dist/',
        filename    : 'js/[name].js'
    },
```
指向自己指定的静态文件域名。