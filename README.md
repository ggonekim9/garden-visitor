# 花园来客 · 互动闪卡

银灰色的小来客，踩着晨光走过花园。支持拖动旋转、翻面、调整银色全息光泽与景深，以及保存当前画面。

[打开闪卡](https://ggonekim9.github.io/garden-visitor/)

## 运行与更新

这是可直接发布到 GitHub Pages 的独立静态网站。图片、三维模型和运行程序均随站点提供，访客无需登录，也无需连接 ChatGPT 服务。

修改 `app.source.js` 后，运行：

```sh
npm ci
npm run build
npm start
```

将重新生成的 `app.js` 一同提交。GitHub Pages 使用 `main` 分支的根目录作为发布来源。

## 画面

本版本已修复猫咪毛发和胡须边缘：保留细毛的连续透明度，移除背景残留，并以预乘 Alpha 处理网页纹理过滤。背景、猫咪、线描和银色装饰保持独立图层。

## 致谢与素材

制作基于 [Holo Card Studio](https://github.com/EverettFish/holo-card-studio)，网页使用 [Three.js](https://threejs.org/)。软件许可见 `THIRD-PARTY-NOTICES.txt`。

卡片画面根据用户提供的猫咪照片制作；软件许可不授予照片与画面素材的再使用权。
