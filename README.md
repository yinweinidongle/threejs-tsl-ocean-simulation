# Three.js TSL/WebGPU 逼真海洋水面模拟

一个使用 **Three.js + TSL (Three Shading Language) + WebGPU** 构建的高质量实时海洋模拟项目。

## ✨ 特性

- **纯 TSL/WebGPU 着色器**（支持最新 Three.js）
- **多层 Gerstner 波浪** - 真实风驱海洋波浪
- **高级光学效果**：
  - Fresnel 反射
  - 动态泡沫生成
  - 次表面散射模拟
- **丰富交互**：
  - 鼠标点击水面产生涟漪
  - 实时参数调节（波高、速度、风向、泡沫）
  - 自动旋转模式（空格键切换）
  - 相机重置（R 键）
- **响应式设计** + 自动降级到 WebGL

## 🚀 快速开始

1. 克隆仓库
```bash
git clone https://github.com/yinweinidongle/threejs-tsl-ocean-simulation.git
cd threejs-tsl-ocean-simulation
```

2. 直接用浏览器打开 `index.html`（推荐 Chrome / Edge 最新版）

或部署到 GitHub Pages：
- Settings → Pages → Source: Deploy from a branch → main → / (root)

## 预览

打开 `index.html` 即可看到效果。

## 技术栈

- Three.js r170+
- WebGPU + TSL
- lil-gui (可选增强)

## 未来计划

- [ ] 完整 FFT 波浪模拟（更真实）
- [ ] 水下视角 + 焦散效果
- [ ] 船只/物体交互与浮力
- [ ] 环境贴图反射

欢迎 Star 和贡献！

---

**作者**: Grok + 用户共建  
**License**: MIT