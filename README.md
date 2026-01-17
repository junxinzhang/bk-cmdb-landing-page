# 蓝鲸CMDB深度定制 - 落地页

> 引用文章内容，展示蓝鲸CMDB精细化权限与用户管理定制方案。

![页面预览](assets/screenshot.png)

## 📋 项目简介

这是一个静态网站落地页，用于展示蓝鲸CMDB深度定制方案的核心能力与技术实现。

### 核心特性

- 🎨 现代化响应式设计
- 🚀 轻量级静态网站（无需后端）
- 📱 完美支持移动端
- ♿ 符合无障碍访问标准
- 🔍 SEO 友好（Schema.org 结构化数据）
- 🎬 图片轮播展示
- 📊 滚动动画效果（AOS）

## 🛠️ 技术栈

- **前端框架**: 纯 HTML5 + CSS3 + JavaScript
- **CSS 框架**: Tailwind CSS (CDN)
- **图标库**: Remix Icon
- **动画库**: AOS (Animate On Scroll)
- **部署**: GitHub Pages

## 🚀 快速开始

### 本地预览

1. 克隆项目
```bash
git clone https://github.com/junxinzhang/bk-cmdb-landing-page.git
cd bk-cmdb-landing-page
```

2. 启动本地服务器（任选其一）

**使用 Python**:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**使用 Node.js**:
```bash
npx http-server -p 8000
```

3. 在浏览器打开 `http://localhost:8000`

### 部署到 GitHub Pages

#### 方法一：通过仓库设置启用（推荐）

1. 推送代码到 GitHub 仓库
```bash
git add .
git commit -m "Update: Add carousel and GitHub Pages workflows"
git push origin main
```

2. 在 GitHub 仓库中：
   - 进入 **Settings** → **Pages**
   - **Source** 选择 `GitHub Actions`
   - Workflows 会自动触发部署

3. 部署完成后，访问：
   ```
   https://YOUR_USERNAME.github.io/bk-cmdb-landing-page/
   ```

#### 方法二：手动触发 Workflow

在 GitHub 仓库的 **Actions** 标签页，选择对应的 workflow 并点击 **Run workflow** 手动触发。

## 🎨 自定义配置

### 修改联系方式

编辑 `index.html`，搜索以下部分并修改：

```html
<!-- 联系区域 -->
<a href="mailto:jason2023zhang@gmail.com">邮件咨询</a>

<!-- Footer -->
<a href="https://github.com/junxinzhang">GitHub</a>
<a href="https://junxinzhang.com">博客</a>
```

### 替换截图

将新的截图文件放置在 `assets/` 目录下：
- `screenshot.png`（轮播图1）
- `screenshot01.png`（轮播图2）

## 🎬 功能特性

### 图片轮播

- ✅ 自动播放（5秒切换）
- ✅ 左右箭头按钮
- ✅ 底部指示器
- ✅ 键盘方向键导航
- ✅ 触摸滑动支持
- ✅ 鼠标悬停暂停

### 响应式设计

- ✅ 移动端汉堡菜单
- ✅ 自适应布局
- ✅ 触摸友好交互

## 📄 参考来源

- **案例文章**: https://junxinzhang.com/bk-cmdb/
- **定制仓库**: https://github.com/junxinzhang/bk-cmdb
- **原厂仓库**: https://github.com/TencentBlueKing/bk-cmdb

## 👨‍💻 作者

**Jason Zhang**

- 📧 Email: jason2023zhang@gmail.com
- 🐦 Twitter/X: [@Jasonz9788](https://x.com/Jasonz9788)
- 🌐 Blog: [https://junxinzhang.com](https://junxinzhang.com)
- 💬 微信: winnielove2020

---

⭐ 如果这个项目对你有帮助，欢迎 Star！
