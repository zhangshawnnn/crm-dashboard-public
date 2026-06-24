# CRM行业画像看板静态发布包

这个目录是可直接部署到 GitHub Pages、Netlify、Cloudflare Pages 等静态托管平台的公开看板包。

必须保留在同一目录：

- `index.html`
- `chart.umd.min.js`

GitHub Pages 发布方式：

1. 新建一个 GitHub 仓库，例如 `crm-dashboard-public`
2. 上传本目录下的全部文件到仓库根目录
3. 在仓库 `Settings -> Pages` 中选择 `Deploy from a branch`
4. Branch 选择 `main`，Folder 选择 `/root`
5. 保存后等待 GitHub Pages 生成网址

注意：当前 `index.html` 内包含客户名称、机构、管户人、商机标签、建议动作等明细信息。公开部署后，任何拿到链接的人都可以查看。
