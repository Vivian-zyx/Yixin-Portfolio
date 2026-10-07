GitHub Pages 上传说明

需要上传的完整内容：
1. index.html
2. assets 文件夹（必须完整上传）
3. .nojekyll

asset-manifest.json 是资源校验清单，建议一并保留。

发布步骤：
1. 在 GitHub 新建一个仓库。
2. 将本文件夹里的所有内容上传到仓库根目录，不要只上传 index.html。
3. 打开仓库 Settings → Pages。
4. 在 Build and deployment 中选择 Deploy from a branch。
5. Branch 选择 main，目录选择 /(root)，然后保存。
6. 等待 GitHub Pages 构建完成，即可访问网站。

注意：
- index.html 必须位于仓库根目录。
- 不要修改 assets 文件夹名称或内部文件名。
- 网站字体通过 Google Fonts 在线加载，其余图片与视频均已包含在上传包内。
