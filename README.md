# Up Series 70 Years / 《人生七年》时间线

中文：《人生七年》（Up Series）14 位主角从 7 岁到 70 岁的 63 年人生轨迹完整档案。包含全部 10 部纪录片纪事、人物卡片、横向阶级变迁对比与资料来源。纯静态原生网页，支持按标签即时筛选与详细时间线折叠浏览。

English: Comprehensive archive of the documentary Up Series tracing 14 lives across 63 years from age 7 to 70. Features timeline records across all 10 films, character profiles, comparative social mobility analysis, and tag-based filtering.

![Project screenshot](./assets/screenshot.png)

## 在线体验 / Live Demo

- [Cloudflare Demo](https://up-series-70years.xiaosang.cc/)
- [GitHub Repo](https://github.com/holynova/up-series-70years)

<img src="./assets/qr.png" width="180" alt="扫码访问 Cloudflare 在线体验">

## 本地运行 / Run locally

```bash
open index.html
```

## 发布 / Deploy

```bash
npx wrangler deploy --config wrangler.jsonc
```

Cloudflare Workers · Custom Domain: `up-series-70years.xiaosang.cc`

源码与部署配置使用同一个主分支；在本地手动发布，不创建 Cloudflare 专用分支或 GitHub Action。
