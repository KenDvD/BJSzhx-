# 个人博客前端
<img width="679" height="467" alt="image" src="https://github.com/user-attachments/assets/873091b6-8c60-45e3-986c-8af15d28c767" />

一个现代化的静态个人博客网站，采用响应式设计，支持暗色主题。

## 功能特性

- 🎨 现代化UI设计，采用渐变背景和玻璃拟态效果
- 📱 完全响应式设计，支持移动端和桌面端
- 🌙 暗色/亮色主题切换
- ⚡ 平滑滚动和动画效果
- 📝 博客文章展示
- 📧 联系表单
- 🔗 社交媒体链接

## 项目结构

```
personal-blog/
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── script.js       # JavaScript文件
└── README.md           # 说明文档
```

## 快速开始

1. 直接在浏览器中打开 `index.html` 文件即可运行
2. 或者使用本地服务器运行以获得更好的体验：

```bash
# 使用 Python 内置服务器
python -m http.server 8000

# 使用 Node.js http-server
npx http-server

# 使用 PHP 内置服务器
php -S localhost:8000
```

3. 在浏览器中访问 `http://localhost:8000`

## 自定义内容

### 修改个人信息
编辑 `index.html` 文件中的以下部分：

1. **导航栏标题**：修改 `.nav-logo a` 中的文本
2. **英雄区域**：修改 `.hero-title` 和 `.hero-subtitle`
3. **关于我**：修改 `#about` 部分的内容
4. **技术栈**：在 `.skill-tags` 中添加或修改技能标签

### 添加博客文章
在 `#blog` 部分的 `.blog-grid` 中添加新的 `.blog-card`：

```html
<article class="blog-card">
    <div class="blog-image">
        <img src="图片URL" alt="文章标题">
    </div>
    <div class="blog-content">
        <h3 class="blog-title">文章标题</h3>
        <p class="blog-excerpt">文章摘要...</p>
        <div class="blog-meta">
            <span class="blog-date">日期</span>
            <span class="blog-read-time">阅读时间</span>
        </div>
        <a href="#" class="read-more">阅读更多</a>
    </div>
</article>
```

### 修改联系方式
在 `#contact` 部分更新社交媒体链接和邮箱地址。

## 样式定制

### 颜色主题
主要颜色变量在 `css/style.css` 中：

- 主色调：`#2563eb` (蓝色)
- 文字颜色：`#374151` (灰色)
- 背景色：`#f8fafc` (浅灰色)

### 字体
使用 Google Fonts 的 Inter 字体，可以在 `index.html` 中修改字体链接。

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 部署

这个静态博客可以部署到任何静态网站托管服务：

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- 阿里云OSS
- 腾讯云COS

## 许可证

MIT License - 可以自由使用和修改。

## 贡献

欢迎提交 Issue 和 Pull Request！

## 更新日志

### v1.0.0
- 初始版本发布
- 基础博客功能
- 响应式设计
- 暗色主题支持
