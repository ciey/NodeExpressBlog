[![node version](https://img.shields.io/badge/node.js-%3E=_8.0.0-green.svg)](http://nodejs.org/download/)
[![express](https://img.shields.io/badge/express-%5E4.17.1-green.svg)](https://expressjs.com)
[![mysql](https://img.shields.io/badge/mysql-%5E2.17.1-green.svg)](https://github.com/mysqljs/mysql)

# NodeExpressBlog

目标：使用Node.js + Express + MySQL开发完整个人博客以替代现有的Hexo静态博客。

定位：入门级，大都采用广泛使用的组件，比如Node框架express、模板引擎ejs、ORM组件sequelize等，以及采用ES6语法async/await避免嵌套回调。即使是小白也能一学就会。

## Features
- [ ] 后台管理
- [ ] 主题切换
- [ ] API接口
- [ ] 首屏加载优化
- [ ] SEO优化

## Required
* node >8.x
* mysql 5.6 ~ 5.7

## Install
```
$ git clone git@github.com:ciey/NodeExpressBlog.git  

$ cd NodeExpressBlog

//将config.default.js复制一份为config.js，因为config.js为git忽略文件
$ cp config.default.js  config.js

$ npm install

//需先在mysql手动创建expressblog数据库，并执行以下命令同步表
$ node dbsync

$ npm start

访问: http://localhost:9000

```



## License
MIT licensed, as found in the LICENSE file.
