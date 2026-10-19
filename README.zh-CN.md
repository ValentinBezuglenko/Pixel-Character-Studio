# Pixel Character Studio

[English](README.md) · [Русский](README.ru.md) · [Español](README.es.md) · [中文](README.zh-CN.md)

一个独立运行于浏览器的 16×16 像素角色与逐帧精灵动画编辑器。它可以完全在本地运行，无需账户或服务器，也不与任何游戏绑定。

## 功能

- 带网格、橡皮擦、撤销和重做功能的 16×16 像素编辑器
- 创建、复制、删除及重新排序精灵和动画帧
- 可调帧时长，以及 1×、2×、4×、8×、10× 动画预览
- 半透明显示上一帧
- 内置调色板和自定义颜色
- 精灵搜索和分组
- 自动本地保存，并保留最多五个手动版本
- 使用 JSON 导入和导出项目
- 导入 16×16 PNG，并将当前帧导出为 PNG
- 导出包含 PNG 精灵表和 JSON 图集的 ZIP
- 支持英语、西班牙语、俄语和简体中文界面
- 三个可编辑的角色动画示例

## 本地运行

无需构建。下载仓库后，使用现代浏览器打开 `index.html` 即可。

也可以在项目目录中运行以下任一命令来启动本地服务器：

```bash
python -m http.server 8000
```

```bash
npx serve .
```

然后打开 `http://localhost:8000` 或服务器显示的地址。

## 使用 GitHub Pages 发布

1. 将项目推送到 GitHub。
2. 在仓库中打开 **Settings → Pages**。
3. 选择 **Deploy from a branch**。
4. 选择 `main` 分支和 `/ (root)` 目录。

项目保存在浏览器的 `localStorage` 中。若要在不同浏览器或电脑之间迁移，请导出项目 JSON 文件。

## 第三方示例

内置示例的作者及使用条款记录在 [THIRD_PARTY_ASSETS.md](THIRD_PARTY_ASSETS.md) 中。

## 项目许可证

编辑器源代码尚未选择许可证。在接受外部贡献或授予复用权之前，请先添加 `LICENSE` 文件。
