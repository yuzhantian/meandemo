# meandemo
基于MEAN搭建的全栈式开发demo，主要参考慕课网翻译的文章[基于MEAN的全栈开发实例教程](http://www.imooc.com/search/article?words=%E5%9F%BA%E4%BA%8Emean)

## 项目搭建
### 本地环境  
需要安装Node.js，MongoDB以及基于Node的Nodemon模块，该模块用于自动重启web服务器

### clone项目  
`git clone https://github.com/yuzhantian/meandemo.git`

### 加载依赖包  
cmd命令行下输入  
`cd meandemo`  
`npm install`

### 启动项目
`nodemon`

### 查看结果
浏览器打开`http://localhost:30000`  
可在 `/bin/www` 中的第15行`var port = normalizePort(process.env.PORT || '30000');`修改端口
