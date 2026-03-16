# livestream-dashboard

直播产品数据监控看板原型。

当前版本聚焦 `LIVE` 口径，核心展示包括：

- `LIVE GMV`
- `LIVE items sold`
- `LIVE impressions`
- 不同生命周期的 `LIVE GMV` 占比
- 未匹配生命周期的直播产品

## Data Sources

页面目前读取两类 Excel 底表：

1. `直播数据底表`
2. `产品生命周期表`

直播底表支持在一个工作簿中读取多个工作表，并优先识别：

- `Sparco`
- `Letme`
- `Stypro`
- `Icyee`

## Run

这是一个纯前端页面，直接在浏览器中打开 `index.html` 即可使用。

如果后续需要部署到 GitHub Pages，仓库已经采用 `index.html` 作为入口文件。
