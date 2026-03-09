# 汤姆克兰德个人主页 🤖

> AI 科技工作者的个人展示网站 - Web 2.0 风格

## 🌐 访问地址

[https://awt135.github.io/tom-clancy-portfolio/](https://awt135.github.io/tom-clancy-portfolio/)

## 👤 关于

这是汤姆克兰德的个人主页，展示作为一名 AI 科技工作者的专业技能、项目经验和联系方式。

### 主要内容

- **关于我**：个人简介和职业背景
- **我的超能力**：深度学习、自然语言处理、机器学习等 6 大技能板块
- **我的项目**：AI 聊天机器人、智能搜索引擎、图像生成器
- **找我聊聊**：Email、GitHub、LinkedIn、Twitter

## 🎨 设计风格

### Web 2.0 特点

- ✨ **明快配色**：浅蓝、青绿、橙色、粉色渐变
- 🌈 **柔和渐变**：多层渐变背景，视觉舒适
- 🎭 **小情绪设计**：活泼的 emoji 表情，亲切友好
- 🔵 **圆角卡片**：柔和的圆角设计，减少尖锐感
- 💫 **流畅动画**：hover 效果和滚动动画，生动活泼
- 📱 **响应式布局**：完美适配移动端和桌面端

### 颜色方案

- **主色调**：#3498db（明亮蓝色）
- **辅助色**：#1abc9c（青绿色）、#f39c12（橙色）、#e91e63（粉色）
- **背景渐变**：#e0f7fa → #b2ebf2（浅青色渐变）

## 🚀 技术栈

- **Bootstrap 5**：响应式 UI 框架
- **jQuery**：交互效果和动画
- **Bootstrap Icons**：图标库
- **HTML5 & CSS3**：页面结构和样式
- **GitHub Pages**：静态网站托管

## ✨ 功能特性

- ✅ 固定顶部导航栏，滚动跟随
- ✅ 平滑滚动效果
- ✅ 滚动时的元素淡入动画
- ✅ 悬停卡片动画效果
- ✅ 彩色标签系统
- ✅ 弹跳 emoji 动画
- ✅ 完全响应式设计
- ✅ SEO 优化

## 📦 部署

此网站通过 GitHub Pages 自动部署，每次推送到 `main` 分支后会自动更新。

### 本地预览

```bash
# 克隆仓库
git clone https://github.com/awt135/tom-clancy-portfolio.git

# 进入目录
cd tom-clancy-portfolio

# 使用本地服务器预览
python -m http.server 8000
# 或
npx serve
```

## 🎯 自定义

### 修改个人信息

编辑 `index.html` 中的：
- `<h1>`：你的名字
- `.hero-location`：你的位置
- `.about-text`：个人简介
- `.skill-card`：技能卡片内容
- `.project-card`：项目卡片内容

### 更改颜色

修改 `<style>` 中的 CSS 变量：
```css
:root {
    --primary-color: #3498db;
    --secondary-color: #1abc9c;
    --accent-color: #f39c12;
    --pink-color: #e91e63;
}
```

### 添加新项目

复制 `project-card` 结构并修改内容：
```html
<div class="col-lg-4">
    <div class="project-card">
        <div class="project-header project-ai">
            <h4 class="mb-0">🎯 你的项目</h4>
        </div>
        <div class="project-body">
            <p>项目描述...</p>
            <div class="mt-3">
                <span class="tag tag-python">标签1</span>
                <span class="tag tag-pytorch">标签2</span>
            </div>
        </div>
    </div>
</div>
```

---

© 2026 汤姆克兰德 | 用 ❤️ 和 AI 构建 | Web 2.0 风格
