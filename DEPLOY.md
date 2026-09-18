# Coreclickmobile 网站文件

这是从原网站完整迁移并重新品牌化后的静态网站，可直接部署到 Cloudflare Pages。

## 已完成

- 英文和中文共 22 个页面全部改为 Coreclickmobile 品牌。
- 网站域名、SEO、结构化数据、隐私政策、使用条款、支持页和 sitemap 均已更新。
- 联系邮箱统一为 `contact@coreclickmobile.com`。
- 地址统一为 `Room 301/F, Ho King Commercial Centre, No. 2-16 Fa Yuen Street, Mong Kok, Hong Kong`。
- 根据提供的标志重新绘制轻量矢量 Logo：`assets/coreclickmobile-mark.svg`，约 1.3 KB。
- 全站恢复采用原网站的深黑、米白、荧光绿、珊瑚橙、紫色和天蓝色配色体系。
- 已加入 Cloudflare Pages 静态资源缓存和基础安全响应头。

## Cloudflare Pages 部署

把本目录作为 Cloudflare Pages 的部署目录即可。此网站为纯静态文件，不需要构建命令，也不需要设置输出目录。

部署后请确认 `coreclickmobile.com` 和 `www.coreclickmobile.com` 已绑定到同一个 Pages 项目，并按需要设置其中一个域名跳转到另一个域名。
