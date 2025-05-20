# VendSense 官方网站

这是 VendSense 智能售货机管理系统的官方网站源代码。网站采用现代化的设计风格，展示了 VendSense 的核心功能和价值主张。

## 项目结构

```
.
├── index.html      # 主页面
├── styles.css      # 样式文件
├── logo.png        # VendSense logo
└── README.md       # 项目说明文档
```

## 功能特点

- 响应式设计，支持各种设备尺寸
- 现代化的UI/UX设计
- 优化的性能和加载速度
- 清晰的产品功能展示
- 简洁的下载引导

## 开发环境设置

1. 克隆仓库：
```bash
git clone [repository-url]
cd vendsense-website
```

2. 安装依赖（如果需要）：
```bash
npm install
```

3. 本地开发：
使用任何静态文件服务器来运行网站，例如：
```bash
python -m http.server 8000
# 或
npx serve
```

## 部署

网站可以部署到任何静态网站托管服务，如：
- GitHub Pages
- Netlify
- Vercel
- 阿里云OSS
- 腾讯云COS

## 自定义

1. 更新颜色主题：
   - 在 `styles.css` 中修改 `:root` 变量

2. 更新内容：
   - 在 `index.html` 中修改相应的文本内容

3. 更新图片：
   - 替换 `logo.png` 和其他图片资源

## 贡献

欢迎提交 Pull Requests 来改进网站。请确保您的代码符合现有的代码风格。

## 许可证

[许可证类型] - 查看 LICENSE 文件了解更多信息 