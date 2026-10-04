# zero-to-tech

从零开始的 Web 学习笔记。目前是一个最小可运行的静态页面，用来练手 HTML / CSS / JavaScript 三件套，以及 Git 的基本流程。

## 当前内容

| 文件 | 作用 |
| --- | --- |
| `index.html` | 页面结构：一张卡片，标题、一段文字、一个按钮 |
| `style.css` | 样式：居中布局、卡片阴影、按钮悬停效果 |
| `script.js` | 行为：`changeText()` 点击按钮后替换段落文字 |

三个文件的分工就是前端最基础的那条分界线：结构、表现、行为分开写。

## 本地预览

直接用浏览器打开 `index.html` 即可：

```bash
# Linux / WSL
xdg-open index.html
```

如果想模拟真实的 HTTP 环境（后面涉及 `fetch`、模块化脚本时会用到），起一个本地服务器：

```bash
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## Git 常用命令

```bash
git status              # 看看改了什么
git add .               # 把改动放进暂存区
git commit -m "说明"     # 提交
git log --oneline       # 回看历史
```
