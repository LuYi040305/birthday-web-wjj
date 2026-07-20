# 给温家家的生日网站

这是一个无需构建的静态网站，可直接发布到 GitHub Pages。

## 修改内容

1. 编辑 `config.js` 中的姓名、日期、各页文字和最后的信。
2. 将照片放进对应目录，例如 `assets/photos/page-01/`。
3. 在 `config.js` 对应页面的 `photos` 中填写相对路径，例如：
   ```js
   photos: ['assets/photos/page-01/photo-1.jpg', 'assets/photos/page-01/photo-2.jpg']
   ```
4. 在浏览器打开 `index.html` 预览。不要用浏览器上传功能作为正式内容；它只在当前浏览器临时显示。

## 发布到 GitHub Pages

1. 在 GitHub 新建仓库，例如 `birthday-for-wenjiajia`，并将本项目全部文件推送到 `main` 分支。
2. 打开仓库 **Settings → Pages**，在 **Build and deployment** 选择 **Deploy from a branch**，分支选择 `main`、目录选择 `/(root)`，然后保存。
3. 稍等片刻，GitHub 会显示公开地址，通常为：`https://你的用户名.github.io/birthday-for-wenjiajia/`。
4. 每次改照片、文字或信件后，重新提交并推送；Pages 会自动更新。

可选：在 Pages 设置里绑定自定义域名，并按 GitHub 的提示配置 DNS。
