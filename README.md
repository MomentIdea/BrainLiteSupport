# BrainLite Support

App Store Connect 技术支持页。纯静态 HTML，无构建步骤。英文首页在 `index.html`，简体中文页在 `zh/index.html`。两页都显示已提供的公开邮箱 `momentidea.support@gmail.com`。 邮件入口会预填带有 `[BrainLite]` 前缀的主题，以及对应语言的反馈模板。工作室邮箱可按该主题前缀筛选 BrainLite 来信。

## 本地预览

在仓库目录运行 `python3 -m http.server 8000`，打开 `http://localhost:8000/`。按 Ctrl+C 停止。

## 发布后填写 App Store Connect

如果用 GitHub Pages，可以在网页文件提交到 `main` 后，在仓库的 Settings → Pages 选择 Deploy from a branch，来源选 `main` 和 `/(root)`，再保存。Pages 是否可用取决于仓库设置和 GitHub 计划。也可以把这些文件部署到已有的 HTTPS 静态站。

以部署后台给出的最终地址为准。提交审核前，用未登录的浏览器访问英文和中文网址，确认页面可读、邮箱正确，并从另一个邮箱发一封测试邮件确认能收到。App Store Connect 的 Support URL 填公开页面的完整 HTTPS 地址。隐私政策 URL 在 App Store Connect 单独维护。

苹果要求支持网址提供真实且有效的联系信息。当地法规要求同时披露其他联系信息时，使用实际的公开业务信息补充。[Apple Support URL 字段说明](https://developer.apple.com/help/app-store-connect/reference/app-information/platform-version-information/)
