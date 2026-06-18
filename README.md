<h1 align="center">🖼️ Image Hosting Repository</h1>

<p align="center">一个基于 Git + 静态托管平台的个人图床仓库，用于存储和管理图片资源。</p>

---

## 📌 用途说明

本仓库是一个**图床（Image Hosting）**项目，主要用于：

- 存储博客、文档中引用的图片
- 为静态网站提供图片外链
- 集中管理各类图片资源，避免散落在不同项目中

## 🚀 使用方式

### 上传图片

```bash
git add your-image.png
git commit -m "Add image: your-image.png"
git push origin main
```

### 引用图片

推送后，可通过 GitHub Raw / jsDelivr CDN 获取图片外链：

- **GitHub Raw**：`https://raw.githubusercontent.com/<用户名>/<仓库名>/main/your-image.png`
- **jsDelivr CDN**：`https://cdn.jsdelivr.net/gh/<用户名>/<仓库名>@main/your-image.png`

> 💡 推荐使用 **jsDelivr**，全球 CDN 加速，访问更快。

### Markdown 中使用

```markdown
![图片描述](https://cdn.jsdelivr.net/gh/<用户名>/<仓库名>@main/your-image.png)
```

## 📂 目录结构

```
image-hosting/
├── blog/         # 博客配图
├── screenshots/  # 截图
├── icons/        # 图标资源
└── README.md     # 本说明文件
```

## ⚠️ 注意事项

- 请勿上传敏感信息或隐私图片
- 单文件大小建议控制在 5MB 以内
- 遵循图片版权法规，勿上传侵权内容
- 建议使用有意义的文件名，方便后续查找

## 📄 许可证

仅用于个人图片存储与引用，不对外授权。
