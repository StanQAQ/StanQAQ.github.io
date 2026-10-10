# StanQAQ 个人网站

这是一个可直接托管在 GitHub Pages 的静态个人主页，使用原生 HTML 和 CSS 编写，没有依赖或构建步骤。

## 本地预览

在仓库根目录运行：

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

然后在浏览器访问 `http://127.0.0.1:8000`。按 `Ctrl+C` 停止预览服务。

## 发布到 GitHub Pages

仓库名为 `StanQAQ.github.io`。在仓库的 **Settings → Pages** 中，将发布来源设为 `Deploy from a branch`、分支 `main`、目录 `/ (root)`。保存后，GitHub Pages 会从仓库根目录发布 `index.html`。

`.nojekyll` 文件让 GitHub Pages 直接提供静态文件，不经过 Jekyll 处理。
