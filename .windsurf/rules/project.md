---
trigger: always_on
description: 项目规则
globs:
---

# 项目概述



# 页面开发

- 页面统一存放在 `pages/` 目录下，按照 `pages/**/index.vue` 目录结构生成
- 每个页面都要在 `pages.json` 中配置
- 尽可能复用 `uni_modules` 和 `components` 中的组件
- 尽可能复用 `uni.scss` 中的样式

### 列表页面

- 包含下拉刷新 (onPullDownRefresh) 和上拉加载更多 (onReachBottom) 的逻辑
- 在数据加载时显示一个 loading 状态
- 如果列表为空，显示一个“暂无数据”的提示

#### 简单列表

- 使用 `uni-list` 和 `uni-list-item` 组件来渲染列表

#### 复杂列表

- 使用 uni_modules/z-paging 插件实现
- 充分阅读[z-paging 文档](https://z-paging.zxlee.cn/) 


### 表单页面

- 使用 `uni-forms` 组件来实现

# 跨平台兼容性

- 项目需要同时运行在微信小程序、App 和 H5 端
- 使用条件编译 `#ifdef` 或 `#ifndef` 加 `%PLATFORM%` 开头，以 `#endif` 结尾方式来处理不同平台兼容性
- 注意不同平台的样式差异