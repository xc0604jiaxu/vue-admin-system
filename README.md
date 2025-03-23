
# Vue 后台管理系统

这是一个基于 Vue.js 开发的后台管理系统，使用 Element UI 组件库构建界面，实现了用户管理、数据可视化等功能。

## 环境要求

- **Node.js**: 10.x - 14.x (推荐使用 Node.js 12.x，由于项目使用了 node-sass 4.12.0，不建议使用 Node.js 15+ 版本)
- **npm**: 6.x+

## 账号信息

**管理员账号**：
username: admin
password: 123456

**普通账号**：
username: test
password: 123456

## 项目功能

- **登录/登出功能**：基于 token 的用户认证系统
- **首页数据展示**：展示订单数据、用户数据等统计信息
- **数据可视化**：使用 ECharts 实现折线图、柱状图、饼图等多种数据可视化展示
- **用户管理**：实现用户的增删改查功能
- **视频管理**：视频资源的管理功能
- **权限管理**：不同角色用户的权限控制
- **动态菜单**：根据用户权限动态生成侧边栏菜单
- **页面标签**：多标签页切换功能

## 技术栈

- **前端框架**：Vue.js 2.x
- **UI 组件库**：Element UI
- **状态管理**：Vuex
- **路由管理**：Vue Router
- **HTTP 请求**：Axios
- **数据模拟**：Mock.js
- **图表库**：ECharts

## 项目结构

```
src/
├── api/          # API 请求配置
├── assets/       # 静态资源
├── components/   # 公共组件
├── mock/         # 模拟数据
├── router/       # 路由配置
├── store/        # Vuex 状态管理
├── views/        # 页面组件
└── main.js       # 入口文件
```

## 项目运行

### 安装依赖
```
npm install
```

### 运行项目
```
npm run serve
```

### 打包项目
```
npm run build
```

### 格式化项目
```
npm run lint
```
### 项目说明

本项目为个人学习Vue.js框架而开发的练手项目，旨在熟悉Vue全家桶（Vue.js、Vuex、Vue Router）的使用以及Element UI组件库的应用。通过开发这个后台管理系统，加深了对前端工程化、组件化开发的理解。

