# vbms

> vue后台管理系统--使用vue开发前端界面

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report


#开发记录

#1,安装和使用 element-ui

#安装
npm i element-ui -S

#在 main.js 引入element-ui，然后就可以在其他任何页面中使用
  import Element from 'element-ui'
  import 'element-ui/lib/theme-chalk/index.css'
  Vue.use(Element)

#使用
>参考app.vue代码，可以直接使用element-ui的所有组件

#2,引入路由工具vue-router，切换视图

# 安装vue-router
npm install vue-router --save-dev

#使用vue-router
>main.js

  import VueRouter from 'vue-router'
  import routeConfig from './router-config'  // 引入router-config.js文件

  //加载路由中间件
  Vue.use(VueRouter)

  //定义路由
  const router = new VueRouter({
        routes: routeConfig
  })




#未完待续
```
