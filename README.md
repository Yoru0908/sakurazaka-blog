# sakurazaka-blog

> 樱坂46 官方博客翻译存档

本仓库由 `sakamichi-blog-backend` 自动抓取并翻译樱坂46 官方博客后，将双语 Markdown 内容写入此仓库。

## 目录结构

```
content/posts/<YYYY>/<MM>/sakurazaka46/<YYYY-MM-DD>-<标题>-sakurazaka-<ID>.md
```

每篇博文为一个 Markdown 文件，文件名包含日期、标题及原始博客 ID。

## 数据来源

- 官方博客：https://www.sakurazaka46.com/s/s46/diary/MEMBER/list
- 抓取与翻译后端：[sakamichi-blog-backend](https://github.com/Yoru0908/sakamichi-blog-backend)
- 前端展示：[sakamichi-platform](https://github.com/Yoru0908/sakamichi-platform)（`/blog` 路由）

## 更新机制

博客后端定时抓取新博客 → 翻译 → 生成 Markdown → commit & push 到本仓库。前端通过 API 读取最新内容。
