# Interactive Water Scene

一个基于 HTML5 Canvas 的交互式水面场景，包含游动的红色小鱼和丰富的交互效果。

## 功能特性

- **动画水面背景**：有机细胞状纹理，带有柔和的动画效果
- **场景 1**：一条红色小鱼自由游动，点击小鱼后跳跃并进入场景 2
- **场景 2**：五条小鱼，其中一条是"顽皮"的，点击它会跳跃，点击其他鱼会吓跑它们
- **交互效果**：
  - 点击水面产生涟漪
  - 鼠标移动产生尾流效果
  - 流畅的动画和过渡

## 在线访问

### 方法 1：GitHub Pages（推荐）

1. 访问 GitHub 仓库：https://github.com/zchen30-lab/ixp2
2. 进入仓库设置 Settings → Pages
3. 在 "Source" 下选择分支 `claude/interactive-water-scene-011CUpF97BZV2x51BVynLLco`
4. 选择根目录 `/ (root)`
5. 点击 Save
6. 等待几分钟后，访问：https://zchen30-lab.github.io/ixp2/

### 方法 2：本地运行

1. 克隆仓库：
```bash
git clone https://github.com/zchen30-lab/ixp2.git
cd ixp2
git checkout claude/interactive-water-scene-011CUpF97BZV2x51BVynLLco
```

2. 在浏览器中打开 `index.html` 或 `water-scene.html` 文件

### 方法 3：直接下载

访问以下链接下载文件：
https://github.com/zchen30-lab/ixp2/blob/claude/interactive-water-scene-011CUpF97BZV2x51BVynLLco/index.html

点击 "Raw" 按钮，然后保存文件到本地，用浏览器打开即可。

## GitHub 仓库位置

- **仓库地址**：https://github.com/zchen30-lab/ixp2
- **分支名称**：`claude/interactive-water-scene-011CUpF97BZV2x51BVynLLco`
- **主要文件**：
  - `index.html` - 网页入口文件
  - `water-scene.html` - 相同内容的备份文件

## 技术实现

- 纯 HTML + CSS + JavaScript
- 无需外部库或图片
- 使用 HTML5 Canvas API 绘制所有图形
- requestAnimationFrame 实现流畅动画
- 响应式设计，自适应窗口大小

## 浏览器要求

支持现代浏览器：
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
