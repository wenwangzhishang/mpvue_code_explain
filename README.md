## 目的
该仓库主要用来 学习 mpvue 相对于vue 做了哪些改变
## mpvue 最后一个正式版本
#2018.8.10
发布 mpvue-loader@1.1.2

#
## 步奏
1、先看目录  mpvue 框架的目录基本上和vue 的没有什么不同
2、src platforms 下多了一个mp目录 
3、package.json 的运行命令 多了关于mpvue 的打包方案


# mpvue
> Vue.js 小程序版, fork 自 [vuejs/vue@2.4.1](https://github.com/vuejs/vue)，保留了 vue runtime 能力，添加了小程序平台的支持。


`mpvue` 是一个使用 [Vue.js](https://vuejs.org) 开发小程序的前端框架，目前支持 `微信小程序`、`百度智能小程序`，`头条小程序` 和 `支付宝小程序`。 框架基于 `Vue.js`，修改了的运行时框架 runtime 和代码编译器 compiler 实现，使其可运行在小程序环境中，从而为小程序开发引入了 `Vue.js` 开发体验。

## mpvue 2.0

mpvue 2.0 开始正式支持 **百度智能小程序**、**头条小程序** 和 **支付宝小程序**，使用 `mpvue-quickstart` 项目模板新创建的项目，将默认升级到 2.0。老项目可继续使用原有版本。详情请参见 [**mpvue 2.0 升级指南**](https://github.com/Meituan-Dianping/mpvue/releases/tag/2.0.0)

**新版本的问题或建议，有请各位关注者及时反馈，mpvue 2.0 祝大家节日快乐~** -2019.02.14

### mpvue 1.x 稳定版本
**对于不升级 2.0 的项目，可以继续使用1.x 的大版本，目前1.x 会持续在 1.4.x 上继续维护** 升级方式参见：[1.x 稳定版说明](https://github.com/Meituan-Dianping/mpvue/releases/tag/2.0.0)

[mpvue 文档](http://mpvue.com)

## 快速开始

我们精心准备了一个简单的 [五分钟上手教程](http://mpvue.com/mpvue/quickstart) 方便你快速体验到 `mpvue` 带来的开发乐趣。

## 名称由来
- `mp`：mini program 的缩写
- `mpvue`：Vue.js in mini program

## 主要特性
使用 `mpvue` 开发小程序，你将在小程序技术体系的基础上获取到这样一些能力：

- 彻底的组件化开发能力：提高代码复用性
- 完整的 `Vue.js` 开发体验
- 方便的 `Vuex` 数据管理方案：方便构建复杂应用
- 快捷的 `webpack` 构建机制：自定义构建策略、开发阶段 hotReload
- 支持使用 npm 外部依赖
- 使用 `Vue.js` 命令行工具 vue-cli 快速初始化项目
- H5 代码转换编译成小程序目标代码的能力

其它特性正在等着你去探索。


## 配套设施
`mpvue` 作为小程序版本的 `Vue.js`，在框架 SDK 之外，完整的技术体系还包括如下设施。

- [mpvue-loader](http://mpvue.com/build/mpvue-loader) 提供 webpack 版本的加载器
- [mpvue-webpack-target](http://mpvue.com/build/mpvue-webpack-target) webpack 构建目标
- [postcss-mpvue-wxss](http://mpvue.com/build/postcss-mpvue-wxss) 样式代码转换预处理工具
- [px2rpx-loader](http://mpvue.com/build/px2rpx-loader) 样式转化插件
- [mpvue-quickstart](http://mpvue.com/mpvue/quickstart) mpvue-quickstart
- [mpvue-simple](http://mpvue.com/mpvue/simple) 辅助 mpvue 快速开发 Page / Component 级小程序页面的工具
- 其它



