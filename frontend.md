> 路线图的文本清单形式，欢迎 fork 并用来跟踪你的学习进度

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

尽管我说了很多遍，但是我还是要再强调一次「实践出真知」。如果你不勤加练习的话，你会有一种似乎已经学会了它的感觉，但是很快你就会把它忘了。在你按照这个路线图学习时，尽可能地让自己多进行练习。

做一些响应式的页面，并使用 JavaScript 进行一些交互。你可以临摹 (copy) 任何已有的你感兴趣的网页，但是 **记得用上你现在已经学到的所有知识**。

## Step 3 – 可选但是高度推荐

如果你没有学习过 [git](https://git-scm.com/)，在你进一步学习之前，我建议你先去了解一下它。它确实能帮助你进一步地学习。你不需要学习它的所有东西，你只需要先学习下面列出的东西（译注：然而作者并没有列出来，那么我先暂时在这里钦定下 [这篇文章](http://blog.gogojimmy.net/2012/01/17/how-to-use-git-1-git-basic/)），然后在你遇到任何问题时再继续学习。

是时候进行一些实战啦！打开 [Github](https://github.com)，搜索一些项目，然后给开源项目开一些 pull request。下面是一些关于 pull request 的建议：
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

预处理器能让你在 CSS 之上添加更强大的功能，让你做一些 CSS 不能做到的事。有诸如 Sass、Less、Stylus 等方案供你选择。如果让我来选择的话，我会选择 Sass。然而，PostCSS 最近获得了很多关注，它可以说是锦上添花 (nice-to-have)，可以说是 CSS 的“Babel”。你可以独立地使用它，也可以在 Sass 之上使用它。我建议你先学习 Sass，之后有时间再去了解下 PostCSS。

- [ ] 选择其中一个
  - [ ] **Sass (建议)**
  - [ ] Less
  - [ ] **PostCSS (之后再学习这个)**
  - [ ] Stylus

## Step 6 – 学习 CSS 框架

这部分之前在图表中是在稍前的位置的，但是我把它移到了下面，因为它们确实不再那么需要了，你可以毫不费力地掌握它们。如果你想要挑一个，那就从你找到的框架中随便选一个吧 (there is one under every rock)。我比较喜欢的并且经常使用的包括 Bootstrap、Materialize 和 Bulma。但是如果更看重它们在市场上的需求，假设我是刚开始学习的话，我会选择 Bootstrap。

- [ ] **Bootstrap (建议)**
- [ ] Materialize CSS
- [ ] Bulma

## Step 7 – 学习如何组织 CSS

随着你的应用的内容组建变得丰富，CSS 开始变得混乱和难以维护。有很多种方案可以让你的 CSS 的结构变得更好

- [ ] **BEM – 建议**
- [ ] OOCSS
- [ ] SMACSS
- [ ] SUITCSS
- [ ] Atomic

## Step 8 – 学习构建工具

这些工具能帮助你捆绑合并、构建和开发你的前端应用。

曾经有很多任务执行工具，但是现在我会选择使用 NPM scripts，当然如果你想要去选择其他的，参考一下 gulp

- [ ] **NPM Scripts (建议)**
- [ ] Gulp

另外还有一些代码风格检测工具，我会选择 ESLint。感兴趣的话你也可以看看别的，然后了解为什么这个会更好 (and see why one over the other)

- [ ] **ESLint (建议)**
- [ ] JSLint
- [ ] JSHint
- [ ] JSCS

**开发应用时用 Webpack，开发库时用 Rollup**。当然，你现在还不需要 rollup；它能做的事，webpack 也可以做，所以先用用 Webpack，然后之后再深入了解 Rollup

- [ ] **Webpack (建议)**
- [ ] Rollup
- [ ] Parcel

## Step 9 – 做些东西 – 比如一个库

打开 Github，然后看看大家做的那些库的源代码，选择一个点子然后做一些包含以下要求的库

- [ ] 它使用了 Sass 来编写样式
- [ ] 它使用了 ES6 编写
- [ ] 它是一个 UMD 库
- [ ] 它使用了 Babel 来让更老的浏览器运行

## Step 10 – 学习一个框架

谈到框架，你同样有多种选择。但是我会推荐下面列出来的这些框架。你可以随便选择其中一个，不过如果你想问我个人选择的话，我会选择 React 或者 Angular。当然把它们都试试看吧，然后看看你会喜欢什么

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

当你做完了第 9 步的应用时，学习如何 **管理和提升你的应用的性能**。比如 **可交互时间 (Interactivity Time)**、**页面速度指标 (Page Speed Index)**、**Lighthouse 评分 (Lighthouse Score)** 等。

## Step 13 – 测试你的应用

现在有越来越多的针对 *不同需求* 的测试工具。我自己大多结合 Jest、Mocha、Karma 和 Enzyme 使用。然而，在你学习他们之前，建议你 **先去理解不同的测试类型**，尝试所有的测试工具，然后选择最适合你需要的那些工具。

这里有一份很好的总结帮助你开始学习 – [An Overview of JavaScript Testing in 2018](https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2018-f68950900bc3)

- [ ] **Jest**
- [ ] **Mocha**
- [ ] **Protractor**
- [ ] **Karma**
- [ ] **Enzyme**

## Step 14 – 渐进式 WebApp

学习 Service Workers 以及如何创建渐进式 Webapp

## Step 15 – 静态类型检查工具

静态类型检查工具帮助你在 JavaScript 中引入类型检查。你不需要去学习它们，但是他们确实能给你带来强大动力，并且只需要几个小时就能掌握。它们主要有 TypeScript 和 Flow。我喜欢 TypeScript，所以我会选择它，当然欢迎你两个都试试然后再选择。

- [ ] **TypeScript (建议)**
- [ ] Flow

## Step 16 – 学习服务端渲染

同样有几种方案，这取决你使用的是什么框架

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



