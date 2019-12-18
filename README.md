wangwang
=====

项目介绍（如果对你有用，请给个star！）
------
汪汪旺影院该网站是一个在线购买电影票系统，登录即可买票。致力于打造适用的分布式系统。采用前后端分离模式，前台采用vue.js为核心框架。

功能介绍
---
* 首页功能，导航模块（自定义导航设置），广告模块（自定的轮播设置），

* 列表功能，分类模块（自定义分类设置），搜索模块（自定义搜索设置）

* 电影详情页功能，电影介绍、目录的展示和购买、播放功能等等

* 个人中心，具有个人信息设置、密码修改、订单管理等功能

目录结构
---
roncoo-education-web/
├── api/ api接口列表目录
│   ├── method.js
│   ├── main.js
├── assets/ 公用的静态资源目录
│   ├── CSS/
│   ├── JS
│   ├── fonts
│   ├── image
├── component/ 
│   ├── 所有的自定义组件
├── config/ 配置文件目录
│   ├── conf.js  系统编译配置文件
│   ├── index.js  系统全局配置文件
│   ├── dev.env.js  开发模式的全局配置
│   ├── pro.env.js  生产模式的全局配置
│   ├── index.js  测试模式的全局配置
├── layouts/
│   ├── 布局目录
├── middleware/
│   ├── 中间件目录
├── pages/
│   ├── 页面目录
├── plugins/
│   ├── 所有的第三方或自定义插件的目录
├── static/
│   ├── 静态文件目录
├── store/
│   ├── actions.js
│   ├── getters.js
│   ├── index.js
│   ├── mutations.js
├── utils/
│   ├── 自定义工具类目录
└── next.config.js   nextjs 配置文件 


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
