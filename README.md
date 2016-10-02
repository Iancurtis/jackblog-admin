# jackblog 后台管理, 使用angular

## 简介
Jackblog 是使用 Node.js + MongoDB + 其它客户端框架, 开发的个人博客系统,前后端分离,仿简书模板.此为后台管理, 使用angular
服务端有:  
[express版](https://github.com/jackhutu/jackblog-api-express)  
[koa版](https://github.com/jackhutu/jackblog-api-koa)         
客户端有:  
[angular1.x版](https://github.com/jackhutu/jackblog-angular1)   
[react 版](https://github.com/jackhutu/jackblog-react)  
[vue 版](https://github.com/jackhutu/jackblog-vue)    
移动端有:   
[react native 版](https://github.com/jackhutu/jackblog-react-native-redux)

## 环境准备
安装sass,compass,以及compass spriting(精灵图)支持.(png图片生成库)  
[sass安装方法](http://sass-lang.com/install)   
[compass安装方法](http://compass-style.org/install)      
[png图片生成库安装方法](http://compass-style.org/help/tutorials/spriting)       
```
$ gem install sass
$ gem install compass
$ gem install oily_png
```

## 开发
 
```
$ npm install
$ bower install
$ gulp serve
```

## 打包  
 
```
$ gulp build 或 gulp serve:dist
```

## 线上布署
```
$ pm2 start process.json
```

## 测试
karma测试:

```
$ gulp test
```

## License
MIT