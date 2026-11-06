# 🐟 CyberWoodenFish · 赛博木鱼

<p align="center">
  <img src="https://img.shields.io/badge/Status-Peaceful-amber.svg?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/Audio-Web%20Audio%20API-emerald.svg?style=flat-square" alt="Web Audio" />
  <img src="https://img.shields.io/badge/Style-TailwindCSS-38bdf8.svg?style=flat-square" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Dependencies-Zero-green.svg?style=flat-square" alt="Zero Dependencies" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" alt="License" />
</p>

<p align="center">
  <b>For those who do not feel well while surfing the internet!</b><br>
  <i>专治上网冲浪时的烦躁、内耗与心浮气躁。涤心净意，功德+1。</i>
</p>

---

## 📖 简介 / Introduction

在快节奏的互联网冲浪时代，信息过载与争论纷扰往往让人心生浮躁。**CyberWoodenFish (赛博木鱼)** 是一款轻量、优雅且现代的网页版电子木鱼。

无需安装任何应用、无需配置复杂环境，甚至不需要网络请求音频文件——只需在浏览器中打开，即可随心敲击，或开启自动修行，聆听空灵纯净的木鱼回音，积攒赛博功德，找回内心的安宁。

> **“凡心偶起恶堕意，闻此鱼声罪自消。”**

---

## ✨ 核心特性 / Features

- 🔊 **纯原生 Web Audio 物理合成音效 (Zero External Audio Files)**
  - 彻底摆脱外部 `.mp3` / `.wav` 音频文件的网络延迟与加载失败烦恼；
  - 基于浏览器的 **Web Audio API**，通过多层振荡器 (Oscillator) 与带通滤波器 (BiquadFilter) 物理级模拟真实木槌打击的瞬态、红木中空腔体的空灵共振与温润的低频回响。

- 🎨 **禅意中式暗色美学 UI**
  - 精心绘制的矢量红木/紫檀木纹与金边木鱼造型；
  - 伴随点击的真实弹性形变（Squash & Bounce）动效、扩散的金色波纹与背景呼吸微光。

- 💫 **灵动弹字与随机祝福**
  - 每次敲击随机生成轻微倾斜漂浮上升的祝福文本：
    - `功德 +1`
    - `心绪渐宁 +1`
    - `杂念消除 +1`
    - `善意丰沛 +1`
    - `烦恼消解 +1`

- ⏱️ **自动诵经敲击模式 (Auto Knocker)**
  - 默认开启 60 BPM（每分钟 60 下 / 1 秒 1 次）稳定节拍敲击；
  - 配备脉冲呼吸指示灯（Pulse Indicator），上班挂机摸鱼、放空冥想两不误；
  - 可随时一键切换为手动专注模式。

- ⌨️ **全平台便捷交互**
  - **鼠标点击 / 屏幕触控**：点击木鱼主体即可触发敲击；
  - **空格快捷键 (Spacebar)**：键盘轻按 `Space` 即可击打木鱼；
  - **静音沉浸模式**：支持一键开关声音，办公室或公共场合静音积德；
  - **功德重置**：提供一键清零（心归太虚）按钮。

- 💾 **本地离线持久化**
  - 所有敲击积累的功德实时同步至浏览器的 `localStorage` 中；
  - 关闭浏览器或刷新页面，修行进度绝不丢失。

- 🚀 **极简单文件，开箱即用**
  - 纯静态页面架构，零构建、零依赖、无后端服务要求，双击即用。

---

## 🕹️ 快速上手 / Quick Start

### 1. 本地运行

克隆本项目到本地，直接双击用浏览器打开：

```bash
git clone https://github.com/Babooninboots/CyberWoodenFish.git
cd CyberWoodenFish
# 使用任意现代浏览器双击打开 index.html 即可
```

### 2. GitHub Pages 在线访问

你可以在仓库的 **Settings -> Pages** 中，将 Source 选为 `Deploy from a branch`（选择 `main` 分支根目录 `/ (root)` 并保存），即可获得永久在线的个人赛博木鱼页面：

```
https://<your-username>.github.io/CyberWoodenFish/
```

---

## 🛠️ 技术栈 / Tech Stack

- **HTML5** & **SVG**: 矢量木鱼与交互结构
- **Tailwind CSS**: 现代暗黑响应式界面排版
- **Web Audio API**: 实时声学合成器
- **Vanilla JavaScript**: 纯原生 DOM 事件与本地存储交互

---

## 🎮 操作指南 / Controls

| 动作 | 操作方式 | 说明 |
| :--- | :--- | :--- |
| **敲击木鱼** | 鼠标左键点击木鱼 / 触屏轻击 / 键盘按 `Space` 空格键 | 触发木鱼音效并增加功德点数 |
| **自动敲击** | 点击底部的「自动诵经敲击」开关 | 开启/关闭 60 BPM 节拍自动敲击 |
| **静音切换** | 点击右上角「声音 开/关」按钮 | 在有声模式与静音模式间切换 |
| **功德重置** | 点击右上角重置按钮（刷新图标） | 将功德计数值清空重置为 0 |

---

## 📜 许可证 / License

本项目采用 [MIT License](LICENSE) 开源协议。

愿每一位在互联网冲浪的朋友都能保持内心平和与清澈。🙏
