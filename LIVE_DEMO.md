# CivilDoc AI Live Demo 指南

[![部署到 Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyourusername%2Fcivildoc-ai)
[![在 Netlify 上部署](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/civildoc-ai)

## 立即获取您自己的 Live Demo

通过以下两种简单方法之一，您可以在不到 2 分钟的时间内创建自己的 CivilDoc AI 网站演示：

### 方法 1: 一键部署（无需下载代码）

1. 点击上方的"部署到 Vercel"或"在 Netlify 上部署"按钮
2. 按照平台提示完成部署流程
3. 部署完成后，您将获得一个可公开访问的网址

### 方法 2: 使用 Deploy 页面（本地项目）

如果您已经下载了项目代码，可以：

1. 在浏览器中打开项目中的 `public/deploy.html` 文件
2. 点击页面上的"Deploy to Vercel"按钮
3. 按照指示完成部署

## 在本地预览 Demo

如果您想在部署前在本地预览：

1. 确保已安装 Node.js
2. 在项目目录中运行：
   ```
   npm install
   npm run dev
   ```
3. 在浏览器中访问 `http://localhost:3000`

## Demo 功能

CivilDoc AI 演示版包含以下功能：

- 文档管理界面（创建、查看和编辑文档）
- AI 代理任务面板（启动自动化任务）
- 设置和配置页面
- 响应式设计（适用于桌面和移动设备）

## 自定义您的 Demo

部署后，您可以通过以下方式自定义您的 demo：

1. 修改 `public/mock-data.json` 文件中的示例数据
2. 更新 `public/logo.svg` 以使用您自己的品牌
3. 在您的托管平台的环境变量中添加自定义设置

## 获取帮助

如果您在部署过程中遇到任何问题，请参阅：

- [Vercel 部署文档](https://vercel.com/docs/concepts/deployments/overview)
- [Netlify 部署文档](https://docs.netlify.com/site-deploys/overview/) 