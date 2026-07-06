# AllVoiceLab Pages

这是用于发布公众号文章静态页面的 GitHub Pages 仓库。

## 线上页面

- 首页文章：`https://joeyyy133.github.io/AllVoiceLab/`
- DataEye AIGC 产业园文章：`https://joeyyy133.github.io/AllVoiceLab/dataeye-aigc-park.html`

## 文件

- `index.html`: AI时代新副业 DataEye x 趣丸千音线下公开课文章
- `dataeye-aigc-park.html`: 祝贺 DataEye AIGC 产业园开园文章
- `assets/images/`: 页面图片资源，本地化后避免微信图片防盗链
- `.nojekyll`: 关闭 GitHub Pages 的 Jekyll 处理，避免静态文件被改写

## 更新流程

修改 HTML 或图片后：

```bash
git add .
git commit -m "Update page"
git push
```

GitHub Pages 会自动发布更新。
