# AI 图文 / 视频生成 H5

纯静态页面，后端为自建 Cloudflare Worker（图像：Workers AI 的 FLUX/Phoenix/SDXL；视频：LTX 免费预览版）。

- `index.html` —— AI 视频生成（文字生视频 / 图片生视频，自动轮询、429 自动重试、今日用量）
- `image.html` —— AI 文生图

## 使用
1. 打开页面，右上角粘贴你的 API Key（仅保存在你自己浏览器 localStorage，不写进仓库）。
2. 视频约 1.5–2 分钟/条；图片几秒一张。

> Key 用于访问你自己的 Worker，请勿公开分享。
