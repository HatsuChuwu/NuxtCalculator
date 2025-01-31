# Nuxt 计算器

一个使用 Nuxt 3 构建的简单计算器应用。

## 特点

- 现代化的用户界面
- 深色/浅色主题切换
- 响应式设计
- 键盘支持
- 数字格式化

## 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev
```

## 部署到 GitHub Pages

1. 将代码推送到 GitHub 仓库:

```bash
git init
git add .
git commit -m "初始化项目"
git branch -M main
git remote add origin 你的仓库地址
git push -u origin main
```

2. 在 GitHub 仓库设置中:
   - 进入 Settings > Pages
   - Source 选择 "GitHub Actions"
   - 等待自动部署完成

3. 部署完成后，你的应用将可以通过以下地址访问：
   `https://你的用户名.github.io/JS简单计算器/`

## 构建静态文件

```bash
# 生成静态文件
npm run generate

# 预览构建结果
npm run preview
```

## 技术栈

- Nuxt 3
- Vue 3
- Font Awesome 图标
- Google Fonts (Poppins)
