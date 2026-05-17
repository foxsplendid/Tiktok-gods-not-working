《这个神坛不太灵》在线部署包说明

直接部署:
1. 将本文件所在文件夹 online_demo_package_20260517 整个上传到 Netlify。
2. Netlify 拖拽部署时,请拖入文件夹本身或压缩包解压后的全部内容。
3. 入口文件是 index.html。

必须保持的目录结构:
index.html
assets/
  audio/
  bg/
  decor/
  deity/
  gods/
  signs/
  stickers/
  videos/

说明:
- 当前包已排除 stickers 目录下的 PSD 源文件,只保留页面运行需要的素材。
- 页面仍通过 CDN 加载 html2canvas:
  https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js
  因此在线访问时需要允许加载该 CDN。
- 若后续替换素材,请保持现有文件名不变,或同步修改 index.html 中的路径。
