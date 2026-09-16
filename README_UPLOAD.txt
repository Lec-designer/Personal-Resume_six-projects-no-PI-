GitHub Pages 上传包（六项目版）

已处理：
- 从单文件 HTML 拆出全部 Base64 图片/视频
- 自动去重重复媒体
- 将唯一超过浏览器单文件上传阈值的大视频压缩为浏览器安全大小
- 自动更新 index.html 媒体路径
- 已加入 .nojekyll，避免纯静态网站走 Jekyll 构建

原始 HTML：167.97 MiB
拆分后 index.html：0.16 MiB
Base64 引用：114 处
独立媒体：106 个
资源文件夹：7 个

上传建议：
1. 新建 Public GitHub 仓库。
2. 先上传 index.html、.nojekyll、asset_manifest.json，并 Commit。
3. 再逐个上传 assets-1、assets-2……，每个文件夹单独 Commit。
4. Settings → Pages → Deploy from a branch → main → /(root) → Save。

各资源文件夹：
- assets-1: 21.96 MiB / 1 files
- assets-2: 19.63 MiB / 1 files
- assets-3: 16.83 MiB / 4 files
- assets-4: 16.83 MiB / 5 files
- assets-5: 16.81 MiB / 15 files
- assets-6: 16.83 MiB / 45 files
- assets-7: 4.48 MiB / 35 files