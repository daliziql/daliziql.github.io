# dalizi 的 Pages 首页

访问：<https://daliziql.github.io/>

默认按首次发布日期从新到旧展示全部文章与工具。通过「全部、技术、学习、旅游」标签即时过滤；空分类自动隐藏。「身体维修之艺术」属于学习，生活分类暂不显示。

| 首次发布日期 | 主题 | 站点 | Pages | 仓库 |
| --- | --- | --- | --- | --- |
| 2026-09-21 | 学习 | 身体维修之艺术 | [访问](https://daliziql.github.io/body-repair-art/) | [body-repair-art](https://github.com/daliziql/body-repair-art) |
| 2026-09-08 | 学习 | AI 时代的数学 | [访问](https://daliziql.github.io/mathematics-in-the-age-of-ai/) | [mathematics-in-the-age-of-ai](https://github.com/daliziql/mathematics-in-the-age-of-ai) |
| 2026-09-07 | 学习 | 这破相机真难用 | [访问](https://daliziql.github.io/photography-light-lab/) | [photography-light-lab](https://github.com/daliziql/photography-light-lab) |
| 2026-09-01 | 旅游 | 哈哈哈哈萨克斯坦 | [访问](https://daliziql.github.io/almaty-aktau-2026/) | [almaty-aktau-2026](https://github.com/daliziql/almaty-aktau-2026) |
| 2026-08-13 | 技术 | Frameflow｜本地影像转场实验室 | [访问](https://daliziql.github.io/frameflow-studio/) | [frameflow-studio](https://github.com/daliziql/frameflow-studio) |
| 2026-08-12 | 学习 | 光影机械｜摄影技术演化史 | [访问](https://daliziql.github.io/photography-technology-history/) | [photography-technology-history](https://github.com/daliziql/photography-technology-history) |
| 2020-12-06 | 技术 | Zhouqili's Blog | [访问](https://daliziql.github.io/zhouqili.github.io/) | [zhouqili.github.io](https://github.com/daliziql/zhouqili.github.io) |

## 发布日期依据

日期按北京时间记录。按 GitHub 当前可查询的最早成功 Pages 发布记录排序，不使用最近提交或最近更新时间。博客入口按整个站点的首次发布日排序。

- `body-repair-art`、`mathematics-in-the-age-of-ai`、`photography-light-lab`、`almaty-aktau-2026`、`zhouqili.github.io`：各仓库 `/pages/builds` 中最早的 `status=built` 记录。
- `frameflow-studio`：`github-pages` 部署 `5889128872`，成功时间 `2026-08-13T13:40:46Z`。
- `photography-technology-history`：`github-pages` 部署 `5867044934`，成功时间 `2026-08-12T09:57:00Z`。
- 核对日期：2026-09-23。

## 维护

无需构建或外部依赖，由 GitHub Pages 发布 `main` 分支根目录。完整内容直接写在 HTML 中，关闭 JavaScript 仍可阅读全部内容；少量原生 JavaScript 负责排序、分类过滤和计数。

增减条目时，编辑 `index.html` 的 `#article-list`，填写 `data-topic`（`technology`、`life`、`learning`、`travel`）与 `data-published`（`YYYY-MM-DD`），同步修改可见标签和 `<time>`，并保持 HTML 本身按日期降序排列。筛选计数自动计算，空分类自动隐藏。加入生活内容后，生活筛选标签会自动出现。

同步更新静态总数、无脚本状态下的内容数量、页脚日期及本文件清单。仅收录允许公开展示的内容。

本地预览：

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```
