# 泡泡刮刮乐

一个有趣的图片刮刮乐互动项目。上传图片后，一个黑色大泡泡覆盖住裁剪成圆形的图片，鼠标划过的地方泡泡不断分裂成密密麻麻的小泡泡，逐步还原出原图的色彩效果。

## 效果演示

- 上传图片 → 图片裁剪成圆形，被一个黑色大泡泡完全覆盖
- 鼠标划过 → 泡泡在划过的区域不断分裂（2×2 → 4×4 → 8×8 → ...）
- 每个泡泡取原图对应区域的平均色，分裂越细越接近原图
- 泡泡小到一定尺寸后自动淡出消失
- 右侧随机显示一句文案，每次刷新都不同

## 使用方式

直接打开 `scratch-card.html` 即可，无需任何依赖或服务器。

```bash
# 克隆仓库
git clone https://github.com/你的用户名/scratch-card.git

# 打开文件
open scratch-card.html        # macOS
start scratch-card.html       # Windows
xdg-open scratch-card.html    # Linux
```

## 技术栈

- 原生 HTML5 + CSS3 + JavaScript
- Canvas 2D 绘图
- 无任何第三方依赖

## 项目结构

```
scratch-card.html    # 单文件，包含所有代码
README.md            # 项目说明
```

## License

MIT
