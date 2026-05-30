# PDF 项目 — 中华衣冠奇遇记 H5

一个面向移动端的 H5 交互页面，主题为中国传统服饰（明代补服）科普。

## 技术栈

- 纯前端：HTML + CSS + JavaScript，不依赖框架
- 移动端优先，需兼容 iOS Safari 和 Android Chrome/微信内置浏览器
- 使用本地静态资源（图片、音频），不依赖 CDN

## 运行

```bash
python3 -m http.server 8080
# 然后浏览器打开 http://localhost:8080
```

## 资源约束

- 图片存放于 `./material/photos/`，JPG 品质 70%，单张不超过 200KB
- 音效使用 CC0 免费素材,在 './material/music/m4a'
- 目标：可通过 Canva 可画 / 易企秀等平台承载的轻量 H5

## 设计风格

手绘国潮插画风 + 轻微动效，色彩取自明代官绿、酱红、鸦青。

## 参考资料

- 脚本设计文档：[H5-脚本-补服篇.md](H5-脚本-补服篇.md)
- 孔府旧藏补服实物照片（用于纹样参考）
