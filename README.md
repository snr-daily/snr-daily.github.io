# snr_daily

每日 AI 技术动态博客：https://snr-daily.github.io/

文章由私有底稿仓库自动渲染生成，请勿直接修改 `_posts/`。

## 工作入口

- 私有底稿仓库：同级目录 `../snr_daily_content`。
- 日报生成规范：`../snr_daily_content/prompts/daily.md`。
- 底稿格式与渠道命令：`../snr_daily_content/README.md`。
- 迁移梳理与运行检查：`../snr_daily_content/docs/handover.md`（仅本地私有仓库可读）。
- 本仓库的 Agent 工作说明：[`AGENTS.md`](AGENTS.md)。

## 本仓库的职责

`_posts/` 和 `assets/figures/` 是生成产物；内容更正应先修改私有底稿，再重新渲染。
`_config.yml`、`index.md`、`about.md` 和 `assets/main.scss` 管理博客配置与展示。
微信公众号的排版、凭据调用和草稿记录均由私有仓库管理。

本仓库不包含新闻检索、自动写稿或定时任务程序。切换 AI 订阅本身不能确认原定时任务已经迁移。
