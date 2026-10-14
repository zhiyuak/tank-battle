# 坦克大战 · Tank Battle

一个用纯 HTML + CSS + JavaScript 写成的经典坦克大战游戏，无需任何依赖，双击打开 `index.html` 即可游玩，也可以部署到 GitHub Pages。

## 🎮 玩法

- 使用 **WASD** 或 **方向键** 移动坦克
- 按 **空格键** 射击
- 消灭所有敌方坦克并**保护下方基地**（⭐ 鹰标志）
- 基地被摧毁则游戏结束

## ✨ 特性

- 经典风格关卡地图
- 可破坏砖墙、不可破坏钢墙、水面、树林掩护
- 敌人 AI（追踪玩家 + 随机移动 + 射击）
- 随关卡提升的敌人数量与强度（更快 / 更高护甲）
- 得分、关卡、生命值、剩余敌人 HUD
- 粒子爆炸特效与 Web Audio 音效
- 纯单文件实现，零依赖

## 🚀 运行

方式一：直接双击 `index.html` 用浏览器打开。

方式二：使用任意静态服务器，例如：

```bash
# Python
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 🛠 技术栈

- HTML5 Canvas
- 原生 JavaScript（ES6+）
- CSS3

## 📄 许可

MIT License
