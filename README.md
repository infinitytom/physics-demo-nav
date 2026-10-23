# 物理演示开源导航

收录开源或开放许可的物理仿真、实验工具、开放教材、视频课和参考资料，按人教版 2019 高中物理六册章节索引。

## 文件

- `index.html`：整个页面。资源数据在文件中的 `RESOURCES` 数组，章节直达在 `BOOKS` 数组
- `assets/alipay.png`：赞赏码

## 增加资源

在 `RESOURCES` 里加一条：

```js
{name:"名称",kind:"仿真演示",en:"英文名/作者",url:"https://…",tier:"open|cc|free",
 license:"许可说明",lang:"语言",offline:"离线情况",desc:"一句话介绍",topics:["力学"]}
```

`kind` 可选：仿真演示、实验工具、建模编程、教材课程、视频、参考资料、图片素材。
`topics` 可选：力学、振动与波、电磁学、光学、热学、近代物理、综合。

## 部署

仓库 Settings → Pages → Deploy from a branch → `main` / `(root)`。
