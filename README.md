# DDMeer Personal Site

这是一个基于学术展示网站。  
网站通过 **GitHub Pages** 部署，访问地址：[https://ddmeer.github.io](https://ddmeer.github.io)

---

## ✨ 功能特点

- 📝 **Home**: 论文风格的介绍页（标题、作者、摘要、关键词、亮点）。
- 📄 **Download**: 点击即可直接下载论文 PDF。
- 📊 **About**: 在网页中直接嵌入 PDF（论文或 Poster 预览）。
- 🔗 **GitHub Project**: 跳转到源码仓库。

---

## 📂 项目结构





---

## 🚀 部署方式

本项目基于 [Jekyll](https://jekyllrb.com/) 构建，**GitHub Pages** 自动部署：

- 仓库名称为 **`ddmeer.github.io`**，映射到 <https://ddmeer.github.io>。
- 每次推送到 `main` 分支时，GitHub 会自动构建并发布新版本。

---

## 🔧 修改方法

1. **修改论文内容**  
   编辑 `index.md`，更新 Title、Author、Abstract、Keywords、Highlights。

2. **替换 PDF 文件**  
   - 将 PDF 放到 `files/` 文件夹，例如 `files/paper.pdf`。
   - 在 `index.md` 或 `about.md` 中更新链接：
     ```html
     <a href="{{ '/files/paper.pdf' | relative_url }}" download>Download PDF</a>
     ```

3. **修改侧边栏**  
   编辑 `_includes/sidebar.html`。

4. **修改网站配置**  
   编辑 `_config.yml`，调整网站标题、副标题、baseurl 等。

---

## 🛠 本地预览

如果想在本地预览：

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve

```

## 🪪 License
本站点最初基于 [Hyde](https://github.com/poole/hyde) 主题修改。




