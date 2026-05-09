# 🗿 Sisyplus
>  Sisyplus————Sisyphus Plus

> **“The struggle itself toward the heights is enough to fill a man's heart.”**

一个基于原生 JavaScript 与 CSS3 物理模拟的“无效化”验证系统实验。

## 🌈 项目简介

**Sisyplus**（西西弗斯-增强版）是一个交互式网页实验。它模仿了现代 UI 中的“验证码”或“进度条”逻辑，但加入了一个残酷的物理现实：无论你如何努力推动那个代表进度的“巨石”，它最终都会因为重力模拟和物理碰撞回到原点。

这是一个关于**交互、挫败感与物理模拟**的小小尝试。

## ✨ 特性

* **物理引擎模拟**：利用原生 JS 计算加速度、重力和碰撞，非简单的线性动画。
* **CSS3 硬件加速**：丝滑的 60 FPS 物理表现，利用 `transform` 与 `transition` 保证视觉流畅度。
* **ACGN 审美适配**：UI 设计保留了细腻的动态效果，支持自定义背景与透明玻璃态质感。
* **纯粹性**：无框架依赖（Vanilla JS），轻量、快速、无意义。

## 🛠️ 技术细节

* **核心算法**：基于 Verlet 积分或简单的欧拉积分实现的重力演算。
* **交互逻辑**：
* 鼠标/触摸屏实时受力监听。
* 动态阻尼（Friction）与弹性系数（Restitution）调节。


* **部署**：完美适配 Cloudflare Pages。

## 🚀 快速开始

1. **克隆项目**
```bash
git clone https://github.com/Mrmiaomrzh/Sisyphus.git

```


2. **本地预览**
直接用浏览器打开 `index.html` 即可。
3. **自定义**
在 `physics.js`（或对应的逻辑文件）中修改 `GRAVITY` 常量来增加“推石”的难度。

## 🤝 贡献者

* **Original Project Author & Inspiration Provided**: [CS-LX](https://github.com/CS-LX)
* **Contributors**: [HSSkyBoy / NkBe](https://github.com/HSSkyBoy)
* **Developer**: [Mrmiaomrzh / NekoCat](https://github.com/Mrmiaomrzh)


## 📜 许可证

根据 **MIT License** 许可。你可以随意推你的石头，但请保留原作者信息。

