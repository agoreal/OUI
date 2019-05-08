#OUI 
<small>v0.0.1</small>
---
[TOC]
---
##0. Intro 介绍
觅诚前端团队自己的 CSS 框架。
根据团队的设计风格，AUI 等 CSS 框架并不能完全满足团队开发需要。为了提高开发效率，封装了常用的样式。
切图标准为将 UI 宽度为 750px 的 psd 文件改为宽度为 2000px，引入 PxCook 进行量图。转换公式为 ***100px = 1 rem***
**注**：*暂需引入 aui.css ，本框架暂时只做日常开发需要的简单补充，以后将逐步放弃 AUI。*
##1. Container 容器
##2. Layout 布局
####2.1 弹性盒子
`.flex`
##3. Typography 字体
####3.1 字号
- `.font-s` 小号字体: 0.64rem;
- `.font-m` 中号字体: 0.80rem;
- `.font-l` 大号字体: 0.96rem;
####3.2 字宽
- `.font-bold` 字体加粗
####3.3 字体颜色
- `.font-white` 白色字体： #fff;
- `.font-black` 黑色字体： #000;
- `.font-grey`  灰色字体： #ccc;
##4 Button 按钮
    由于我在当前的项目中的按钮都不太常见，所以还未封装一些标准常见的按钮样式。
- `.span-btn`（暂时）
##5 Br 分割线
- `.br`（暂时）高度为 0.54rem 的灰色分割线。
##6 Backgroud Color 背景颜色
-`.bg-blue` <table><tr><td bgcolor=#00b4ff>#00b4ff</td></tr></table>
-`.bg-red`  <table><tr><td bgcolor=#ff5c5c>#ff5c5c</td></tr></table>
-`.bg-green` <table><tr><td bgcolor=#09ca7b>#09ca7b</td></tr></table>
-`bg-white` <table><tr><td bgcolor=#ffffff>#ffffff</td></tr></table>