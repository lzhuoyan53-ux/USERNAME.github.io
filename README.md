# 个人日记网站（完整模板）

这个仓库是一个完整的个人日记网站模板（基于 GitHub Pages + Jekyll）。

快速上手（网页方式，推荐给非程序用户）
1. 在 GitHub 上新建仓库（见说明），将本仓库的文件逐个上传到新仓库（使用 “Add file” → “Create new file” 或 “Upload files”）。
2. 在仓库 Settings → Pages 中选择 Branch: main / Folder: / (root)，保存。几分钟后网站会出现并显示网址。
3. 写新日记：在 `_posts/` 目录创建文件，文件名格式 `YYYY-MM-DD-标题.md`，填写顶部的 YAML（示例在 `_posts/` 目录），Commit 后几分钟网站自动更新。

要点说明
- 如果你希望网址为 https://USERNAME.github.io，请把仓库名设置为 `USERNAME.github.io`（USERNAME 替换为你的 GitHub 用户名）。
- 想保密就把仓库设为 private（但访问方式可能不同）。
- 新日记写法示例：参见 `_posts/2025-12-02-my-first-diary.md`。
