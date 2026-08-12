# Minecraft World

An open-source Codex skill that reconstructs photographs as coherent, cinematic scenes inside a Minecraft-like game world.

> 一个开源的 Codex Skill，将照片重建为统一、具有电影感的 Minecraft 风格游戏世界。

Instead of applying a pixel or voxel filter, the skill identifies the defining subjects, removes clutter, and rebuilds the entire frame with structural blocks, low-resolution surface textures, designed block clouds, game lighting, and atmospheric depth.

> 它并非简单叠加像素或体素滤镜，而是识别关键主体、移除杂乱细节，并使用结构性方块、低分辨率表面纹理、设计化方块云、游戏光照和空间雾化重新构建整个画面。

## Before and After

### 效果对比

The source remains recognizable through its subjects, composition, environment, dominant colors, time of day, and mood, while every visible layer is rebuilt in one game-world visual language.

> 通过保留主体、构图、环境、主色调、时间和氛围，让原图保持可辨识，同时将所有可见层统一重建为游戏世界的视觉语言。

<p align="center">
  <img src="comparisons/winter-forest-comparison.png" alt="Winter forest before and after" width="47%">
  <img src="comparisons/tulip-comparison.png" alt="Tulip before and after" width="47%">
</p>

<p align="center">
  <img src="comparisons/guardian-statues-comparison.png" alt="Guardian statues before and after" width="47%">
</p>

## Features

### 特点

- **Source-aware reconstruction** — Preserves defining subjects, spatial relationships, environment identity, and dominant colors.<br>
  **忠于原图的重建** — 保留关键主体、空间关系、环境特征和主色调。

- **One coherent world** — Rebuilds the subject, ground, architecture, vegetation, sky, and lighting in the same visual language.<br>
  **统一的游戏世界** — 使用同一种视觉语言重建主体、地面、建筑、植被、天空和光照。

- **Structural block design** — Uses large block-built forms and stepped silhouettes instead of dense cubelet sculpture.<br>
  **结构性方块设计** — 使用大型方块结构和阶梯式轮廓，避免密集小方块雕塑。

- **Designed block clouds** — Replaces realistic clouds with flat rectangular slabs and stepped graphic cloud bands.<br>
  **设计化方块云** — 用平面矩形云层和阶梯式图形云带替代真实云层。

- **Cinematic game rendering** — Adds directional light, ambient occlusion, restrained shader grading, and world-space haze.<br>
  **电影感游戏渲染** — 加入方向光、环境光遮蔽、克制的着色器调色和空间雾化。

- **Broad photo support** — Works with portraits, animals, objects, architecture, landscapes, and travel photos.<br>
  **广泛的照片类型** — 支持人像、动物、物体、建筑、风景和旅行照片。

## Installation

### 安装

Copy the `minecraft-world` folder into your Codex skills directory:

> 将 `minecraft-world` 文件夹复制到 Codex Skills 目录：

```bash
cp -R minecraft-world "${CODEX_HOME:-$HOME/.codex}/skills/"
```

Restart or refresh Codex so it can discover the skill.

> 重启或刷新 Codex，使其发现新 Skill。

## Usage

### 使用

Attach a photograph and invoke the skill:

> 上传一张照片并调用 Skill：

```text
Use $minecraft-world to transform this photo.
```

The skill preserves the source by default. Ask explicitly if you want a different season, time of day, palette, or environment.

> Skill 默认忠于原图；如果希望改变季节、时间、色调或环境，请在指令中明确说明。

## Repository Structure

### 仓库结构

```text
minecraft-world/
├── SKILL.md
├── agents/openai.yaml
├── comparisons/
└── references/
    ├── examples.md
    └── style-guide.md
```

## License

### 许可证

Released under the MIT License. See [LICENSE](LICENSE).

> 本项目采用 MIT License，详见 [LICENSE](LICENSE)。
