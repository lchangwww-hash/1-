# Lchang 的个人主页

一个无需安装依赖、无需构建的中文个人主页，使用 HTML、CSS 和少量 JavaScript，适配桌面与手机。

## 本地运行

在仓库目录执行：

```sh
python3 -m http.server 8000 --bind 0.0.0.0
```

浏览器打开该服务即可。也可以直接打开 `index.html`。按 `Ctrl+C` 停止服务。

## 自定义

- 在 `index.html` 修改姓名、自我介绍、项目和联系链接。目前使用 GitHub 用户名作为展示名，介绍为示例文案。
- 在 `style.css` 修改配色与布局，主要颜色集中在 `:root`。
- `script.js` 自动更新页脚年份。

页面不依赖外部字体、图片、框架或 API。可部署到 GitHub Pages 等静态网站托管服务。
