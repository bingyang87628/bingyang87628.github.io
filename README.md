# 冰洋AI探索

这是一个基于 Hugo 框架的个人博客网站，专注于分享 AI 技术探索和学习经验。

## 特点

- 使用 Hugo 静态网站生成器
- 采用现代简约的 Stack 主题
- 支持文章搜索功能
- 响应式设计，支持移动端
- 支持深色模式

## 本地开发

1. 克隆仓库：
```bash
git clone https://github.com/bingyang-blog/bingyang-blog.github.io.git
cd bingyang-blog.github.io
git submodule update --init --recursive
```

2. 安装 Hugo：
```bash
# macOS
brew install hugo

# Windows
choco install hugo-extended

# Linux
snap install hugo
```

3. 本地预览：
```bash
hugo server -D
```

访问 http://localhost:1313 查看效果

## 添加新文章

```bash
hugo new content post/文章名/index.md
```

## 部署

本站使用 GitHub Actions 自动部署到 GitHub Pages。每次推送到 main 分支都会触发自动部署。

## 许可证

MIT License 