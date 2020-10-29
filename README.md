# Canary

> 一个坚持简约美的在线博客网站，可以实现博客的在线编辑，预览，发布功能。
提供用户登录注册功能，登录后可以发布文章，对文章进行点赞、评论、收藏等功能。文章可以根据分类或者标签查询，更是提供了全文检索功能。采用所见即所得的Markdown编辑器，使写作成为一种享受。采用prism进行代码高亮，更接近主流编译器的高亮风格。项目是采用前后端分离设计思想，前台界面采用响应式布局，在多端浏览都会有良好的视觉体验。前后端分开部署，采用了docker+jenkins自动化部署。

## 技术栈

 - vue2   用于构建用户界面的渐进式框架
 - vue-router   Vue.js 官方的路由管理器
 - vuex   专为 Vue.js 应用程序开发的状态管理模式
 - webpack   模块打包器
 - es6/eslint   采用es6语法，并使用eslint检查语法
 - axios   尤雨溪推荐使用axios来完成ajax请求
 - sass   对CSS的扩展，让CSS语言更强大、优雅

## 项目构建运行

``` bash
# clone项目到本地
git clone https://github.com/jie12366/simple-beauty.git

# 进入项目根路径
cd simple-beauty

# 安装相关依赖
npm install (或yarn)
 
# 本地运行
npm run dev
```

## 关于后端
后端用springboot+mongod构建，restful风格api，使用swagger生成在线api文档，JWT生成token，redis作为缓存以及内存数据库，使用websocket通信。

项目地址：[simple-beauty-after](https://github.com/jie12366/simple-blog-after.git)
## 目标功能
- [x] 登录注册  -- 完成
- [x] 修改密码  -- 完成
- [x] 第三方登录(暂时只支持QQ、github、码云)  -- 完成
- [x] 个人中心  -- 完成
- [x] 消息提醒  -- 完成
- [x] 在线编辑文章  -- 完成
- [x] 文章详情展示  -- 完成
- [x] 管理博客  -- 完成
- [x] 自定义主题  -- 完成
- [x] 评论回复系统  -- 完成
- [x] 点赞、收藏  -- 完成
- [x] 分类、标签、归档展示  -- 完成
- [x] 照片墙、关于我  -- 完成
- [x] 全文检索/站内搜索  -- 完成
## 项目演示
项目演示地址为：[Canary](https://jie12366.xyz:8081)

## 需要注意的问题
支持高亮的语言为java、kotlin、c、cpp、python、bash、lua、vim、yaml、docker、git、json，其他语言不支持代码高亮，如果不是以上语言，请不要在代码块中注明语言。默认使用shell语法来高亮代码。
## 感谢开源
|名称|说明|GitHub/官网|
|---|---|---|
|HyperMD|所见即所得的markdown编辑器组件|https://github.com/laobubu/HyperMD|
|CodeMirror|浏览器内代码编辑器|https://github.com/codemirror/CodeMirror|
|prism|轻量又好看的代码高亮库|https://github.com/PrismJS/prism|
|markdown-it|强大的markdown解析器|https://github.com/markdown-it/markdown-it|
|markdown-it-prism|使用prism高亮markdown-it中的代码块|https://github.com/jGleitz/markdown-it-prism|
|markdown-it-emoji|用于markdown-it中的表情解析|https://github.com/markdown-it/markdown-it-emoji|
|markdown-it-anchor|用于markdown中给标题增加id|https://github.com/valeriangalliat/markdown-it-anchor|
|moment|增强js的时间处理|https://github.com/moment/moment|
|v-viewer|强大的图片预览组件|https://github.com/mirari/v-viewer|
|vue-canvas-nest|用于画布嵌套的Vue.js背景组件|https://github.com/ZYSzys/vue-canvas-nest|
|vue-drag-verify|用于滑动验证的vue组件|https://github.com/AshleyLv/vue-drag-verify|
|vuex-persistedstate|用于vuex持久化的组件|https://github.com/robinvdvleuten/vuex-persistedstate|
|Element-ui|适用于Web的Vue.js 2.0 UI工具包|https://github.com/ElemeFE/element|
|iconfont|好看又全面的字体图标库|https://www.iconfont.cn/|
## 开源协议
MIT LICENSE  
> 无论是由于软件，使用或其他方式产生的，与之有关或与之有关的合同，侵权或其他形式的任何索赔，损害或其他责任，作者或版权所有者概不负责。
## 部分截图
![](https://user-gold-cdn.xitu.io/2019/12/25/16f3b531dea56235?w=2525&h=1273&f=png&s=714944)
### 2、写文章

![](https://user-gold-cdn.xitu.io/2019/12/25/16f3b53a03a007c9?w=2299&h=1191&f=png&s=314241)
### 3、文章详情

![](https://user-gold-cdn.xitu.io/2019/12/25/16f3b541e4139f9b?w=2538&h=1267&f=png&s=246017)
### 4、照片墙

![](https://user-gold-cdn.xitu.io/2019/12/25/16f3b55499b2ab33?w=2542&h=1204&f=png&s=1811660)
### 5、侧边栏

![](https://user-gold-cdn.xitu.io/2019/12/25/16f3b54e1f6f606a?w=444&h=1272&f=png&s=842554)
### 6、分类

![](https://user-gold-cdn.xitu.io/2019/12/25/16f3b55e380f768d?w=2525&h=1218&f=png&s=420762)
