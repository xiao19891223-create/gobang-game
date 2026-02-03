# 五子棋游戏

一个简洁优雅的网页版五子棋游戏，支持双人对战。

![五子棋](https://img.shields.io/badge/游戏-五子棋-blue)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 在线体验

点击这里体验游戏：[gobang.html](https://xiao19891223-create.github.io/gobang-game/gobang.html)

## 游戏功能

- 15×15 标准棋盘
- 黑白双方轮流落子
- 自动判断胜负（五子连珠）
- 重新开始游戏
- 悔棋功能
- 落子计数显示

## 如何运行

### 方式一：直接打开
1. 下载 `gobang.html` 文件
2. 双击用浏览器打开即可

### 方式二：本地服务器
```bash
# 使用 Python
python -m http.server 8080

# 使用 Node.js
npx http-server
```

然后访问 `http://localhost:8080/gobang.html`

## 游戏规则

1. 黑方先行，双方轮流落子
2. 点击棋盘交叉点放置棋子
3. 先连成五子（横、竖、斜）的一方获胜
4. 可使用"悔棋"按钮撤销上一步
5. 可使用"重新开始"按钮开始新游戏

## 技术特点

- 纯 HTML/CSS/JavaScript 实现
- 无需任何依赖或框架
- 响应式设计
- 优雅的渐变背景和木纹棋盘
- 流畅的动画效果

## 截图

![游戏界面](screenshot.png)

## License

MIT License
