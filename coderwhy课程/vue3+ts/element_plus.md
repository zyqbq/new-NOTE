react+AntDesign

Vue3+VantUI

UI组件库 后台管理系统常用

AntDesign=>react(蚂蚁金服)

AntDesignVue=>vue

elementUI=>vue2 (饿了么团队)

elementPlus=>vue3

### 安装

npm install element-plus

安装文档

https://element-plus.gitee.io/zh-CN/guide/installation.html

导入文档

https://element-plus.gitee.io/zh-CN/guide/quickstart.html

### 全局引入

打包会很大

![image-20240321102940215](img/image-20240321102940215.png)

### 全局引入时 让ui使用时有属性提示

全局引入利用volar 配置tsconfig.json

![image-20240321103736727](img/image-20240321103736727.png)

![image-20240321103722741](img/image-20240321103722741.png)

### 按需引入

```
npm install -D unplugin-vue-components unplugin-auto-import
```

[快速开始 | Element Plus (gitee.io)](https://element-plus.gitee.io/zh-CN/guide/quickstart.html)

配置

![image-20240321105023767](img/image-20240321105023767.png)

配置tsconfig 才会产生提示

![image-20240321105422816](img/image-20240321105422816.png)

不支持自动导入的ui

![image-20240321110728214](img/image-20240321110728214.png)



### 页面全屏

![image-20240321200828441](img/image-20240321200828441.png)

### checkbox

![image-20240328015817305](img/image-20240328015817305.png)

![image-20240328020059084](img/image-20240328020059084.png)

超链接

![image-20240328020236895](img/image-20240328020236895.png)

按钮

![image-20240328020953413](img/image-20240328020953413.png)

![image-20240328020927822](img/image-20240328020927822.png)

tab

![image-20240328021224137](img/image-20240328021224137.png)

### 在tab中使用图标

```
npm install @element-plus/icons-vue
```

![image-20240328030307338](img/image-20240328030307338.png)

全局注册

![image-20240328031230731](img/image-20240328031230731.png)

![image-20240328032002570](img/image-20240328032002570.png)

![image-20240328032109931](img/image-20240328032109931.png)

![image-20240328032529852](img/image-20240328032529852.png)

 ![image-20240328045234301](img/image-20240328045234301.png)



![image-20240328045152240](img/image-20240328045152240.png) 

### 登录时js查询是哪种登录方式

![image-20240328045837379](img/image-20240328045837379.png)

![image-20240328045815424](img/image-20240328045815424.png)

![image-20240328045737088](img/image-20240328045737088.png)



输入框

![image-20240328051838049](img/image-20240328051838049.png)

![image-20240328051819492](img/image-20240328051819492.png)

![image-20240328051757021](img/image-20240328051757021.png)

### 表单校验

就是表单输入不符合时的提示

![image-20240328053006618](img/image-20240328053006618.png)

一个输入框可以定义多个规则

![image-20240328053241882](img/image-20240328053241882.png)

![image-20240328053331688](img/image-20240328053331688.png)

![image-20240328053508867](img/image-20240328053508867.png)

### 在父组件中执行子组件的方法

![image-20240328063743730](img/image-20240328063743730.png)

ref的dom组件类型

![image-20240328063603636](img/image-20240328063603636.png)

![image-20240328064202995](img/image-20240328064202995.png)

### 登录时账号和密码不符合要求提示功能

![image-20240328072606460](img/image-20240328072606460.png)

![image-20240328072636047](img/image-20240328072636047.png)

![image-20240328072753982](img/image-20240328072753982.png)

### 提示弹出功能

![image-20240328072951318](img/image-20240328072951318.png)

![image-20240328073031731](img/image-20240328073031731.png)

这里只有组件没有样式

样式引入的方式

1. 全部引入

![image-20240328073152304](img/image-20240328073152304.png)

2. 部分引入

![image-20240328073235752](img/image-20240328073235752.png)

3. 插件引入

npm i vite-plugin-style-import -D

npm i consola -D

在vite.config.ts中配置

![image-20240328073828023](img/image-20240328073828023.png)

![image-20240328073812942](img/image-20240328073812942.png)

![image-20240328073818528](img/image-20240328073818528.png)

### 登录

![image-20240328075008057](img/image-20240328075008057.png)

![image-20240328075200050](img/image-20240328075200050.png)

![image-20240328075805865](img/image-20240328075805865.png)

![image-20240328075919345](img/image-20240328075919345.png)

### 245类型定义

### 246postman使用

![image-20240328084044492](img/image-20240328084044492.png)

配置环境变量

![image-20240328085723968](img/image-20240328085723968.png)

### 保存token

![image-20240328091014578](img/image-20240328091014578.png)