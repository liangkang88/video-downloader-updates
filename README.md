# Video Downloader 更新源

本仓库仅用于「视频下载工具」的在线更新分发，不包含源代码。

- 更新清单：`update/update.json`
- 安装包：Releases 中的资产

客户端读取清单后按 `sha256` 与 `size` 校验安装包，校验通过才会静默安装。

清单可访问地址（CDN 镜像，便于国内访问）：

```
https://cdn.jsdelivr.net/gh/liangkang88/video-downloader-updates@main/update/update.json
```
