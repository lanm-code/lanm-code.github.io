# 兰云皓 · 个人简历

个人简历主页(单文件、自包含,头像/证书/游戏示意图均已 base64 内嵌),部署在 GitHub Pages。

- 网站地址:https://lanm-code.github.io/symmetrical-octo-palm-tree/
- 仓库地址:https://github.com/lanm-code/symmetrical-octo-palm-tree

## 文件说明

- `index.html` —— 网页主文件,单文件即可正常显示
- `钢铁前线_游戏包.zip` —— 游戏《钢铁前线》免安装版(EXE),下载解压后双击 `钢铁前线.exe` 即玩
- `钢铁前线_运行说明.txt` —— 免安装版运行说明

## 如何更新

1. 修改 `index.html`(或替换上面的下载文件)
2. 提交并推送:

   ```
   git add .
   git commit -m "更新主页"
   git push
   ```

3. GitHub Actions 会自动重新部署到 Pages,约 1 分钟生效

## 部署方式

- 静态托管,无需构建;通过 `.github/workflows/pages.yml` 自动部署到 GitHub Pages
- `index.html` 里的下载链接为**相对路径**,指向本仓库根目录的 `钢铁前线_游戏包.zip` 与 `钢铁前线_运行说明.txt`
