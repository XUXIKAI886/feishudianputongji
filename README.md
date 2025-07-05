# 呈尚策划 - 飞书店铺统计系统

一个采用苹果官网风格设计的高端毛玻璃效果主页面，为飞书店铺统计系统提供优雅的入口界面。

## 🌟 项目特色

### 🍎 苹果官网风格设计
- **极简主义理念**: 采用苹果官网的设计语言，注重内容本身
- **毛玻璃效果**: 强化的 `backdrop-filter` 效果，营造高端质感
- **精致排版**: 使用苹果标准字体 SF Pro Display/Text，优化字间距和行高
- **中性色调**: 苹果风格的浅灰渐变背景配色

### ✨ 高端视觉效果
- **多层阴影**: 3-5层不同强度阴影营造空间深度感
- **边框高光**: 渐变边框模拟苹果设备玻璃质感
- **流畅动画**: 使用苹果风格缓动函数的交互动画
- **响应式设计**: 完美适配桌面、平板、手机等各种设备

### 🚀 功能模块
- **飞书运营数据统计系统**: 直达数据分析平台
- **查询店铺解约状态**: 快速查询合作状态

## 🛠️ 技术实现

### 核心技术
- **HTML5**: 语义化标签结构
- **CSS3**: 现代CSS特性
  - `backdrop-filter`: 毛玻璃背景模糊
  - `mask`: 精致渐变边框效果
  - `cubic-bezier`: 苹果风格缓动动画
- **SVG图标**: 矢量图标，完美缩放
- **响应式布局**: CSS Grid + Flexbox

### 浏览器兼容性
- ✅ Chrome 76+
- ✅ Firefox 103+
- ✅ Safari 9+
- ✅ Edge 79+

## 📱 响应式设计

### 桌面端 (>768px)
- 双列网格布局
- 大尺寸图标和按钮
- 丰富的悬停效果

### 平板端 (768px-480px)
- 单列布局
- 适中的元素尺寸
- 优化的触摸体验

### 移动端 (<480px)
- 紧凑的单列布局
- 大号触摸目标
- 简化的动画效果

## 🎨 设计规范

### 色彩搭配
- **主背景**: `#f5f7fa` → `#c3cfe2` 渐变
- **卡片背景**: `rgba(255, 255, 255, 0.7)` 半透明白色
- **主色调**: `#007aff` 苹果蓝
- **文字颜色**: `#1d1d1f` (主标题), `#6e6e73` (副文本)

### 字体层次
- **主标题**: 3.5rem, font-weight: 600
- **副标题**: 1.3rem, font-weight: 400
- **卡片标题**: 1.75rem, font-weight: 600
- **描述文字**: 1.1rem, font-weight: 400

### 间距系统
- **容器间距**: 60px
- **卡片内边距**: 60px × 40px
- **元素间距**: 20px, 30px, 40px

## 🚀 快速开始

### 本地运行
```bash
# 克隆仓库
git clone https://github.com/XUXIKAI886/feishudianputongji.git

# 进入项目目录
cd feishudianputongji

# 使用任意HTTP服务器运行
# 方式1: 使用Python
python -m http.server 8000

# 方式2: 使用Node.js
npx serve .

# 方式3: 直接在浏览器中打开index.html
```

### 在线访问
- **GitHub Pages**: https://xuxikai886.github.io/feishudianputongji/
- **GitHub仓库**: https://github.com/XUXIKAI886/feishudianputongji

## 📂 项目结构

```
feishudianputongji/
├── index.html          # 主页面文件
├── README.md           # 项目说明文档
└── .git/              # Git版本控制
```

## 🔧 自定义配置

### 修改链接地址
在 `index.html` 中找到对应的 `onclick` 事件，修改URL：

```javascript
// 飞书运营数据统计系统链接
onclick="openLink('你的新链接地址')"

// 查询店铺解约状态链接  
onclick="openLink('你的新链接地址')"
```

### 自定义样式
主要样式变量位于CSS的 `:root` 选择器中，可以轻松修改：
- 主色调
- 背景渐变
- 字体大小
- 间距尺寸

## 🌐 部署指南

### GitHub Pages 部署
1. 在GitHub仓库设置中启用Pages
2. 选择 `main` 分支作为源
3. 访问 `https://用户名.github.io/仓库名`

### 其他平台部署
- **Vercel**: 连接GitHub仓库自动部署
- **Netlify**: 拖拽文件夹或连接Git
- **服务器**: 上传文件到Web目录

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 👨‍💻 作者

**呈尚策划团队**
- 项目设计: 苹果官网风格UI设计
- 技术实现: 现代Web技术栈
- 维护更新: 持续优化用户体验

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

---

⭐ 如果这个项目对您有帮助，请给它一个星标！
