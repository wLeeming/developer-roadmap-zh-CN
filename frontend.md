> 路线图的文字表单形式，欢迎 fork 并用来跟踪你的学习进度

> 翻译：@ccloli  
> 译注：本文仅对原文进行原样翻译，文章及图片中提到的个人观点均为原作者之观点。因个人翻译水平有限，翻译文本可能会稍有出入或略带意译。对于可能有明显歧义的地方，会在文后标记英文原文。如果您有翻译改进之建议，欢迎提交 issue 或 PR。提交 issue 与 PR 以改进翻译为主，如果您认为路线图可以改进，建议您向原 repo 提交贡献，谢谢。

## 前端开发路线图 – 2018

这个文件将前端开发路线图转换成了任务清单，这样可以让其他人更容易进行贡献，fork，以及跟踪他们的进度。你可以在这篇前端开发路线图的 [medium 文章](https://medium.com/@kamranahmedse/modern-frontend-developer-in-2018-4c2072fa2b9c)中查看评论

## Step 1 – 学习基础

你需要做的第一件事就是学习基础，这包括学习 HTML 基础、CSS，以及对 JavaScript 的语法有一些熟悉。

- [ ] 学习 HTML 基础
  - [ ] 学习 HTML 基础与如何编写语义化的 HTML
  - [ ] 将页面划分为多个节并了解如何准确地构建 DOM
  - [ ] **任务** 制作至少 5 个 HTML 页面 – 专注于结构，先不要在意如何 *美化* 它们
- [ ] 学习 CSS 基础
  - [ ] 学习 CSS 基础知识
  - [ ] 学习如何使用网格 (Grid) 和弹性盒子 (Flexbox)
  - [ ] 媒体查询 (Media Queries) 和如何制作响应式网站
  - [ ] 理解 CSS 标准、盒模型等
  - [ ] **任务** 为你之前创建的 HTML 页面加上样式
- [ ] JavaScript 基础
  - [ ] 了解语法与基础代码结构
  - [ ] 了解如何操作 DOM
  - [ ] 了解诸如变量提升 (hoisting)、事件冒泡、原型 (prototype) 等概念
  - [ ] 了解 Ajax (XHR)
  - [ ] 了解 ES6+ 的新功能并编写模块化的 JavaScript
- [ ] 学习 jQuery – **可选（你可以先继续往下，过会儿再回来）**

## Step 2 – 练习你已经学到的！

I say this a lot and I will say it here again, you don’t learn anything without practice. You might have a momentary feeling that you understand something but it would soon go away if you don’t practice. Make sure that you practice as much as you can, while you are following this roadmap.

做一些响应式的页面，并使用 JavaScript 进行一些交互。 You can copy any existing webpage that you might find interesting but **remember to use everything that you have learnt till this point**.

## Step 3 – 可选但是高度推荐

Before you go any further, I would recommend you to go and learn some [git](https://git-scm.com/) if you haven't learnt already. it is really going to help you as you go further. You don't have to learn everything about it, just learn the below listed and keep learning as you continue and face any issues.

Its time to get into the real business now. 打开 [Github](https://github.com)，搜索一些项目，然后给开源项目开一些 pull request。下面是一些关于 pull request 的建议：
- 提升 UI 效果，使一些示例页面实现响应式设计或增强设计效果
- 寻找一些你能解决的 open issue
- 重构一些代码，或者实现一些你学习过程中了解到的最佳实践

记得添加这个 repo 的链接，告诉他们你正在学习，并询问他们对你的 PR 的意见以及如何改进。

## Step 4 – 学习包管理工具

NPM 和 Yarn 在使用上是几乎一样的；你可以学习其中一个，你就会学习到另一个。

- [ ] 学习如何使用 NPM
- [ ] 学习如何使用 Yarn
- [ ] 了解语义化版本控制 (Semantic Versioning)
- [ ] **任务** 使用 yarn 或 npm 安装一些在你之前做的网页中所用到的额外的库

## Step 5 – 学习 CSS 预处理器

预处理器能让你在 CSS 之上添加更强大的功能，让你做一些CSS 不能做到的事。There are different many options Sass, Less, Stylus etc. If I were to pick one, I would go for Sass. However, PostCSS has been gaining a lot of traction lately, 它可以说是锦上添花 (nice-to-have)，可以说是CSS 的“Babel”。你可以独立地使用它，也可以在 Sass 之上使用它。我建议你先学习 Sass，之后有时间再去了解下 PostCSS。

- [ ] 选择其中一个
  - [ ] **Sass (建议)**
  - [ ] Less
  - [ ] **PostCSS (之后再学习这个)**
  - [ ] Stylus

## Step 6 – 学习 CSS 框架

This used to be way up in the chart, but I moved it down below as they aren't really needed any more and can be mastered without much effort. If you would want to pick any, there is one under every rock. The ones that I liked the most among the ones that I tried are Bootstrap, Materialize and Bulma. But if you look at their demand in market I would pick Bootstrap if I was starting today.

- [ ] **Bootstrap (建议)**
- [ ] Materialize CSS
- [ ] Bulma

## Step 7 – 学习如何组织 CSS

As your applications grow, CSS start to become messy and unmaintainable. 有很多种方案可以让你的 CSS 的结构变得更好

- [ ] **BEM – 建议**
- [ ] OOCSS
- [ ] SMACSS
- [ ] SUITCSS
- [ ] Atomic

## Step 8 – 学习构建工具

These are the tools that help you in bundling, building and development of your frontend applications

There used to be alot of stuff in the task runners but today 我会选择使用 NPM scripts, 当然如果你想要去选择其他的，参考一下 gulp

- [ ] **NPM Scripts (建议)**
- [ ] Gulp

There are several linters, but I would go for ESLint. Feel free to have a look at others and see why one over the other

- [ ] **ESLint (建议)**
- [ ] JSLint
- [ ] JSHint
- [ ] JSCS

**开发应用时用 Webpack，开发库时用 Rollup**。当然，你现在还不需要 rollup；它能做的事，webpack 也可以做，so go for Webpack and look into Rollup later

- [ ] **Webpack (建议)**
- [ ] Rollup
- [ ] Parcel

## Step 9 – 做些东西 – 比如一个库

Go to Github and Have a look at the source code of libraries that people have made, pick an idea and make some library with the below listed requirements

- [ ] 它使用了 Sass 来编写样式
- [ ] 它使用了 ES6 编写
- [ ] 它是一个 UMD 库
- [ ] 它使用了 Babel 来让更老的浏览器运行

## Step 10 – 学习一个框架

There are several options, when it comes to frameworks. However, below listed frameworks are the ones that I would recommend. You can pick any of them, however if you ask me for the personal picks I would choose React or Angular. However, have a look at any of them and see what you like

- [ ] **React**
  - [ ] Redux - 适合大规模应用，也可以在 react 外使用
  - [ ] Mobx - 适合小规模应用，也可以在 react 外使用
- [ ] **Angular (重要 – 学习 Angular 2+)**
  - [ ] Rx.js – 它真的很棒，也可以在 angular 外使用
  - [ ] Ngrx
- [ ] Vue.js
  - [ ] Vuex - 和 redux 很像，但是是给 Vue 用的

## Step 11 – 练习时间

现在你已经掌握了构建一个现代化 JavaScript 应用可能需要的 _所有知识_ 了。继续前进，使用你所选择的任何框架来制作一个应用。你可以试试在 repo 的 `ideas` 文件夹内找一些灵感（译注：然而原作者忘了写 ideas）。随便选择一个，然后开始吧！

## Step 12 – 学习性能

Once you are done making the application from Step 9, 学习如何**管理和提升你的应用的性能**。比如 **Interactivity Time**、**Page Speed Index**、**Lighthouse Score** 等。

## Step 13 – 测试你的应用

现在有越来越多的针对 *不同需求* 的测试工具。我自己大多结合 Jest、Mocha、Karma 和 Enzyme 使用。然而，在你学习他们之前，建议你**先去理解不同的测试类型**，尝试所有的测试工具，然后选择最适合你需要的那些工具。

这里有一份很好的总结帮助你开始学习 – [An Overview of JavaScript Testing in 2018](https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2018-f68950900bc3)

- [ ] **Jest**
- [ ] **Mocha**
- [ ] **Protractor**
- [ ] **Karma**
- [ ] **Enzyme**

## Step 14 – 渐进式 WebApp

学习 Service Workers 以及如何创建渐进式 Webapp

## Step 15 – 静态类型检查工具

Static type checkers help you to add type checking to JavaScript. 你不需要去学习它们，但是他们确实能给你带来强大动力，并且只需要几个小时就能掌握。There is mainly TypeScript and Flow. 我喜欢 TypeScript，所以会选择它，当然欢迎你两个都试试然后再选择。

- [ ] **TypeScript (建议)**
- [ ] Flow

## Step 16 – 学习服务端渲染

There are different options, depending on what framework you are using

- [ ] React
  - [ ] Next.js
  - [ ] After.js
- [ ] Angular
  - [ ] Universal
- [ ] Vue.js
  - [ ] Nuxt.js

## Step 17 – 所有我们之前没提到的东西

Canvas、HTML-5 API、SVG、sourcemap、函数式编程 (functional programming)、TC39、渐进增强 (Progressive enhancement)、优雅降级 (graceful degradation) 等等。去弄清楚它们吧！

## 学无止境

旅程还没到此结束。仍然有很多的技能值得你去学习，你只需要保持对学习的渴望，并且永不止步。

祝你好运 👏



