<p align="center">
	<img alt="logo" src="https://oscimg.oschina.net/oscnet/up-d3d0a9303e11d522a06cd263f3079027715.png">
</p>
<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">RuoYi SpringBoot3 UniApp v1.2.0</h1>
<h4 align="center">基于 Vue3 + UniApp 的跨平台移动端快速开发框架</h4>


## 平台简介

RuoYi SpringBoot3 UniApp 是基于 [RuoYi-App](https://gitee.com/y_project/RuoYi-App/tree/vue3/) 的移动端解决方案，采用 Vue3 + UniApp 技术栈，实现一套代码多端运行（微信小程序、App、H5、Electron桌面端）。

本项目提供完整的移动端开发框架，包含登录认证、个人中心、工作台等常用功能模块，采用最新技术栈和最佳实践，帮助开发者快速构建跨平台移动应用。


![公众号](https://cdn.undsky.com/img/ghss.png)
 > 关注公众号，聚焦 AI 应用落地与开发经验分享


## 📑 目录

- [平台简介](#平台简介)
- [后端项目](#后端项目)
- [核心特性](#核心特性)
- [技术栈](#技术栈)
- [内置功能](#内置功能)
- [快速开始](#快速开始)
- [项目结构](#项目结构)
- [使用说明](#使用说明)
- [开源协议](#开源协议)
- [参与贡献](#参与贡献)
- [鸣谢](#鸣谢)
- [联系方式](#联系方式)

##  后端项目
- 💻 https://github.com/undsky/RuoYi-SpringBoot3-Pro

## ✨ 核心特性

### 1. 🌐 跨平台支持

一套代码，多端运行：

| 平台 | 支持状态 | 说明 |
|------|---------|------|
| **微信小程序** | ✅ 完全支持 | 适配微信小程序环境 |
| **H5** | ✅ 完全支持 | 支持浏览器访问 |
| **Android App** | ✅ 完全支持 | 原生 Android 应用 |
| **iOS App** | ✅ 完全支持 | 原生 iOS 应用 |
| **Electron** | ✅ 实验支持 | 跨平台桌面应用 |

### 2.  Vue3 组合式 API

全面采用 Vue3 最新特性：

- **Composition API**：更灵活的代码组织方式
- **\<script setup\>**：更简洁的语法糖
- **响应式系统**：使用 ref、reactive 等最新 API
- **生命周期钩子**：使用 onLoad、onShow 等 UniApp 生命周期
- **状态管理**：Pinia 现代化状态管理方案
- **TypeScript 友好**：完善的类型支持（可选）

### 3. 📦 丰富的 UI 组件

集成 uni-ui 全家桶和其他优秀插件：

- **uni-ui**：官方 UI 组件库（50+ 组件）
- **z-paging**：终极列表分页、下拉刷新解决方案
- **mp-html**：富文本渲染组件，支持所有平台
- **自定义组件**：可复用的业务组件

### 4. 🔐 完整的认证体系

基于 Token 的认证机制：

- **JWT Token**：安全的身份认证
- **路由拦截**：页面跳转权限验证
- **白名单机制**：免登录页面配置
- **自动登录**：记住密码功能
- **密码加密**：RSA 加密传输
- **退出登录**：清除本地缓存

### 5. 🛠️ 开发工具集成

完善的开发工具链：

- **HBuilderX**：官方推荐的 IDE
- **条件编译**：针对不同平台的差异化处理
- **调试工具**：支持真机调试和模拟器调试
- **打包构建**：一键打包多端应用
- **热更新**：开发时实时预览

### 6. 📱 原生能力调用

封装常用的原生能力：

- **网络请求**：统一的 HTTP 请求封装
- **文件上传**：图片、文件上传功能
- **数据缓存**：本地存储管理
- **页面跳转**：统一的路由管理
- **消息提示**：Toast、Modal、Loading 等
- **分享功能**：社交分享能力

### 7. 🎯 最佳实践

遵循 UniApp 和 Vue3 最佳实践：

- **项目结构规范**：清晰的目录组织
- **代码风格统一**：使用 Prettier 格式化
- **性能优化**：按需加载、懒加载等
- **跨平台兼容**：使用条件编译处理差异
- **响应式布局**：适配不同尺寸屏幕

### 8. 🖥️ Electron 桌面支持

将 UniApp H5 打包为跨平台桌面应用：

- **跨平台桌面应用**：支持 Windows、macOS、Linux
- **原生窗口体验**：使用 Electron 提供原生窗口和菜单
- **开发调试**：开发环境加载本地服务（http://localhost:5173）
- **生产打包**：生产环境加载打包后的 H5 文件
- **Node.js 集成**：支持调用 Node.js 原生能力
- **开发工具**：内置开发者工具，方便调试
- **快速启动**：`npm run dev` 开发，`npm run prod` 生产

**使用步骤**
1. 构建 H5：在项目根目录运行 `npm run build:h5`
2. 进入 electron 目录：`cd electron`
3. 安装依赖：`npm install`
4. 运行桌面应用：`npm run prod`

## 技术栈

### 核心框架

| 技术 | 版本 | 说明 |
|------|------|------|
| Vue | 3.x | 渐进式 JavaScript 框架 |
| UniApp | Latest | 跨平台应用开发框架 |
| Pinia | Latest | 新一代状态管理工具 |
| uni-ui | Latest | UniApp 官方 UI 组件库 |
| Electron | 27.1.0 | 跨平台桌面应用框架 |

### 主要插件

| 插件 | 说明 | 文档 |
|------|------|------|
| **z-paging** | 列表分页、下拉刷新 | [文档](https://z-paging.zxlee.cn/) |
| **mp-html** | 富文本渲染 | [文档](https://jin-yufeng.github.io/mp-html/) |
| **jsencrypt** | RSA 加密 | [文档](https://www.npmjs.com/package/jsencrypt) |

### 工具库

- **uni-icons**：图标库
- **uni-forms**：表单组件
- **uni-list**：列表组件
- **uni-popup**：弹窗组件
- **uni-calendar**：日历组件

## 内置功能

### 基础功能

1. ✅ **用户登录**：账号密码登录、记住密码、自动登录
2. ✅ **用户注册**：新用户注册功能
3. ✅ **忘记密码**：密码找回流程
4. ✅ **路由守卫**：页面跳转权限验证拦截
5. ✅ **Token 管理**：自动管理 Token 失效和刷新

### 个人中心

6. ✅ **个人信息**：查看和编辑个人资料
7. ✅ **修改头像**：拍照或从相册选择头像
8. ✅ **修改密码**：在线修改登录密码
9. ✅ **应用设置**：清除缓存、关于我们等
10. ✅ **常见问题**：帮助文档
11. ✅ **关于我们**：应用信息展示

### 工作台

12. ✅ **工作台首页**：待办事项、快捷入口
13. ✅ **数据字典**：系统字典数据管理

### 通用功能

14. ✅ **网页浏览**：内置 WebView 浏览器
15. ✅ **文本查看**：富文本内容展示
16. ✅ **底部导航**：首页、工作台、我的三个 Tab

## 快速开始

### 环境要求

- **Node.js**：20+
- **HBuilderX**：最新版本（推荐）
- **开发工具**：
  - 微信开发者工具（开发小程序）
  - Android Studio（开发 Android App）
  - Xcode（开发 iOS App，仅 macOS）

### 安装步骤

#### 1. 克隆项目

```bash
git clone https://gitee.com/mc-springboot/RuoYi-SpringBoot3-UniApp.git
cd RuoYi-SpringBoot3-UniApp
```

#### 2. 安装依赖

```bash
npm install
```

#### 3. 配置后端地址

编辑 `config.js` 文件，修改 `baseUrl`：

```javascript
export default {
  baseUrl: 'http://localhost:8087',  // 修改为你的后端地址
  // ...
}
```

#### 4. 运行项目

1. 使用 HBuilderX 打开项目
2. 在菜单栏选择"运行" → "运行到..."
3. 选择要运行的平台：
   - 运行到浏览器（H5）
   - 运行到小程序模拟器
   - 运行到手机或模拟器（App）


## 项目结构

```
RuoYi-SpringBoot3-UniApp
├── api/                          # API 接口
│   ├── login.js                 # 登录接口
│   └── system/                  # 系统模块接口
├── components/                   # 全局组件
├── electron/                     # Electron 桌面应用
│   ├── main.js                  # 主进程入口
│   ├── preload.js               # 预加载脚本
│   ├── package.json             # Electron 配置
│   └── README.md                # 使用说明
├── pages/                        # 页面目录
│   ├── index.vue                # 首页
│   ├── login.vue                # 登录页
│   ├── register.vue             # 注册页
│   ├── work/                    # 工作台模块
│   ├── mine/                    # 个人中心模块
│   └── common/                  # 通用页面
├── plugins/                      # 插件封装
│   ├── auth.js                  # 权限插件
│   ├── modal.js                 # 消息提示插件
│   └── tab.js                   # 标签页插件
├── static/                       # 静态资源
│   ├── images/                  # 图片资源
│   └── font/                    # 字体图标
├── store/                        # 状态管理（Pinia）
│   ├── index.js                 # Store 入口
│   └── modules/                 # Store 模块
├── uni_modules/                  # UniApp 插件
│   ├── uni-ui/                  # uni-ui 组件库
│   ├── z-paging/                # 分页插件
│   └── mp-html/                 # 富文本插件
├── utils/                        # 工具库
│   ├── request.js               # 请求封装
│   ├── auth.js                  # 认证工具
│   └── storage.js               # 存储工具
├── App.vue                       # 应用入口组件
├── main.js                       # 应用入口文件
├── pages.json                    # 页面路由配置
├── manifest.json                 # 应用配置
├── uni.scss                      # 全局样式变量
├── config.js                     # 全局配置
├── permission.js                 # 路由守卫
└── package.json                  # 依赖配置
```

## 使用说明

### 路由守卫配置

在 `permission.js` 中配置路由拦截：

```javascript
// 登录页面
const loginPage = "/pages/login"

// 页面白名单（无需登录即可访问）
const whiteList = [
  '/pages/login', 
  '/pages/register', 
  '/pages/common/webview/index'
]
```

### API 接口调用

使用封装的 `request` 工具：

```javascript
import request from '@/utils/request'

// GET 请求
export function getUser() {
  return request({
    url: '/system/user/profile',
    method: 'get'
  })
}

// POST 请求
export function updateUser(data) {
  return request({
    url: '/system/user/profile',
    method: 'put',
    data: data
  })
}
```

### 状态管理（Pinia）

```javascript
import { defineStore } from 'pinia'

export const useUserStore = defineStore('user', {
  state: () => ({
    token: '',
    userInfo: {}
  }),
  actions: {
    setToken(token) {
      this.token = token
    },
    setUserInfo(info) {
      this.userInfo = info
    }
  }
})
```

在组件中使用：

```vue
<script setup>
import { useUserStore } from '@/store/modules/user'

const userStore = useUserStore()

// 获取数据
console.log(userStore.token)

// 修改数据
userStore.setToken('new-token')
</script>
```

### 数据字典使用

```vue
<script setup>
import { useDict } from '@/utils/dict'
import { getCurrentInstance } from 'vue'

const { proxy } = getCurrentInstance()

// 加载字典
const { sys_user_sex } = proxy.useDict('sys_user_sex')

// 在模板中使用
</script>

<template>
  <view v-for="item in sys_user_sex" :key="item.value">
    {{ item.label }}
  </view>
</template>
```

### 条件编译

针对不同平台的差异化处理：

```vue
<template>
  <!-- 仅在 H5 显示 -->
  <!-- #ifdef H5 -->
  <view>这是 H5 端的内容</view>
  <!-- #endif -->

  <!-- 仅在微信小程序显示 -->
  <!-- #ifdef MP-WEIXIN -->
  <view>这是微信小程序的内容</view>
  <!-- #endif -->

  <!-- 仅在 App 显示 -->
  <!-- #ifdef APP-PLUS -->
  <view>这是 App 的内容</view>
  <!-- #endif -->
</template>

<script>
// JavaScript 条件编译
// #ifdef H5
console.log('H5 平台')
// #endif

// #ifdef MP-WEIXIN
console.log('微信小程序平台')
// #endif
</script>

<style>
/* 样式条件编译 */
/* #ifdef H5 */
.title { font-size: 32rpx; }
/* #endif */

/* #ifdef MP-WEIXIN */
.title { font-size: 28rpx; }
/* #endif */
</style>
```

### 列表页面开发

使用 z-paging 组件：

```vue
<template>
  <z-paging 
    ref="paging" 
    v-model="dataList" 
    @query="queryList"
  >
    <view v-for="item in dataList" :key="item.id">
      {{ item.name }}
    </view>
  </z-paging>
</template>

<script setup>
import { ref } from 'vue'
import { getUserList } from '@/api/system/user'

const paging = ref(null)
const dataList = ref([])

// 查询列表
const queryList = (pageNo, pageSize) => {
  getUserList({ pageNo, pageSize }).then(res => {
    paging.value.complete(res.rows)
  })
}
</script>
```

### 富文本显示

使用 mp-html 组件：

```vue
<template>
  <mp-html :content="htmlContent" />
</template>

<script setup>
import { ref } from 'vue'

const htmlContent = ref('<p>这是富文本内容</p>')
</script>
```

## 开源协议

本项目遵循 [ISC 协议](LICENSE) 开源。

## 参与贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


## 鸣谢

- [RuoYi-App](https://gitee.com/y_project/RuoYi-App/tree/vue3/)：后端管理框架
- [UniApp](https://uniapp.dcloud.net.cn/)：跨平台框架
- [uni-ui](https://uniapp.dcloud.net.cn/component/uniui/uni-ui.html)：UI 组件库
- [z-paging](https://z-paging.zxlee.cn/)：分页组件
- [mp-html](https://jin-yufeng.github.io/mp-html/)：富文本组件

## 📞 联系方式

- 网站：[https://www.undsky.com](https://www.undsky.com)
- GitHub：[https://github.com/undsky/RuoYi-SpringBoot3-UniApp](https://github.com/undsky/RuoYi-SpringBoot3-UniApp)
- Issues：[https://github.com/undsky/RuoYi-SpringBoot3-UniApp/issues](https://github.com/undsky/RuoYi-SpringBoot3-UniApp/issues)

---



⭐ 如果觉得项目不错，请点个 Star 支持一下！

