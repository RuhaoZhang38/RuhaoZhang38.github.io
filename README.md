# 张汝昊学术主页

这是一个无需构建工具的静态网站，可直接发布到 GitHub Pages。`index.html` 是页面内容，`styles.css` 是样式，`portrait.jpg` 是从提供的 Word 简历中提取的照片。

## 本地预览

直接用浏览器打开 `index.html` 即可。发布后检查手机和电脑上的显示效果。

## 发布到 GitHub Pages

1. 在 GitHub 创建公开仓库，名称为 `你的GitHub用户名.github.io`。
2. 把 `index.html`、`styles.css`、`script.js`、`portrait.jpg` 和 `.nojekyll` 上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`、目录选 `/ (root)` 并保存。
4. 发布完成后访问 `https://你的GitHub用户名.github.io`。

不要把原始 Word 简历上传到公开仓库；仓库中的 `.gitignore` 也会排除 Word 文件。

## 发布前建议核对

- 论文的正式年份、作者顺序与名称。原始简历有一条未注明年份，暂未放到公开页面。
- 可补充每篇成果的 DOI、出版社页面或开放获取全文链接。
- 2020 年以后写作“至今”的项目状态，需按最新情况更新后再公开。

