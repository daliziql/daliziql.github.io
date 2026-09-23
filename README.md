# dalizi 的 Pages 首页

访问：<https://daliziql.github.io/>

按「技术、生活、学习、旅游」四个主题汇总个人公开的 GitHub Pages，包含内容说明、网页入口和对应仓库。首页支持通过主题导航跳转到对应分组。

| 主题 | 站点 | Pages | 仓库 |
| --- | --- | --- | --- |
| 技术 | Frameflow｜本地影像转场实验室 | [访问](https://daliziql.github.io/frameflow-studio/) | [frameflow-studio](https://github.com/daliziql/frameflow-studio) |
| 技术 | Zhouqili's Blog | [访问](https://daliziql.github.io/zhouqili.github.io/) | [zhouqili.github.io](https://github.com/daliziql/zhouqili.github.io) |
| 生活 | 身体维修之艺术 | [访问](https://daliziql.github.io/body-repair-art/) | [body-repair-art](https://github.com/daliziql/body-repair-art) |
| 学习 | 这破相机真难用 | [访问](https://daliziql.github.io/photography-light-lab/) | [photography-light-lab](https://github.com/daliziql/photography-light-lab) |
| 学习 | 光影机械｜摄影技术演化史 | [访问](https://daliziql.github.io/photography-technology-history/) | [photography-technology-history](https://github.com/daliziql/photography-technology-history) |
| 学习 | AI 时代的数学 | [访问](https://daliziql.github.io/mathematics-in-the-age-of-ai/) | [mathematics-in-the-age-of-ai](https://github.com/daliziql/mathematics-in-the-age-of-ai) |
| 旅游 | 哈哈哈哈萨克斯坦 | [访问](https://daliziql.github.io/almaty-aktau-2026/) | [almaty-aktau-2026](https://github.com/daliziql/almaty-aktau-2026) |

## 维护

这是无需构建、无需 JavaScript 的静态页面，由 GitHub Pages 发布 `main` 分支根目录。

增减站点时，编辑 `index.html` 中的目录条目，将条目放入对应主题分组，同时更新主题导航计数、分组计数、站点总数、页脚日期及本文件中的清单。仅收录允许公开展示的站点。

本地预览：

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```
