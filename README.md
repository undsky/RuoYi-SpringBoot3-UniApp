<p align="center">
	<img alt="logo" src="https://oscimg.oschina.net/oscnet/up-d3d0a9303e11d522a06cd263f3079027715.png">
</p>
<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">RuoYi SpringBoot3 UniApp v1.2.0</h1>
<h4 align="center">基于 Vue3 + UniApp 的跨平台移动端快速开发框架</h4>
<p align="center">
	<a href="https://gitee.com/mc-springboot/RuoYi-SpringBoot3-UniApp/stargazers"><img src="https://gitee.com/mc-springboot/RuoYi-SpringBoot3-UniApp/badge/star.svg?theme=dark"></a>
	<a href="https://gitee.com/mc-springboot/RuoYi-SpringBoot3-UniApp"><img src="https://img.shields.io/badge/RuoYi%20UniApp-v1.2.0-brightgreen.svg"></a>
	<a href="https://gitee.com/mc-springboot/RuoYi-SpringBoot3-UniApp/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mashape/apistatus.svg"></a>
</p>

## 平台简介

RuoYi SpringBoot3 UniApp 是基于 [RuoYi-App](https://gitee.com/y_project/RuoYi-App/tree/vue3/) 的移动端解决方案，采用 Vue3 + UniApp 技术栈，实现一套代码多端运行（微信小程序、App、H5、Electron桌面端）。

本项目提供完整的移动端开发框架，包含登录认证、个人中心、工作台等常用功能模块，采用最新技术栈和最佳实践，帮助开发者快速构建跨平台移动应用。

## 联系方式

- 🌐 **官方网站**：https://www.undsky.com

## 相关项目

### 后端项目
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

### 2. 🎯 Cursor AI 智能开发

内置 Cursor Rules 开发规则，AI 辅助编码：

- **自动代码建议**：AI 按项目规范自动生成代码
- **代码质量审查**：实时检测代码问题并提供改进建议
- **最佳实践应用**：自动应用 Vue3 组合式 API 和简洁代码原则
- **智能注释**：生成有意义的代码注释
- **快速重构**：一键重构代码符合规范
- **团队协作**：统一的编码标准和规范
- **Context7 集成**：自动获取最新技术文档
- **开箱即用**：在 Cursor IDE 中打开即可使用

### 3. 🎨 Vue3 组合式 API

全面采用 Vue3 最新特性：

- **Composition API**：更灵活的代码组织方式
- **\<script setup\>**：更简洁的语法糖
- **响应式系统**：使用 ref、reactive 等最新 API
- **生命周期钩子**：使用 onLoad、onShow 等 UniApp 生命周期
- **状态管理**：Pinia 现代化状态管理方案
- **TypeScript 友好**：完善的类型支持（可选）

### 4. 📦 丰富的 UI 组件

集成 uni-ui 全家桶和其他优秀插件：

- **uni-ui**：官方 UI 组件库（50+ 组件）
- **z-paging**：终极列表分页、下拉刷新解决方案
- **mp-html**：富文本渲染组件，支持所有平台
- **自定义组件**：可复用的业务组件

### 5. 🔐 完整的认证体系

基于 Token 的认证机制：

- **JWT Token**：安全的身份认证
- **路由拦截**：页面跳转权限验证
- **白名单机制**：免登录页面配置
- **自动登录**：记住密码功能
- **密码加密**：RSA 加密传输
- **退出登录**：清除本地缓存

### 6. 🛠️ 开发工具集成

完善的开发工具链：

- **HBuilderX**：官方推荐的 IDE
- **条件编译**：针对不同平台的差异化处理
- **调试工具**：支持真机调试和模拟器调试
- **打包构建**：一键打包多端应用
- **热更新**：开发时实时预览

### 7. 📱 原生能力调用

封装常用的原生能力：

- **网络请求**：统一的 HTTP 请求封装
- **文件上传**：图片、文件上传功能
- **数据缓存**：本地存储管理
- **页面跳转**：统一的路由管理
- **消息提示**：Toast、Modal、Loading 等
- **分享功能**：社交分享能力

### 8. 🎯 最佳实践

遵循 UniApp 和 Vue3 最佳实践：

- **项目结构规范**：清晰的目录组织
- **代码风格统一**：使用 Prettier 格式化
- **性能优化**：按需加载、懒加载等
- **跨平台兼容**：使用条件编译处理差异
- **响应式布局**：适配不同尺寸屏幕

## 技术栈

### 核心框架

| 技术 | 版本 | 说明 |
|------|------|------|
| Vue | 3.x | 渐进式 JavaScript 框架 |
| UniApp | Latest | 跨平台应用开发框架 |
| Pinia | Latest | 新一代状态管理工具 |
| uni-ui | Latest | UniApp 官方 UI 组件库 |

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

## 平台支持

### 微信小程序

- AppID：`wxccd7e2a0911b3397`
- 配置文件：`manifest.json` → `mp-weixin`
- 适配特性：
  - 分包加载
  - ES6 转 ES5
  - 代码压缩优化
  - 启用 using-components

### H5 网页

- 开发端口：9090
- 路由模式：Hash
- 配置文件：`manifest.json` → `h5`
- 访问地址：http://localhost:9090

### App 应用

- 平台支持：Android、iOS
- 渲染引擎：uni-app
- 配置文件：`manifest.json` → `app-plus`
- 权限配置：完整的设备权限管理

### Electron 桌面端

- 入口文件：`electron/main.js`
- 渲染进程：基于 H5 构建
- 跨平台：Windows、macOS、Linux
- 配置：`package.json` → `uni-app.scripts.electron`

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

- **Node.js**：14.0+
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

**方式一：使用 HBuilderX（推荐）**

1. 使用 HBuilderX 打开项目
2. 在菜单栏选择"运行" → "运行到..."
3. 选择要运行的平台：
   - 运行到浏览器（H5）
   - 运行到小程序模拟器
   - 运行到手机或模拟器（App）

**方式二：使用 CLI（仅 H5）**

```bash
npm run dev:h5
```

访问 http://localhost:9090

### 打包发布

#### 微信小程序

1. HBuilderX 中选择"发行" → "小程序-微信"
2. 填写小程序名称和 AppID
3. 点击发行，生成小程序代码包
4. 使用微信开发者工具打开生成的代码包
5. 上传代码并提交审核

#### H5 网站

```bash
npm run build:h5
```

构建产物在 `unpackage/dist/build/h5` 目录。

#### App 应用

1. HBuilderX 中选择"发行" → "原生 App-云打包"
2. 选择打包平台（Android/iOS）
3. 配置证书、图标等信息
4. 点击打包，等待云端构建完成
5. 下载并安装生成的安装包

#### Electron 桌面应用

```bash
# 在 electron 目录下
cd electron
npm install
npm run build
```

## 项目结构

```
RuoYi-SpringBoot3-UniApp
├── api/                          # API 接口
│   ├── login.js                 # 登录接口
│   └── system/                  # 系统模块接口
│       ├── dict/                # 字典接口
│       └── user.js              # 用户接口
├── components/                   # 全局组件
│   └── uni-section/             # 区块组件
├── pages/                        # 页面目录
│   ├── index.vue                # 首页
│   ├── login.vue                # 登录页
│   ├── register.vue             # 注册页
│   ├── work/                    # 工作台模块
│   │   └── index.vue            # 工作台首页
│   ├── mine/                    # 个人中心模块
│   │   ├── index.vue            # 个人中心首页
│   │   ├── info/                # 个人信息
│   │   ├── avatar/              # 修改头像
│   │   ├── pwd/                 # 修改密码
│   │   ├── setting/             # 应用设置
│   │   ├── help/                # 常见问题
│   │   └── about/               # 关于我们
│   └── common/                  # 通用页面
│       ├── webview/             # 网页浏览
│       └── textview/            # 文本查看
├── plugins/                      # 插件封装
│   ├── auth.js                  # 权限插件
│   ├── modal.js                 # 消息提示插件
│   ├── tab.js                   # 标签页插件
│   └── index.js                 # 插件入口
├── static/                       # 静态资源
│   ├── images/                  # 图片资源
│   ├── font/                    # 字体图标
│   └── scss/                    # 样式文件
├── store/                        # 状态管理（Pinia）
│   ├── index.js                 # Store 入口
│   └── modules/                 # Store 模块
│       ├── user.js              # 用户模块
│       ├── dict.js              # 字典模块
│       └── settings.js          # 设置模块
├── uni_modules/                  # UniApp 插件市场插件
│   ├── uni-ui/                  # uni-ui 组件库
│   ├── z-paging/                # 分页插件
│   └── mp-html/                 # 富文本插件
├── utils/                        # 工具库
│   ├── request.js               # 请求封装
│   ├── auth.js                  # 认证工具
│   ├── dict.js                  # 字典工具
│   ├── storage.js               # 存储工具
│   └── ruoyi.js                 # 通用工具
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

## Cursor Rules 智能开发

项目内置 Cursor AI 开发规则，提升开发效率和代码质量。

### 规则配置

项目在 `.cursor/rules/` 目录下配置了以下规则文件：

| 规则文件 | 说明 | 应用范围 |
|---------|------|---------|
| `common.mdc` | 通用开发规则 | 全局应用 |
| `clean-code.mdc` | 简洁代码指南 | 所有代码文件 |
| `codequality.mdc` | 代码质量规范 | 所有代码文件 |
| `vue.mdc` | Vue 最佳实践 | Vue 文件 |
| `vue-3-composition-api.mdc` | Vue3 组合式 API 指南 | Vue 文件 |
| `vue-3-project-structure.mdc` | Vue3 项目结构规范 | 全局应用 |
| `uniapp-project-structure.mdc` | UniApp 项目结构规范 | 全局应用 |

### 使用方式

**自动应用**

在 Cursor IDE 中打开项目，规则会自动生效：

1. **智能代码建议**
   - AI 助手会遵循项目规范生成代码
   - 自动应用 Vue3 组合式 API 最佳实践

2. **代码审查**
   - AI 会根据规则检查代码质量
   - 提供符合规范的改进建议

3. **快速开发**
   - 使用 `Ctrl+K`（或 `Cmd+K`）唤起 AI 助手
   - 描述需求，AI 会按规则生成代码

**手动触发**

在 Cursor 中与 AI 对话时，提及规则名称：

```
请按照 vue-3-composition-api 规则实现用户列表页面
遵循 clean-code 规范优化这段代码
```

### 规则优势

| 优势 | 说明 |
|------|------|
| 🎯 **一致性** | 团队成员使用统一的编码规范 |
| ⚡ **效率** | AI 自动遵循最佳实践，减少返工 |
| 📚 **知识传承** | 新成员快速了解项目标准 |
| 🔍 **质量保障** | 代码审查自动化，减少低级错误 |
| 🚀 **快速上手** | 开箱即用的智能开发体验 |

## 常见问题

### 1. 如何切换后端接口地址？

修改 `config.js` 文件中的 `baseUrl`：

```javascript
export default {
  baseUrl: 'https://your-api-domain.com',
  // ...
}
```

### 2. 微信小程序无法访问接口？

需要配置服务器域名白名单：

1. 登录微信公众平台
2. 开发 → 开发设置 → 服务器域名
3. 添加你的后端接口域名

### 3. H5 跨域问题如何解决？

在 `manifest.json` 中配置代理：

```json
{
  "h5": {
    "devServer": {
      "proxy": {
        "/api": {
          "target": "http://localhost:8087",
          "changeOrigin": true
        }
      }
    }
  }
}
```

### 4. 如何添加新页面？

1. 在 `pages/` 目录下创建页面文件
2. 在 `pages.json` 中注册页面：

```json
{
  "pages": [
    {
      "path": "pages/your-page/index",
      "style": {
        "navigationBarTitleText": "页面标题"
      }
    }
  ]
}
```

### 5. 如何使用 uni-ui 组件？

直接在模板中使用，无需导入：

```vue
<template>
  <uni-list>
    <uni-list-item title="标题" />
  </uni-list>
</template>
```

### 6. 如何调试小程序？

1. HBuilderX 中运行到小程序模拟器
2. 微信开发者工具会自动打开
3. 使用开发者工具的调试功能

### 7. 如何自定义 TabBar？

在 `pages.json` 中配置：

```json
{
  "tabBar": {
    "color": "#000000",
    "selectedColor": "#007AFF",
    "list": [
      {
        "pagePath": "pages/index",
        "iconPath": "static/images/home.png",
        "selectedIconPath": "static/images/home_.png",
        "text": "首页"
      }
    ]
  }
}
```

### 8. 如何处理不同平台的差异？

使用条件编译：

```vue
<!-- #ifdef H5 -->
<view>H5 端显示</view>
<!-- #endif -->

<!-- #ifdef MP-WEIXIN -->
<view>小程序端显示</view>
<!-- #endif -->
```

### 9. 如何实现下拉刷新？

使用 z-paging 组件自动处理，或使用 UniApp 内置方法：

```vue
<script setup>
import { onPullDownRefresh } from '@dcloudio/uni-app'

onPullDownRefresh(() => {
  // 刷新数据
  loadData().then(() => {
    uni.stopPullDownRefresh()
  })
})
</script>
```

### 10. 如何上传图片？

```javascript
uni.chooseImage({
  count: 1,
  success: (res) => {
    uni.uploadFile({
      url: 'http://your-api/upload',
      filePath: res.tempFilePaths[0],
      name: 'file',
      success: (uploadRes) => {
        console.log('上传成功', uploadRes)
      }
    })
  }
})
```

## 平台兼容性说明

### 各平台特性支持

| 特性 | H5 | 小程序 | App | 说明 |
|------|----|----|-----|------|
| 网络请求 | ✅ | ✅ | ✅ | 完全支持 |
| 文件上传 | ✅ | ✅ | ✅ | 完全支持 |
| 本地存储 | ✅ | ✅ | ✅ | 完全支持 |
| 定位 | ✅ | ✅ | ✅ | 需要权限 |
| 相机 | ⚠️ | ✅ | ✅ | H5 部分浏览器支持 |
| 扫码 | ❌ | ✅ | ✅ | H5 不支持 |
| 支付 | ⚠️ | ✅ | ✅ | 需要对接支付平台 |
| 分享 | ⚠️ | ✅ | ✅ | H5 需要浏览器支持 |

### 尺寸单位说明

- **rpx**：响应式单位，750rpx = 屏幕宽度
- **px**：固定像素单位
- **upx**：UniApp 推荐使用 rpx

## 性能优化建议

### 1. 图片优化

- 使用合适的图片格式（WebP 优先）
- 压缩图片大小
- 使用懒加载

### 2. 分包加载

大型应用建议使用分包：

```json
{
  "subPackages": [
    {
      "root": "pages/module1",
      "pages": [
        { "path": "page1/index" }
      ]
    }
  ]
}
```

### 3. 减少 setData

小程序中尽量减少 setData 的调用频率和数据量。

### 4. 使用组件缓存

合理使用 keep-alive 和组件缓存。

### 5. 避免过度渲染

使用 v-show 替代频繁切换的 v-if。

## 部署说明

### H5 部署

1. 构建生产版本：
```bash
npm run build:h5
```

2. 部署 `unpackage/dist/build/h5` 目录到服务器

3. 配置 Nginx：
```nginx
server {
    listen 80;
    server_name your-domain.com;
    
    location / {
        root /path/to/h5;
        try_files $uri $uri/ /index.html;
    }
}
```

### 小程序部署

1. HBuilderX 发行小程序
2. 微信开发者工具上传代码
3. 微信公众平台提交审核
4. 审核通过后发布

### App 部署

1. HBuilderX 云打包
2. 下载安装包
3. 上传到应用商店

## 更新日志

### v1.2.0 (2024-XX-XX)

- ✨ 新增 Cursor Rules 智能开发规则
- ✨ 升级到 Vue3 组合式 API
- ✨ 集成 Pinia 状态管理
- ✨ 集成 z-paging 分页组件
- ✨ 集成 mp-html 富文本组件
- 🐛 修复已知问题
- 📝 完善文档说明

### v1.0.0 (2024-XX-XX)

- 🎉 项目初始化
- ✨ 实现基础功能模块
- ✨ 支持多端运行

## 开源协议

本项目遵循 [ISC 协议](LICENSE) 开源。

## 参与贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request

## 技术支持

- **官方文档**：http://doc.ruoyi.vip
- **UniApp 文档**：https://uniapp.dcloud.net.cn/
- **Gitee**：https://gitee.com/mc-springboot/RuoYi-SpringBoot3-UniApp
- **后端项目**：https://gitee.com/y_project/RuoYi-App/tree/vue3/

## 鸣谢

- [RuoYi-App](https://gitee.com/y_project/RuoYi-App/tree/vue3/)：后端管理框架
- [UniApp](https://uniapp.dcloud.net.cn/)：跨平台框架
- [uni-ui](https://uniapp.dcloud.net.cn/component/uniui/uni-ui.html)：UI 组件库
- [z-paging](https://z-paging.zxlee.cn/)：分页组件
- [mp-html](https://jin-yufeng.github.io/mp-html/)：富文本组件

---

⭐ 如果觉得项目不错，请点个 Star 支持一下！

