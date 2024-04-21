## 项目说明

感受下`uniapp-x`的原生渲染能力以及开发体验，整体来说习惯`vue3+ts`组合的开发者可以快速上手；

**为什么要仿微信朋友圈？**

朋友圈中有长列表、键盘事件、沉浸式头部，图片布局，video相关操作，涉及的点比较多，在实现过程中可以学习和掌握此类需求的相关知识！

## 更新说明

### 1.0.2（2024-04-20）

- 修复安卓端运行报错、类型补全等
- 优化安卓端体验
- 新增九宫格图片尺寸动态计算
- 新增发表朋友圈页面图片尺寸动态计算

### 1.0.1（2024-04-19）

- 补全变量类型，修复安装打包、运行报错，🎉 支持安卓
- 优化代码结构
- 新增发布朋友圈页面
- 新增图片拖拽删除功能

### 1.0.0（2024-04-17）

- 高度还原微信朋友圈，ios上完美运行

## 待解决的问题

`如果大家有更好的方案，还请不吝赐教😁`

- touchstart 与 click 作用于同一个元素时，重复执行的问题
- textarea ios上键盘不支持换行 [查看uniapp-x文档](https://doc.dcloud.net.cn/uni-app-x/component/textarea.html)
- video相关事件逻辑暂未添加
- 发布朋友圈暂时只支持上传图片，视频未适配

## 预览图

<img src="https://img-cdn-tx.dcloud.net.cn/stream/plugin_screens/a7e92550-fc8d-11ee-829d-478a042f758e_0.png/webp?&v=1713339674" width="200" /> <img src="https://img-cdn-tx.dcloud.net.cn/stream/plugin_screens/a7e92550-fc8d-11ee-829d-478a042f758e_1.png/webp?&v=1713339675" width="200" /> <img src="https://img-cdn-tx.dcloud.net.cn/stream/plugin_screens/a7e92550-fc8d-11ee-829d-478a042f758e_2.png/webp?&v=1713527260" width="200" />

## ⚠️ 注意

video竖屏全屏退出后，视频出现黑屏为官方BUG，官方正在修复

[查看BUG修复进度](https://issues.dcloud.net.cn/pages/issues/detail?id=1491)  

---

## 微信/QQ：582639426！  

## [uniapp 插件市场下载](https://ext.dcloud.net.cn/plugin?id=17683)