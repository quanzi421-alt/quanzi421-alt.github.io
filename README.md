# 泉师傅 · FITZ

个人网站：https://quanzi421-alt.github.io/

大罗洞观 · 浮生耳目录 · 偶有所成

本仓库仅保存经过检查的公开网站静态发布包。GitHub Actions 会解压 `fitz-github-pages-site.zip`，将其中的网页、样式、脚本、封面及字体发布到 GitHub Pages。

这是只读公开展示版，不包含登录、后台编辑、自动抓取、数据库或飞书实时同步。完整开发项目与私人资料不在此仓库。

## 更新

在本地公开构建副本中更新内容、完成构建和公开数据检查后，替换同名 ZIP。ZIP 必须以 `index.html` 为根目录文件，保留 `_next/`、Next 路由 TXT 文件、`.nojekyll` 和字体许可。不要上传环境变量文件、Cookie、密钥、原始私人项目或交接压缩包。

自动发布工作流位于 `.github/workflows/pages.yml`。部署状态以 Actions 运行结果为准；实际访问体验取决于所在地网络，不能仅凭部署成功认定所有网络均可访问。
