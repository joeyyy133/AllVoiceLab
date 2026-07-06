# 趣丸千音公开课页面

这是一个可直接发布的静态页面项目。

## 文件

- `index.html`: 对外访问的首页
- `article.md`: 原始 Markdown 备份
- `.nojekyll`: 关闭 GitHub Pages 的 Jekyll 处理，避免静态文件被改写

## GitHub 上传

把本目录作为一个 GitHub 仓库上传即可。建议仓库名：

`quwan-qianyin-page`

## EdgeOne Makers 发布配置

在 EdgeOne Makers 中连接 GitHub 仓库后：

- Framework preset: `Other` / 静态站点
- Build command: 留空
- Output directory: `.`
- Root directory: `.`

部署完成后，EdgeOne 会生成一个可公开访问的 URL。
