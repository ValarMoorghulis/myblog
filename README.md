# 🌐 Valar Morghulis 的个人博客

这是我的个人静态博客仓库，完全托管于 GitHub Pages。

## 🚀 站点概览
- **预览地址**: [https://github.io](https://github.io)
- **构建引擎**: [Jekyll](https://jekyllrb.com) (GitHub Pages 默认)
- **当前主题**: Cayman (可根据 _config.yml 修改)

---

## 📂 目录结构规划
为了保持仓库整洁，我采用了以下结构进行管理：

*   `_posts/` - 📝 **文章存放处**。文件名格式：`YYYY-MM-DD-title.md`。
*   `assets/` - 🖼️ **静态资源**。存放博客用到的图片、自定义 CSS 或 PDF 附件。
*   `pages/`  - 📄 **独立页面**。如“关于我”、“项目汇总”或“分类索引”。
*   `_config.yml` - ⚙️ **站点大脑**。修改博客名称、描述、主题及导航配置。

---

## ✍️ 撰写指南 (备忘录)

### 发布新文章
1. 进入 `_posts/` 文件夹。
2. 创建新文件，命名为 `202X-XX-XX-my-new-post.md`。
3. 必须包含以下头部信息 (Front Matter)：
   ```yaml
   ---
   layout: post
   title: "文章标题"
   date: 202X-XX-XX
   categories: [分类1, 分类2]
   tags: [标签1, 标签2]
   ---
   ```

### 图片引用
建议将图片放在 `/assets/img/` 下，然后在 Markdown 中引用：
`![描述]({{ site.baseurl }}/assets/img/example.jpg)`

---

## 🛠️ 后续待办 (TODO)
- [ ] 完善 `about.md` 个人介绍页面
- [ ] 自定义域名绑定 (Optional)
- [ ] 增加评论插件 (如 Giscus 或 Valine)
- [ ] 优化移动端显示效果

---

## 📜 许可
本项目内容采用 [CC BY-NC-SA 4.0](https://creativecommons.org) 许可。
代码部分遵循 MIT 协议。
