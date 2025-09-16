# Leapwhale Theme for Cloudflare Workers Blog

基于 [leapwhale.com](https://leapwhale.com/) 设计风格的现代化博客主题。

## 🎨 设计特色

- **现代深色主题** - 深色背景配色方案，符合Web3/技术博客的现代感
- **渐变色卡片** - 每个文章卡片都有独特的渐变背景
- **响应式设计** - 完美适配桌面端和移动端
- **卡片式布局** - 大尺寸卡片设计，视觉冲击力强
- **个人资料卡片** - 侧边栏包含个人信息和社交链接

## 🚀 功能特点

### 首页功能
- Hero 区域展示博客信息
- 多彩渐变背景的文章卡片
- 标签和分类系统
- 动态背景动画
- 现代化导航栏
- 个人资料侧边栏
- 随机文章推荐

### 文章页功能
- 渐变色文章头部
- 优化的阅读体验
- 代码高亮支持
- 文章导航
- 侧边栏小部件

### 后台管理
- 现代化仪表盘设计
- 侧边栏导航
- Markdown 编辑器集成
- 实时预览功能
- 响应式管理界面

## 📱 响应式设计

- **桌面端 (>1024px)**: 双栏布局，文章 + 侧边栏
- **平板端 (768-1024px)**: 单栏布局，侧边栏移至底部
- **移动端 (<768px)**: 优化的单栏布局，触摸友好

## 🎯 技术特点

- **Inter 字体** - 现代化的无衬线字体
- **Font Awesome 图标** - 丰富的图标库
- **Highlight.js** - 代码语法高亮
- **CSS 变量** - 便于主题定制
- **平滑动画** - 提升用户体验
- **渐变背景** - 每个卡片都有独特的渐变色

## 🛠️ 使用方法

1. 将 `leapwhale` 文件夹复制到你的 `themes` 目录下

2. 在 `index.js` 中修改主题配置：
   ```javascript
   "themeURL": "https://raw.githubusercontent.com/你的用户名/cloudflare-workers-blog/master/themes/leapwhale/"
   ```

3. 或者本地测试时使用：
   ```javascript
   "themeURL": "./themes/leapwhale/"
   ```

## 🎨 自定义配置

### 颜色变量
```css
:root {
    --primary-bg: #0a0a0a;
    --secondary-bg: #1a1a1a;
    --card-bg: #2a2a2a;
    --text-primary: #ffffff;
    --text-secondary: #b0b0b0;
    --text-muted: #808080;
    --accent-color: #00d4ff;
    --accent-hover: #00b8e6;
    --border-color: #333333;
}
```

### 渐变色配置
主题包含 4 种不同的渐变背景，会自动循环应用到文章卡片：
- 蓝紫渐变 (#667eea → #764ba2)
- 粉红渐变 (#f093fb → #f5576c)
- 蓝青渐变 (#4facfe → #00f2fe)
- 绿青渐变 (#43e97b → #38f9d7)

## 📁 文件结构

```
themes/leapwhale/
├── index.html          # 首页模板
├── article.html        # 文章页模板
├── admin/              # 后台管理
│   ├── index.html      # 后台首页
│   └── edit.html       # 文章编辑页
└── README.md           # 说明文档
```

## 🌟 特色功能

1. **多彩卡片设计** - 每个文章卡片都有独特的渐变背景色
2. **悬停动效** - 卡片悬停时会有缩放和阴影效果
3. **个人资料卡** - 右侧侧边栏包含个人信息和社交链接
4. **标签云** - 美观的标签显示
5. **随机文章** - 侧边栏推荐随机文章
6. **现代化后台** - 深色主题的管理界面

## 📄 许可证

MIT License

## 🙏 致谢

设计灵感来源于 [leapwhale.com](https://leapwhale.com/)，感谢原网站的精美设计。
