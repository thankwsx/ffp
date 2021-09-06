Basic
- HTML

    ```基础的html及html5的支持，通过w3school的官方网站学习即可，时不时看一下，还会有一些意外收获。```
- CSS
    - preprocess

        ```浏览器对css的支持还不完善的早年，有很多异军突起的尝试以编程思想控制css的库诞生```
        - [less](https://lesscss.org/) 支持变量，嵌套等等
    - Framework
        - [tailwindcss](https://tailwindcss.com/) 理念与众不同，但是和浏览器一致的css功能库。

- JavaScript

    ```JS的基础知识很庞杂，主要先看这两本线上教程即可```
    * [Javascript教程](https://wangdoc.com/javascript/)
    * [ES6标准入门教程](https://wangdoc.com/es6/)

Junior
- Git

    ```与人协作，必不可少```
    - github

        ```如果想在开源项目上面有所作为，尽早熟悉github的一切必要操作。```
- Net

    ```前后台交互，网络知识必须学习```
    - http
        - [http时延小实战](http://www.disheng.tech/blog/%E7%AE%80%E5%8D%95%E7%9A%84-http-%E8%B0%83%E7%94%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E6%97%B6%E5%BB%B6%E8%BF%99%E4%B9%88%E5%A4%A7/)
    - https
    - http2
        - [nginx如何支持http2](https://developer.aliyun.com/article/7171)
        - [HTTP合并请求与拆分的实验](https://cloud.tencent.com/developer/article/1837260)
    - websocket
- IDE
    - vscode
        - [editorconfig](https://editorconfig.org/) 多人开发时保持代码风格的一致性
        - [不同编程语言支持的内部逻辑](https://code.visualstudio.com/api/language-extensions/overview)
        - [内置支持TypeScript语言](https://code.visualstudio.com/docs/languages/typescript#_formatting)
        - [volar扩展，for Vue3](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)
- Browser
    - chrome
        - [CSP Content Security Policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) 网络安全开发比较重要的知识点
        - [Link Preload](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types/preload) 从代码角度控制资源加载优先级的手段

- Framework

    ```现代应用开发不可能离开框架了，但是还没有走过框架这一步```
    - vue

        ```快速发展中的前端框架之一```
        - 快速搭建后台应用系统的脚手架框架[vue-element-admin](https://github.com/PanJiaChen/vue-element-admin/blob/master/README.zh-CN.md)，基于vue2.6（上一代版本）+ elementui
        - 快速搭建后台应用系统的脚手架框架[vite-vue3-admin](https://github.com/buqiyuan/vite-vue3-admin)，基于vite2.0和vue3+antd等
        - [Vite](https://cn.vitejs.dev/)，新一代前端开发与构建工具，主要服务于vue，但是实际上于框架无关。
        - vue的UI库
            - 2021年最佳Vue3 UI框架推荐 [juejin指引链接](https://juejin.cn/post/6995519561030172702#comment)
            - [vue3.0下setup脚本的写法](https://chengpeiquan.com/article/vue3-script-setup.html)
            - [vue的性能优化](https://juejin.cn/post/6940190960609394695)
    - react
    - angular
- Library

    ```如果开发的应用中需要大量的图表展示，则必学```
    - highcharts
    - echarts
- Node

    ```如果前端要做一些纯后端的工作，最好的入门方式是node相关模块```
    - Nuxt.js
    - Next.js
    - npm
        - package
            - [he](https://www.npmjs.com/package/he)  html实体编解码库
            - [lite-server](https://www.npmjs.com/package/lite-server) 轻量级开发用web服务器
            - [regenerator-runtime](https://www.npmjs.com/package/regenerator-runtime) 用于在旧式浏览器支持async/await的库
        - config
            - [module配置](https://loveky.github.io/2018/02/26/tree-shaking-and-pkg.module/)
    - pm2

        ```一个非常流行的node应用管理工具，可以方便的启动或者停止node应用```
        - [pm2启动配置文件](https://pm2.keymetrics.io/docs/usage/application-declaration/)
- Deploy

    ```做完应用开发之后，需要进行部署，部署工具需要学习```
    - linux
        - shell
            - [shell特殊变量](https://blog.csdn.net/w746805370/article/details/51044352)
    - ssh
    - docker
    - Server
    
        ```也可能使用传统的部署方式，直接使用服务器的方式```
        - nginx
        - apache

Senior

```业务发展，涉及到更多的环境和平台，中小企业没有财力支持太大的团队，跨平台开发能力重要性突显```
- TypeScript

    ```虽然ts语言的学习不是必须的，但是作为一门规范化了的语言，掌握ts是一个加分项。```
- 小程序
    
    ```快速试错，采用小程序的方式开发错不了```
    
    - [小程序入们核心概念——小程序登录](https://developers.weixin.qq.com/miniprogram/dev/framework/open-ability/login.html)
- electron
    
    ```如果需要使用桌面应用进行推广宣传，可以使用electron```
- native

    ```一般不会独立存在，适用于和客户端打配合的业务场景```
- reactive programming
- ioc
- extension

    ```有时候也可以试试浏览器扩展的开发模式，适用PC端快速试错```
- 构建

    ```不知何时，前端语言变得比后端语言还臃肿，打包CI工具眼花缭乱，grunt、gulp，接踵而至。目前占主导地位的是以为大佬webpack```
    - [webpack](https://webpack.js.org/) 不是故意将工作流构建和打包混为一谈。
        
Project
- 实际问题
    - 用户登录

        [一篇简单的小文章介绍](https://juejin.cn/post/6844904129337229325)
- 配置化
- 缓存
- 设计模式
- 工程模式
    - monorepo 
        - [lerna](https://github.com/lerna/lerna) 
- 算法
- 性能
- 安全

    ```凡事对外的服务，一定要考虑安全问题，前端也是如此。```
    - [OWASP组织- Open Web Application Security Project](https://owasp.org/)
- 微服务
    - 微前端框架 [qiankun](https://qiankun.umijs.org/zh/guide)基于single-spa
    - 前端微服务框架 [single-spa](https://single-spa.js.org)
- SSR(服务端渲染)
    - [必要性，知乎贴](https://www.zhihu.com/question/308792091)
    - [React服务器端组件](https://addyosmani.com/blog/react-server-components/)
    - [Vue SSR工程实践](https://zhuanlan.zhihu.com/p/60816418)
- code review
- 问题排查
- 实用工具

    ```介绍常用的一些工具，但不会很深入```
    - [browsersync](https://browsersync.io/) 高效浏览器同步测试工具
    - [cloc](https://github.com/AlDanial/cloc) 统计代码行数的工具
    - [import-map-overrides](https://github.com/joeldenning/import-map-overrides) 在新式浏览器的module加载工具链中占有一席之地

大神列表
  - [Addy Osmani - chrome工程师](https://addyosmani.com/)

Reference
- site
- wechat
- book
