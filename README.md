# 🚀 uAvicii's Digital Sanctuary

> 一个炫酷的个人博客网站，展示代码诗人的赛博空间

## ✨ 特性

- 🎨 **现代化设计** - 采用深色主题，科技感十足
- 🌈 **动态效果** - 代码雨、渐变动画、悬停效果
- 📱 **响应式布局** - 完美适配各种设备
- 🎯 **交互体验** - 平滑滚动、加载动画、鼠标跟随
- 🎪 **彩蛋系统** - 隐藏的Konami Code彩蛋
- 🔧 **高性能** - 优化的CSS和JavaScript

## 🛠️ 技术栈

- **HTML5** - 语义化标签
- **CSS3** - 现代CSS特性，Grid布局，Flexbox
- **JavaScript** - 原生JS，无框架依赖
- **Font Awesome** - 图标库
- **Google Fonts** - 字体优化
- **Vercel** - 部署平台

## 🎨 设计理念

### 色彩方案
- 主色调：霓虹绿 `#00ff88`
- 辅助色：霓虹粉 `#ff0080`
- 强调色：霓虹蓝 `#0080ff`
- 背景色：深空黑 `#0a0a0a`

### 视觉效果
- **代码雨效果** - 营造Matrix风格的科技感
- **渐变文字** - 彩虹色渐变标题
- **发光效果** - 霓虹灯式的光晕
- **玻璃拟态** - 半透明卡片设计

## 📁 项目结构

```
.
├── index.html              # 主页面
├── blog/                   # 博客文章目录
│   └── ai-programmer.html  # AI时代程序员文章
├── college_admission_report.html  # 原高考报告（保留）
├── vercel.json            # Vercel配置
├── package.json           # 项目配置
└── README.md              # 项目说明
```

## 🚀 部署

本项目已部署到Vercel，支持自动部署：

1. **克隆仓库**
   ```bash
   git clone https://github.com/uAvicii/0627.git
   cd 0627
   ```

2. **本地预览**
   ```bash
   # 使用任何静态服务器
   npx serve .
   # 或者使用Python
   python -m http.server 8000
   ```

3. **部署到Vercel**
   ```bash
   vercel --prod
   ```

## 🎯 功能特色

### 🌟 主要功能
- **响应式导航栏** - 滚动隐藏/显示
- **英雄区域** - 动态背景和代码雨效果
- **技能展示** - 交互式技能卡片
- **博客系统** - 文章列表和详情页
- **联系方式** - 社交媒体链接

### 🎪 隐藏彩蛋
- **Konami Code** - 输入 ↑↑↓↓←→←→BA 触发彩虹效果
- **鼠标跟随** - 自定义光标效果
- **打字机效果** - 动态文字显示

## 🎨 自定义样式

### CSS变量
```css
:root {
    --primary-color: #00ff88;    /* 主色调 */
    --secondary-color: #ff0080;  /* 辅助色 */
    --accent-color: #0080ff;     /* 强调色 */
    --bg-dark: #0a0a0a;         /* 背景色 */
    --text-primary: #ffffff;     /* 主文字色 */
    --text-secondary: #a0a0a0;   /* 次文字色 */
}
```

### 动画效果
- `bgFloat` - 背景浮动动画
- `titleGlow` - 标题发光效果
- `pulse` - 脉冲动画
- `fall` - 代码雨下落效果
- `spin` - 加载旋转动画

## 📝 内容管理

### 添加新博客文章
1. 在 `blog/` 目录下创建新的HTML文件
2. 使用现有模板结构
3. 更新首页的博客卡片链接

### 修改个人信息
- 编辑 `index.html` 中的个人介绍部分
- 更新社交媒体链接
- 修改技能列表

## 🔧 开发指南

### 代码规范
- 使用语义化HTML标签
- CSS采用BEM命名规范
- JavaScript使用ES6+语法
- 注释清晰，代码简洁

### 性能优化
- 图片懒加载
- CSS和JS压缩
- 字体优化加载
- 减少HTTP请求

## 🌟 特色亮点

1. **科技感设计** - 霓虹色彩搭配，未来主义风格
2. **丰富动画** - 多种CSS动画和JavaScript交互
3. **个性化内容** - 幽默风趣的文案，有内涵的技术分享
4. **用户体验** - 流畅的交互，直观的导航
5. **移动适配** - 完美的响应式设计

## 🎉 致谢

感谢以下资源的支持：
- [Font Awesome](https://fontawesome.com/) - 图标库
- [Google Fonts](https://fonts.google.com/) - 字体服务
- [Vercel](https://vercel.com/) - 部署平台

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

<div align="center">
  <p>Made with ❤️ and lots of ☕</p>
  <p>© 2024 uAvicii.dev - 用代码编织梦想</p>
</div> 