# o.lab SVG 3D Demo

交互式 `o.lab` 视觉原型，基于单文件 `HTML + CSS + JavaScript` 构建。

## 内容

- `svg-frame-demo.html`
  主程序文件
- `index.html`
  入口页，会跳转到主程序
- `assets/fonts/OPPO Sans 4.0.ttf`
  项目内置字体资源

## 本地打开

直接在浏览器里打开 `index.html` 或 `svg-frame-demo.html` 即可。

## 发布到 GitHub

1. 在 GitHub 新建一个仓库
2. 在当前目录执行：

```bash
git remote add origin <你的仓库地址>
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

## GitHub Pages

如果要直接生成网页链接，可以在仓库设置里开启 GitHub Pages：

1. 打开仓库 `Settings`
2. 进入 `Pages`
3. `Build and deployment` 里选择 `Deploy from a branch`
4. Branch 选择 `main`
5. Folder 选择 `/(root)`
6. 点击 `Save`

启用后，站点地址通常会是：

`https://5r6h.github.io/olab/`

项目根目录已经包含 `index.html`，并且增加了 `.nojekyll`，适合直接从 `main` 分支根目录发布。
