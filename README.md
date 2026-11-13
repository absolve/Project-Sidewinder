# Project-Sidewinder

一款俯视角载具射击游戏（Top-Down Vehicle Shooter）。玩家驾驶可改装的战斗载具，在手工设计的多区域战场上探索、完成目标并夺取敌人武器；故事通关后进入挑战模式，用突变因子与星级评分挑战极限。玩法融合 **双摇杆射击 + 可破坏地形采集 + 基地防守 + 割草式构筑成长**。

> 当前状态：项目搭建中（早期原型阶段）。

## 目录结构

```
Project-Sidewinder/
├── doc/                  # 设计文档（玩法、系统、关卡、数值等，持续补充）
├── Project-Sidewinder/   # Godot 工程目录
├── LICENSE               # 许可证（MIT）
└── README.md             # 本文件
```

## 技术栈

- 引擎：Godot 4.x
- 语言：GDScript / C#
- 目标平台：PC（Steam），优先适配 Steam Deck 与手柄

## 开发约定

- 设计文档统一放在 `doc/`，Godot 工程资源统一放在 `Project-Sidewinder/`。
- 文档使用 UTF-8 Markdown，建议用支持 UTF-8 的阅读器查看。
- 开发计划见 [doc/DEV_PLAN.md](doc/DEV_PLAN.md)（里程碑、验收标准、风险、范围裁剪顺序；活文档，随进度增改）。

## 许可证

本项目采用 [MIT License](LICENSE)。