# 大前端高薪训练营 v3.0 课程大纲

## **开营破局** · 打开晋升通道

- 前端如何一步一步变成大前端
- 大前端时代下的前端开发
- 前端开发者的进阶路径
- 训练营整体内容概述

## **Part 1** · JavaScript 深度剖析

> _全方位夯实 JavaScript 语言本身及周边_

### 学习目标

- 充分掌握 ES2016 - ES2020（ES7 - ES11）新特性、迭代器模式
- 掌握使用 Babel 编译、Polyfill 等方案处理新特性环境兼容问题
- 理解单线程下的 JavaScript 异步模式执行机制，根治此类面试题
- 掌握 JavaScript 处理异步任务的消息队列和事件循环，以及宏任务和微任务
- 理解 JavaScript 语言自有类型系统的不足以及相应的解决方案
- 掌握 TypeScript 基本语法、高级特性、内置标准库以及类型补充声明
- 掌握函数式编程范式，理解函数式思想，为深入源码学习做出铺垫
- 理解 JavaScript 中的内存管理机制、回收机制、相关算法
- 掌握 JavaScript 语言层面性能优化的 10 大优化细节

### ECMAScript 新特性

- JavaScript vs. ECMAScript
- 块级作用域、模板字符串
- 对象与数组的解构、rest 操作符
- 函数进阶（箭头函数、默认参数）
- 对象和数组的扩展用法
- Proxy、Reflect、Map、Set、Symbol
- for...of、迭代器模式、生成器函数
- ES Modules 模块系统
- ES2016 - ES2020（ES7 - ES11）特性一览
- 新特性编译工具（Babel）的使用
- 新特性的 Polyfill：CoreJS 标准库

### JavaScript 异步编程

- JavaScript 的单线程设计
- 同步模式和异步模式的调用差异
- 回调函数的执行原理
- Promise 异步方案的使用进阶与剖析
- 处理异步任务的任务队列和事件循环
- JavaScript 内部的宏任务与微任务
- ES 6 Generator 迭代器的异步应用
- 使用 Async / Await 语法糖编写扁平的异步代码
- 手写 Promise 源码实现

### TypeScript 高级编程

- 编程语言的几种不同类型系统
- JavaScript 自有类型系统的问题
- Flow 静态类型检查方案
- Flow 工具的配置及相关插件的使用
- TypeScript 基本语法
- TypeScript 高级特性（泛型、接口）
- TypeScript 内置对象标准库
- TypeScript 的类型声明

### 函数式编程范式

- 函数式编程的本质以及应用场景
- 如何以函数式编程风格创建应用程序
- 用简单的代码构建复杂的应用程序
- 纯函数的定义以及为什么使用纯函数
- 为什么消除和控制副作用如此重要
- 柯里化、compose、高阶函数的优点
- 不可变的数据结构
- 常见库（Lodash、Ramda.js）

### JavaScript 性能优化

- JavaScript 中的垃圾收集
- JavaScript 内存管理
- V8 垃圾回收机制分类
- 引用计数、标记清除、标记整理和增量标记
- Preformance 工具的使用及注意事项
- 10 个代码层面的优化细节

## **Part 2** · 前端工程化实战

> _远离刀耕火种的原始时代，全面提升战斗力_

### 学习目标

- 理解前端工程化的定义及组成，以及对现代前端项目的重要性
- 理解脚手架工具的设计思想和目标，掌握通用型脚手架工具的使用及扩展
- 掌握如何设计并开发一款符合自己企业个性化需求的脚手架工具
- 掌握自动化构建任务工具的使用，理解其实现原理和扩展方式
- 掌握如何基于 Gulp 这类工具定制「傻瓜式」自动化工作流工具
- 掌握前端项目工作流中的自动化部署实现方式（CI/CD）
- 理解前端模块化的必要性以及模块化的发展演进过程（读史明智）
- 掌握使用 Webpack 实现前端项目整体模块化的实践方式
- 掌握 Webpack 最核心的 Loader 和 Plugin 机制，并能够开发自定义扩展
- 掌握 Webpack 中 Tree-shaking、sideEffects、CodeSplitting 等高级特性
- 掌握 Webpack 实现原理，手写实现 Webpack 核心源码
- 掌握前端规范化在企业开发中具体的落地方式及相应工具

### 工程化的组成

- 工程化组成和项目中的表现
- 工程化与工具之间的关系

### 脚手架工具

- 脚手架设计思想与目标
- 脚手架工具的本质作用
- 常用的脚手架工具一览
- Yeoman 的基本使用以及自定义 Generator
- Yeoman Sub Generator 特性
- 基于 Yeoman 创建适合自己的脚手架工具
- Plop 生成器的基本使用
- 使用 Plop 提高项目创建同类文件的效率
- 脚手架工作原理剖析
- 手写一个自己的脚手架工具：caz

### 自动化构建

- 如何使用自动化构建提高开发效率
- 常用的自动化构建任务执行器
- npm scripts & script hooks
- Grunt 工具的使用及扩展开发
- Gulp 的使用以及任务结构
- 基于 Gulp 创建自动化构建工作流
- 封装独立的自动化构建工具
- FIS 3 的使用以及常用的扩展插件

### 自动化部署（CI / CD）

- 持续集成与持续部署
- 基于 GitHub / GitLab 的自动化工作流搭建
- 常见的 CI 实践：Jenkins、GitLab CI、Travis CI、Circle CI
- 开源项目的新选择：GitHub Actions
- 基于常用 CI 系统实现静态 / Node 类型的项目自动部署

### 模块化开发与 Webpack

- 模块化标准与规范
- ES Modules 标准的支持情况
- Webpack 打包工具的基本使用
- Webpack 的配置详解
- Webpack 打包过程和打包结果分析
- Webpack 中资源模块的加载（Loader）
- 如何开发一个 Webpack 的 Loader
- Webpack 的插件机制
- 开发一个 Webpack 插件
- Webpack 周边生态（Dev Server、HMR、Proxy）
- Webpack 高级特性（Tree-shaking、sideEffects)
- Webpack 打包过程及打包结果的优化
- 深度剖析 Webpack 实现原理（AST 语法树）
- 其他常见的打包工具（Rollup、Parcel）
- 手写 Webpack 源码，掌握 Webpack 原理

### 规范化标准

- 常见的代码 Lint 工具（ESLint、Stylelint）
- 创建项目或者团队专属的 Lint 规则 / 风格
- 通用型代码格式化工具 Prettier
- 结合自动化工具或者 Webpack 的使用
- 配合 Git Hook 确保源代码仓库中代码的质量
- 结合脚手架、自动化、模块化、规范化搭现代化前端工程

## **Part 3** · Vue.js 框架源码与进阶

> _目前国内应用最为广泛的 Vue.js 框架实现原理与高阶用法_

### 学习目标

- 掌握 Vue Router、Vuex 等 Vue.js 生态下主要库的实现原理，手写源码
- 理解虚拟 DOM 机制，掌握 Diff 算法的实现原理及工作过程
- 掌握如何实现一套数据响应式系统，理解核心原理过程
- 理解 Vue.js 的整体实现过程、响应式机制、模板编译、组件实现机制
- 掌握如何开发符合企业个性化需求的 Vue.js 的组件库
- 掌握 Monorepo、Yarn workspace、Lerna、Storybook、Rollup、自动化测试
- 理解 CSR 存在的问题，了解 SSR 概念、优势及实现原理
- 掌握如何使用 Nuxt.js 快速实现 Vue.js 框架的 SSR 项目开发
- 掌握静态站点生成（SSG）方案及 Gridsome 框架
- 理解 Vue.js 3.0 的设计动机、Composition API，以及响应式原理
- 掌握基于 Bundleless 概念的 Vite 工具的使用及核心原理，手写源码实现
- 掌握基于 TypeScript 的 Vue.js 项目实战，掌握类型补充声明的使用
- 能够开发项目中的独立业务功能，权限管理、动态菜单、身份认证等
- 掌握如何搭建服务器生产环境（docker），能够独立部署完整前端项目

### 手写 Vue Router、响应式核心原理、虚拟 DOM

- Vue.js 框架基础回顾、生命周期、组件结构
- 手写 Vue Router 实现原理（Hash、History、嵌套）
- 手写 Vue.js 2.x 响应式原理（发布订阅、观察者）
- Vue、Observer、Compiler、Dep、Watcher、双向绑定
- Virtual DOM 的作用和优势、Snabbdom 的基本使用
- Vue.js 的 Virtual DOM 实现库：Snabbdom 源码解读
- 虚拟 DOM 和 Diff 算法的实现
- h 函数、VNode、patch、createElm、patchVnode

### Vue.js 2.6 框架核心源码剖析

- Vue.js 初始化过程（成员初始化、首次渲染）
- Vue.js 内部数据响应式相关的实现原理源码
- Vue.js 内部 Virtual DOM 部分相关源码解析
- Vue.js 内部组件化机制的实现原理剖析
- Vue.js 内部模板编译过程
- compileToFunctions、compile、AST、parse、optimize、generate
- Vue.js 相关源码的调试、Vue Template Explorer

### Vuex 数据流方案、手写实现 Vuex 框架

- Vue.js 组件间通信方式方式总结复盘
- Vuex 库的基础概念回顾
- State、Getter、Mutation、Action
- Vuex 的模块化（Module）开发与插件（Plugin）机制
- Vuex 的严格模式与非严格模式之间的差异
- 使用 Vuex 重构电商应用的购物车模块
- 手写实现 Vuex 框架、理解 Vuex 实现原理

### Nuxt.js 服务端渲染（SSR）及同构开发

- 传统的服务端渲染模式与客户端渲染模式
- 现代化 SPA 框架下的的服务端渲染模式
- 通过 Nuxt 体验同构渲染以及同构开发的优势
- Nuxt.js 框架快速上手与案例实战
- Nuxt.js 框架中的异步数据处理（asyncData、上下文对象）
- PM2 启动 Node.js 服务、自动化部署（GitHub Actions)
- Vue.js 实现 SSR 的原理以及如何搭建自己的 SSR
- 静态站点生成方案（SSG）的趋势及原因
- 基于 Vue.js 实现的 SSG 框架：Gridsome 实战

### Vue.js 自定义组件库开发与 Monorepo

- Vue CLI 快速原型开发、组件边界情况处理
- 组件库类型项目的基本结构搭建
- 步骤条组件、表单组件的开发
- Storybook 组件自动化测试与预览
- Yarn workspaces 功能、Lerna 以及 Monorepo
- Vue.js 组件的自动化测试、单元测试
- 基于 Rollup 打包组件库类型的项目
- 开发可复用的组件库项目模版用于生成组件基本结构

### Vue.js 3.0 Composition APIs 及 3.0 源码剖析

- Vue.js 3.0 设计和用法的变化以及优势
- Vue.js 3.0 Composition APIs 的设计动机以及优势
- Vue.js 3.0 在性能上得到的提升与改进
- 全新的 Web 开发工具：Vite 体验与上手
- Composition APIs 基本结构（响应式、生命周期、计算属性）
- 基于 Composition APIs 构建 TODO List 应用案例
- 手写 Vue.js 3.0 响应式原理（Proxy、依赖收集、effect/track）
- 手写 Vite 工具、Vite 核心原理、@vue/compiler-sfc

### Vue.js + TypeScript 实战项目开发与项目优化

- 使用 TypeScript 开发 Vue.js 应用
- Vue.js + Vue Router + Vuex + TypeScript 项目实战
- 常见的后台业务功能，例如：权限管理、动态菜单、身份认证等
- 课程管理、内容管理、用户管理、广告维护
- Husky + Commitlint + ESLint 代码质量保证
- 基于 GitLab CI + Jenkins 自动化应用部署
- Vue.js 项目优化

## **Part 4** · React 框架原理与实战

> _掌握业界口碑最佳的 React 框架的设计哲学与高级特性_

### 学习目标

- 掌握 React 设计思想及优势，理解为什么大厂更偏爱 React 技术栈
- 掌握 React 框架下的 Virtual DOM 实现原理与 Vue.js 框架的差异点
- 掌握 React 框架中的协调算法：Fiber、requestIdleCallback API
- 掌握大型 React 项目中不可避免的数据流管理方案：Redux 与 MobX
- 理解 Redux 核心模块实现原理，掌握手写 Redux 核心模块源码
- 掌握 React 16.8 新增的 React Hooks 特性，理解 React Hooks 实现原理
- 掌握 CSS-in-JS 方案及常见的 CSS-in-JS 库：Emotion，理解 CSS-in-JS 思想
- 掌握社区中先进的 React CSS-in-JS 库：Chakra-UI
- 掌握 React 生态下的同构开发、 SSR 方案、Next.js 框架，SSG 方案、Gatsby 框架
- 掌握基于 TypeScript 的大型企业 React 项目搭建与开发
- 掌握 Angular 框架的实战开发，理解 Angular 框架的设计思想
- 掌握响应式状态管理库：RxJS，以及在 Angular 框架下的落地使用实践

### React 设计原理解密及核心源码解读

- React 框架基础回顾、JSX 语法
- 分析 Virtual DOM 目的及实现原理
- 更新 DOM 元素与 VirtualDOM 对比
- React 核心算法：Fiber
- requestIdleCallback API
- React 框架的设计哲学
- React 框架核心源码解读

### React 数据流方案专题（Redux、MobX）

- Redux 核心概念及工作流程
- 在 React 中使用 Redux 解决的问题
- Redux 常用中间件以及中间件的开发
- Redux 数据流实战案例
- Redux 设计原理及源码解读
- Enhancer、applyMiddleware、bindActionCreators、combineReducers
- 新型数据流方案：MobX 快速上手与核心特性

### React Hooks 新特性

- Class 组件存在的不足、React Hooks 要解决的问题
- React 16.8 内置常用 Hook 函数的实战
- useState、useEffect、useReducer、useContext
- 使用 memo 方法提高组件性能
- 如何自定义 React Hooks 函数
- React Hooks 的实现原理
- 手写实现 React Hooks 特性

### CSS-in-JS 方案与 Emotion 库、Chakra-UI

- 为什么会有 CSS-in-JS 这种解决方案
- CSS-in-JS 解决方案的优缺点
- Emotion 库快速上手与实战
- 样式嵌套、媒体查询、全局样式、keyframe 动画
- 现代化 React UI 框架 Chakra-UI
- Chakra-UI 常用组件与内置功能性 API
- Chakra-UI 中的 Color Modes

### 服务端渲染（SSR）方案、同构开发、SSG

- 原生服务端渲染（SSR）的实现
- React 框架下的同构开发
- 服务端渲染模式下的 Redux
- 集成式 SSR 框架 Next.js
- 基于 Next.js 的案例实战
- 部署 Next.js 应用到 Vercel 平台（PaaS）
- 静态站点生成方案及 Gatsby 框架

### React 综合项目实战

- 基于 TypeScript 的 React 项目开发
- React + React Router + Redux + Ant Design + TypeScript 实战
- 后端 Mock 服务接口开发（Node.js + Express + MongoDB)
- 用户鉴权、权限控制、权限管理、动态菜单、身份认证
- 课程管理、内容管理、用户管理、广告维护
- Husky + Commitlint + ESLint 代码质量保证
- 基于 GitLab CI + Jenkins 自动化应用部署

### Angular 企业实战开发

- Angular 11 框架基础快速上手
- Angular 数据绑定及实现原理
- Angular 组件封装及父子组件通信
- Angular 服务模块及服务注入
- Angular 路由模块
- RxJS 响应式编程的库
- NgRx 状态管理工具

## **Part 5** · Node.js 全栈开发

> _打通前后端边界，做企业炙手可热的“无所不能”_

### 学习目标

- 掌握 Node.js 平台下核心机制：非阻塞 IO、EventLoop、消息队列
- 掌握 Node.js 模块加载机制、第三方包机制、CommonJS 实现原理
- 掌握 Node.js 平台下网络编程、TCP/IP 协议、HTTP 服务搭建、Session 原理
- 掌握多进程 Node.js 应用开发以及 Node.js 集群搭建，结合 Nginx 反向代理服务
- 掌握 MongoDB、Redis 数据库的使用及 BFF 层中数据库的应用
- 掌握基于 Express 框架快速开发 API 服务，以及 Koa 框架源码实现
- 掌握 BFF 层 RESTful 接口聚合方案，以及通过 GraphQL 标准提升 API 服务的可复用性
- 掌握阿里推出的 Egg.js 企业级 Node.js 框架，以及 Nest.js 框架落地
- 掌握基于 Egg.js + Mongoose + Nunjucks + TypeScript 的企业级项目实践

### Node.js 高级编程

- 非堵塞 IO、EventLoop、事件队列
- CommonJS 原理解析
- 核心模块、自定义模块、第三方模块
- 文件系统、Buffer 对象、字符编码
- 压缩和解压缩、加密和签名算法
- 网络编程、TCP/IP、HTTP 服务
- cookie 和 session 原理
- 多进程和集群搭建
- 搭建反向代理服务器

### NoSQL 数据库

- NoSQL 数据库特性及优势介绍
- MongoDB 的安装、连接、操作
- mongoose 模块以及常用的操作 API
- Redis 快速上手以及它所适合的场景
- 使用 Node.js 操作 Redis

### Web 开发框架

- Express 完成基本的服务端应用开发
- Express 路由、模板引擎、错误处理
- Express 中间件机制的设计思想
- Express 中间件使用以及自定义中间件
- Express 应用程序的进程管理器
- Express 安全与性能的最佳实践
- Express + Handlebars + Mongoose 实战
- Koa 应用与实践、AOP 面向切面编程
- Koa 中间件实现、源码深度剖析
- Koa 的中间件模型与 Express 的差异
- PM2 宿主部署 Node.js 应用

### GraphQL API 开发

- 基于 Koa 开发 RESTful API
- 应用层最佳接口实践：GraphQL
- GraphQL 规格标准与设计优势
- GraphQL 快速开发库：Apollo
- API 鉴权标准、jsonwebtoken 模块及其相关 API
- Docker Compose + GitLab CI 自动化部署 Node.js 应用

### 企业级框架

- Egg.js 项目架构与脚手架工具
- Egg.js 中间件机制、洋葱圈模型
- Egg.js 路由、控制器、服务
- Egg.js 插件机制以及插件开发
- Egg.js 定时任务调度
- Egg.js + Mongoose + Nunjucks + TypeScript 项目实战
- Nest.js 框架的基本概念和内部组成
- 使用 Nest.js 框架构建高效且可伸缩的服务端应用
- Nest.js 面向切面编程、依赖注入的实践

## **Part 6** · 泛客户端开发

> _泛客户端大行其道，高级前端开发者务必掌握多端开发，从容应对不同客户端载体_

### 学习目标

- 掌握微信小程序原生开发，以及 MINA 框架结构
- 掌握 uni-app 多端统一开发解决方案、能够使用一套代码部署至所有移动平台
- 掌握基于 uni-app 的多媒体分享社区小程序项目开发
- 了解京东凹凸团队推出的 Taro 框架，理解其实现原理
- 掌握基于 H5 + 原生 WebView 的 Hybird App 开发方案，了解 JSBridge 通讯
- 掌握 React Native 技术方案，了解目前企业对 React Native 技术栈的落地方案
- 掌握 Dart 语言，能够使用 Flutter 完成真正意义上的原生 App 开发
- 掌握基于 Flutter 的在线教育 App 开发
- 掌握 Electron 整体架构，能够基于 Electron 使用 Web 技术开发桌面应用
- 掌握 Vue.js / React 这类框架在 Electron 平台下落地使用的最佳实践

### 小程序与快应用

- 原生小程序 MINA 框架回顾
- uni-app 多端统一开发方案
- 基于 uni-app 框架开发小程序应用
- 基于 uni-app 框架打包快应用和 H5
- 京东 Taro 多端统一开发方案

### Hybrid App 开发

- 基于 WebView UI 的基础方案
- Cordova / Ionic 通用型混合 App 开发框架
- Cordova 的实现原理分析以及它的常用插件
- H5 配合原生 WebView 开发混合式 App
- 通过 JSBridge 完成 H5 与 Native 的双向通讯
- 原生 App 开发相关知识

### React Native

- React Native 开发环境搭建
- 初始环节搭建以及相关基础配置
- 热更新的开发体验
- 使用 Flexbox 实现界面布局
- 常见界面布局和长列表呈现
- 接入第三方 Native 组件（Objective-C / Swift / Java）
- React Native 架构的实现原理

### Flutter 原生 App 开发

- Flutter 概述以及 Windows / macOS 环境搭建
- Dart 语言快速上手、包管理工具
- Flutter 快速上手、开发体验、路由和导航
- UI 开发：内置 Material Design 和 Cupertino（iOS 风格）Widget
- 常用 Widget、表单组件、布局方式
- 数据响应：界面状态管理
- 网络编程以及相关第三方包
- Native 功能和 SDK 的调用
- Flutter 在线课堂项目实战案例

### Electron 桌面应用开发

- Electron 运行时的基本结构分析
- 快速上手、常用 API、基础案例
- 主进程与渲染进程之间的差异以及相互通信
- 常见桌面应用程序功能的实现
- Electron 结合 React / Vue.js 之类的前端框架
- Electron 应用的调试（主进程与渲染进程）以及相关工具（Spectron / Devtron）
- 集成式打包工具（electron-builder / electron-packager / electron-forge）
- 实战案例：模仿 Microsoft To Do

## **Part 7** · 商业技术解决方案与高阶技术专题

> _通过更多的行业商业级技术解决方案，落地更多优秀技术_

### 学习目标

- 了解 Serverless 无服务端架构方案的优势及发展趋势
- 掌握基于「腾讯云 / 阿里云」云函数的微服务开发
- 了解微前端架构诞生的背景以及所要解决的问题，理解实现思路
- 掌握基于 Single SPA 的微前端框架，以及 Webpack 5 最新推出的模块联邦特性
- 掌握企业级 App 中最常见的长列表无线滚动功能性能优化方案
- 掌握前端大数据展示、数据可视化框架 ECharts、AntV，以及 3D 可视化框架 Three.js
- 了解淘宝推出的基于 Node.js 的中途岛解决方案，掌握 BFF 架构
- 了解 PWA 渐进式 Web 应用开发方案、ServiceWorkers
- 掌握数据埋点系统设计、上报服务、客户端 SDK 封装
- 了解 Web 安全和前端应用性能解决方案

### Serverless 无服务端架构方案

- BaaS / FaaS / PaaS 服务
- Serverless 架构与实现原理
- Serverless 应用场景与局限性
- 国外常见的 Serverless 服务（Vercel、Netlify）
- 国内常见的 Serverless 服务（阿里云、腾讯云）

### 微前端架构与实践

- 微前端诞生的背景和解决的问题
- 微前端下的工程化实践
- single-spa 框架、Webpack 5 模块联邦
- 如何同时使用 React / Vue.js / Angular 等不同的框架
- 开发一个简单的微前端框架

### 长列表无限滚动优化方案

- 触底加载更多功能的实现
- 长列表渲染卡顿问题的原因
- 高性能长列表渲染的思路：虚拟列表
- 不同框架下长列表无限滚动的实现方法
- 高性能滚动及页面渲染优化

### 大数据可视化

- 相关知识储备：Canvas、SVG
- 数据可视化的目标
- 实现数据可视化的常用方式
- 相关库：D3.js、AntV、ECharts.js、Three.js

### 中途岛 / 中间层方案

- BFF 架构的优势及常见方式
- 基于 Node.js 的中间层架构
- 实现更合理的前后端分离架构
- 中间层的目标与职责
- 后端细粒度接口聚合
- 服务端模板渲染
- 前端路由设计

### PWA 渐进式 Web 应用

- PWA 使用场景分析
- 服务端 / 客户端离线缓存技术
- 浏览器多线程环境
- 通过 ServiceWorkers 让 PWA 离线工作
- ServiceWorkers 的生命周期
- 基于 PWA 的消息推送、应用更新
- 渐进式加载

### 更多常见技术方案

- RBAC 权限管理及鉴权方案
- 接口 Mock 方案
- OSS 云存储方案
- CDN 加速方案
- H5 直播方案
- Web 安全专题（HTTPS、XSS / CSRF、CSP）
- 前端应用性能专题

## **Part 8** · 大厂面试指导

> _临门一脚，如何脱颖而出，立于不败之地？_

### 学习目标

- 狂扫 Leet Code 经典算法题，掌握前端常见数据结构与算法相关知识储备
- 全面拆解历年百度、阿里、腾讯、京东、头条、美团、滴滴经典前端面试题
- 面试专项能力突击，简历指导，一、二、三、四面注意事项及侧重点
- 大厂面试过程中屡试不爽的表达套路，学会在面试中更好的发挥应有水平
- 高分简历参考、1v1 重写简历，合理表达自己
- 掌握数据结构基础、了解常见前端算法
- 掌握 BATJ、TMD 常见面试题
- 轻松应对技术，人事，项目，leader 四面轰炸

### Leet Code 精选题

- 常用数据结构介绍
- 常见算法题解析
- 常见数据结构题解析

### BATJ、TMD 高频面试真题

- BATJ、TMD 高频前端框架题解析
- BATJ、TMD 高频前端原理题解析
- BATJ、TMD 高频前端应用题解析

### 面试专项能力突击

- 一面：编程基础能力考察
- 二面：项目经验考察
- 三面：方案设计综合能力考察
- 四面：HR 综合软素质考察

### 面试过程发挥应有水平

- 学会表达：如何把硬实力表达出来
- 扬长避短：如何表现出自己的闪光点
- 洞悉套路：面试考察点与答题套路指导
- 面试指导：面试前 1v1 辅导
- 面试复盘：面试后 1v1 复盘

### 打造一份让人无法拒绝的简历

- 高分简历模板分析
- 打造一份高分简历的方法
- 模拟训练：重写简历 1v1 指导服务

## **结营精华** · 职业发展规划

- 前端行业技术前景展望
- 高级前端开发者的晋升通道
- 技术岗位周边技能的认知
- 打造属于自己的技术发声渠道
