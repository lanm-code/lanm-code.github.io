# 兰云皓个人主页

个人简历主页,部署在 Netlify(通过 GitHub 自动部署)。

## 文件说明

- `index.html` —— 网页主文件,头像和证书图片已内嵌(base64),单文件即可正常显示
- `avatar.jpg` —— 微信头像原图(枫叶),素材备份
- `cert-aliyun.jpg` —— 证书原图,素材备份

## 如何更新网站

1. 修改 `index.html`
2. 提交并推送到 GitHub:

   ```
   git add index.html
   git commit -m "更新主页"
   git push
   ```

3. Netlify 检测到推送后会自动重新部署,约 1 分钟内生效

## 注意

- 如果换了新图片,需要把图片转成 base64 内嵌进 `index.html`,或改为外部引用并保证图片文件也一起上传
- 网站为单文件部署:Netlify 发布目录设为仓库根目录,无需构建命令
