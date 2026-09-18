# Collision （赛博斗蛐蛐小游戏）

双人 P2P 实时对战小游戏（观战 + 主动干涉）

## 在线地址
https://ku-134.github.io/Kukuz-Game-Collision/

## 当前版本
- 我也不知道……

## 项目结构（组件模块化）
```
Collision/
├── index.html
├── css/style.css
└── js/
    ├── main.js          # 入口
    ├── config.js        # 全部数值配置
    ├── core/            # 物理/事件/主循环
    ├── entities/        # 球/状态效果
    ├── skills/          # 技能系统 + 职业定义
    ├── rendering/       # 渲染/摄像机/粒子
    ├── ui/              # 页面/HUD/输入
    ├── mode/            # 单机/联机模式
    └── ai/              # AI 对手
```
