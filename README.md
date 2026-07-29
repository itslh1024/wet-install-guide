# 湿贴法 / Wet Install Method

> 在线访问：https://itslh1024.github.io/wet-install-guide/

## 关于这个项目

一个解释"为什么贴膜要喷皂水"的单页交互指南，覆盖原理、操作步骤、常见误区。

## 文件说明

| 文件 | 用途 |
|---|---|
| `index.html` | 完整交互页面（自包含，无外部依赖） |
| `README.md` | 本说明文件 |

## 本地预览

直接双击 `index.html` 用浏览器打开即可，无构建步骤。

如需起一个本地静态服务器：

```bash
# Python 3
python3 -m http.server 8000

# 然后访问 http://localhost:8000
```

## 更新部署

修改 `index.html` 后：

```bash
cd /Users/mbp-cl/Documents/wet-install-guide
git add .
git commit -m "Update content"
git push origin main
```

GitHub Pages 会自动重新构建并生效（通常 30 秒内）。

## 数据来源

原始文件：`/Users/mbp-cl/Downloads/wet_install_guide.html`（2026-07-27 创作）

---

📌 **在线地址：** https://itslh1024.github.io/wet-install-guide/