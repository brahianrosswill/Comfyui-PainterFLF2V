# ComfyUI-PainterFLF2V  
### 让首尾帧视频“动”得更自然、更干净  
*Make first-last-frame videos move smoother & cleaner*

---

## 🎬 简介 | Intro
PainterFLF2V 是对官方 WAN 首尾帧节点的“动态增强补丁”。  
通过**反向结构斥力**算法，一键消除慢动作与重影，同时保护颜色不失真。  
PainterFLF2V is a plug-and-play upgrade for WAN's first-last-frame node.  
Using **inverse structural repulsion**, it erases ghosting & sluggish motion while keeping colors intact.

---

## ✨ 核心亮点 | Highlights
| 功能 | 效果 | Feature | Result |
|---|---|---|---|
| 动态增强幅度 | 1.0→2.0 无级滑杆 | Motion Amplitude | 1.0 (stock) – 2.0 (max boost) |
| 推荐“日常”值 | **1.3** 动静平衡 | Sweet-spot | **1.3** for natural yet punchy moves |
| 颜色锁定 | 零偏移 | Color Lock | Zero hue shift |
| 4× 去重影 | 中间帧更清晰 | Ghost Kill | 4× high-freq diff amplification |

---

## 🚀 快速开始 | Quick Start
1. 克隆到 `custom_nodes`  
   ```bash
   git clone https://github.com/princepainter/Comfyui-PainterFLF2V ComfyUI/custom_nodes/Comfyui-PainterFLF2V
2. 重启 ComfyUI  
   Restart ComfyUI
3. 工作流中把 `PainterFLF2V` 替换掉原生首尾帧节点即可  
   Drop `PainterFLF2V` in place of the stock first-last-frame node.

---

## 🎛️ 参数速查 | Params Cheat-Sheet
| 参数 | 范围 | 推荐 | Tips |
|---|---|---|---|
| motion_amplitude | 1.0 – 2.0 | **1.3** | 1.0=原版，1.3=日常，2.0=极客测试 |
| width/height | 16-4096 | 832×480 | 按需求保持 16 的倍数 |
| length | 1-4096 | 81 | 越大越吃显存 |

---

## 📈 效果对比 | Before vs After
| 场景 | 原版 1.0 | PainterFLF2V 1.3 |
|---|---|---|
| 人物转身 | 慢半拍 / 残影 | 干净利落 / 动作饱满 |
| 风景推拉 | 色块拖尾 | 线条清晰 / 颜色稳定 |

---

## 📜 许可证 | License
[MIT](./LICENSE) – 随意商用 & 魔改，点个⭐ 就好 :)  
Feel free to commercialize & fork; just give us a star ⭐
```
