# 证件水印

给身份证、银行卡等证件照片加上防盗用水印的纯前端小工具。

**图片仅在本地浏览器处理，绝不上传服务器** —— 打开网页即用，也可保存 `index.html` 后离线使用。

## 特性

- 🔒 纯前端、零依赖、零上传，隐私安全
- 🧱 支持在图片上直接涂抹打马赛克（可调画笔粗细、马赛克粒度，支持单步撤销与一键清除）
- 📝 自定义水印文字、颜色、不透明度、大小、间隔、字体（水印覆盖在马赛克之上，保持清晰）
- 📱 自动按 EXIF 方向纠正手机竖拍照片
- 💾 一键保存成 PNG，设置自动记忆（localStorage）

## 使用

在线打开 `index.html`，或直接把文件下载到本地双击打开。

1. 选择或拖拽证件图片到页面
2. 如需遮挡敏感信息，直接在画布上涂抹打马赛克
3. 填写水印文字（如「仅供XX实名认证使用」）并调整样式
4. 点「保存图片」下载

## 致谢与授权

本项目基于 [zsxeee/Watermark-helper](https://github.com/zsxeee/Watermark-helper)（MIT，Copyright © 2020 zsxeee）的 `watermark-helper.html` 派生：核心的旋转平铺水印算法来自原作者，本仓库在其上修复了 EXIF 方向、保存性能等问题。经 [shihuili1218/watermark](https://github.com/shihuili1218/watermark) 中转。

以 [MIT](./LICENSE) 协议开源，保留原作者版权声明。
