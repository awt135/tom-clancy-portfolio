# 汤姆克兰德个人主页

> AI 科技工作者的个人展示网站 - iOS 小清新风格

## 🌐 访问地址

[https://awt135.github.io/tom-clancy-portfolio/](https://awt135.github.io/tom-clancy-portfolio/)

## 👤 关于

这是汤姆克兰德的个人主页，展示作为一名 AI 科技工作者的专业技能、项目经验和联系方式。

### 主要内容

- **关于我**：个人简介和职业背景
- **技能**：深度学习、自然语言处理、机器学习等 6 大技能板块
- **项目**：AI 聊天机器人、智能搜索引擎、图像生成器
- **联系**：Email、GitHub、LinkedIn、Twitter

## 🎨 iOS 设计风格

### 设计特点

- 🍎 **Apple 风格**：遵循 Apple Human Interface Guidelines
- 💎 **毛玻璃效果**：导航栏采用 backdrop-filter blur
- 🔵 **圆角设计**：20px 大圆角卡片
- 🎯 **极简主义**：大量留白，简洁优雅
- ✨ **细腻阴影**：多层次阴影系统
- 🌈 **小清新配色**：柔和明亮的色彩
- 📱 **完美适配**：响应式设计，iOS 原生体验

### 颜色方案

- **背景色**：#f5f5f7（Apple 浅灰）
- **卡片背景**：#ffffff（纯白）
- **主色调**：#007AFF（iOS 蓝）
- **辅助色**：
  - 浅蓝：#5ac8fa
  - 绿色：#34c759
  - 橙色：#ff9500
  - 粉色：#ff2d55
- **文字色**：#1d1d1f（深灰）、#86868b（浅灰）

### iOS 风格元素

- ✅ 毛玻璃导航栏（滚动时背景变化）
- ✅ 大圆角卡片（20px）
- ✅ 柔和阴影系统（sm/md/lg）
- ✅ Apple 系统字体（-apple-system）
- ✅ 流畅的动画效果
- ✅ 圆形按钮（50px 圆角）
- ✅ 细腻的悬停效果

## 🚀 技术栈

- **Bootstrap 5**：响应式 UI 框架
- **jQuery**：交互效果和动画
- **Bootstrap Icons**：图标库
- **HTML5 & CSS3**：页面结构和样式
- **CSS 变量**：主题配置
- **GitHub Pages**：静态网站托管

## ✨ 功能特性

- ✅ 毛玻璃固定导航栏
- ✅ 滚动时导航栏背景变化
- ✅ 平滑滚动效果
- ✅ 淡入动画（页面加载）
- ✅ 悬停卡片动画效果
- ✅ 彩色标签系统
- ✅ 完全响应式设计
- ✅ iOS 原生字体
- ✅ 细腻的阴影层次
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

### 修改配色方案

编辑 `<style>` 中的 CSS 变量：

```css
:root {
    --bg-color: #f5f5f7;
    --card-bg: #ffffff;
    --primary-color: #007AFF;
    --secondary-color: #5ac8fa;
    /* ... 其他颜色 */
}
```

### 修改个人信息

编辑 `index.html` 中的：
- `.hero-title`：你的名字
- `.hero-location`：你的位置
- `.about-text`：个人简介
- `.skill-item`：技能卡片内容
- `.project-card`：项目卡片内容

### 调整圆角大小

修改全局圆角变量：

```css
.ios-card {
    border-radius: 20px; /* 调整这个值 */
}
```

### 调整阴影强度

修改阴影变量：

```css
:root {
    --shadow-sm: 0 2px 8px rgba(0, 0, 0, 0.04);
    --shadow-md: 0 4px 16px rgba(0, 0, 0, 0.08);
    --shadow-lg: 0 8px 32px rgba(0, 0, 0, 0.12);
}
```

### 添加新项目

复制 `project-card` 结构：

```html
<div class="col-lg-4">
    <div class="project-card">
        <div class="project-header project-ai">
            🎯 你的项目
        </div>
        <div class="project-body">
            <p>项目描述...</p>
            <div>
                <span class="tag tag-blue">标签1</span>
                <span class="tag tag-pink">标签2</span>
            </div>
        </div>
    </div>
</div>
```

### 创建新标签颜色

在 `<style>` 中添加：

```css
.tag-custom {
    background: #你的背景色;
    color: #你的文字色;
}
```

然后使用：

```html
<span class="tag tag-custom">新标签</span>
```

## 📱 浏览器兼容性

- ✅ Safari（最佳体验）
- ✅ Chrome
- ✅ Firefox
- ✅ Edge
- ⚠️ IE 11（不支持 backdrop-filter）

## 🌟 设计理念

这个主页遵循 Apple 的设计原则：

- **清晰**：内容层次分明，易于理解
- **一致**：统一的视觉语言
- **深度**：通过阴影和层次感创造深度
- **简洁**：去除不必要的装饰
- **专注**：突出重要内容

---

© 2026 汤姆克兰德 | iOS 小清新风格
