# 第一财经 - DT 财经

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/yicai/dt/:column?/:category?`
- Route Name: `DT 财经`
- Example: `/yicai/dt/article`
- URL: `yicai.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `dt.ts`
- Source Module: `_None_`

## Description
#### [文章](https://dt.yicai.com/article)

| 分类     | ID         |
| -------- | ---------- |
| 全部     | article/0  |
| 新流行   | article/31 |
| 新趋势   | article/32 |
| 商业黑马 | article/33 |
| 新品     | article/34 |
| 营销     | article/35 |
| 大公司   | article/36 |
| 城市生活 | article/38 |

#### [报告](https://dt.yicai.com/report)

| 分类       | ID        |
| ---------- | --------- |
| 全部       | report/0  |
| 人群观念   | report/9  |
| 人群行为   | report/22 |
| 美妆个护   | report/23 |
| 3C 数码    | report/24 |
| 营销趋势   | report/25 |
| 服饰鞋包   | report/27 |
| 互联网     | report/28 |
| 城市与居住 | report/29 |
| 消费趋势   | report/30 |
| 生活趋势   | report/37 |

#### [可视化](https://dt.yicai.com/visualization)

| 分类     | ID               |
| -------- | ---------------- |
| 全部     | visualization/0  |
| 新流行   | visualization/39 |
| 新趋势   | visualization/40 |
| 商业黑马 | visualization/41 |
| 新品     | visualization/42 |
| 营销     | visualization/43 |
| 大公司   | visualization/44 |
| 城市生活 | visualization/45 |

## Parameters
- `column`: 栏目，见下表，默认为文章
- `category`: 分类，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "#### [文章](https://dt.yicai.com/article)\n\n| 分类     | ID         |\n| -------- | ---------- |\n| 全部     | article/0  |\n| 新流行   | article/31 |\n| 新趋势   | article/32 |\n| 商业黑马 | article/33 |\n| 新品     | article/34 |\n| 营销     | article/35 |\n| 大公司   | article/36 |\n| 城市生活 | article/38 |\n\n#### [报告](https://dt.yicai.com/report)\n\n| 分类       | ID        |\n| ---------- | --------- |\n| 全部       | report/0  |\n| 人群观念   | report/9  |\n| 人群行为   | report/22 |\n| 美妆个护   | report/23 |\n| 3C 数码    | report/24 |\n| 营销趋势   | report/25 |\n| 服饰鞋包   | report/27 |\n| 互联网     | report/28 |\n| 城市与居住 | report/29 |\n| 消费趋势   | report/30 |\n| 生活趋势   | report/37 |\n\n#### [可视化](https://dt.yicai.com/visualization)\n\n| 分类     | ID               |\n| -------- | ---------------- |\n| 全部     | visualization/0  |\n| 新流行   | visualization/39 |\n| 新趋势   | visualization/40 |\n| 商业黑马 | visualization/41 |\n| 新品     | visualization/42 |\n| 营销     | visualization/43 |\n| 大公司   | visualization/44 |\n| 城市生活 | visualization/45 |",
  "example": "/yicai/dt/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 39,
  "location": "dt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "DT 财经",
  "parameters": {
    "category": "分类，见下表，默认为全部",
    "column": "栏目，见下表，默认为文章"
  },
  "path": "/dt/:column?/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "用数据度量商业 让数据自由跨界 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63944281636561920",
      "image": "data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iNjZweCIgaGVpZ2h0PSIzNHB4IiB2aWV3Qm94PSIwIDAgNjYgMzQiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayI+CiAgICA8IS0tIEdlbmVyYXRvcjogU2tldGNoIDYzICg5MjQ0NSkgLSBodHRwczovL3NrZXRjaC5jb20gLS0+CiAgICA8dGl0bGU+57yW57uEPC90aXRsZT4KICAgIDxkZXNjPkNyZWF0ZWQgd2l0aCBTa2V0Y2guPC9kZXNjPgogICAgPGRlZnM+CiAgICAgICAgPHBvbHlnb24gaWQ9InBhdGgtMSIgcG9pbnRzPSIwIDAgMzIuOTAyOTA5NyAwIDMyLjkwMjkwOTcgMzIuOTk5NTMwNCAwIDMyLjk5OTUzMDQiPjwvcG9seWdvbj4KICAgIDwvZGVmcz4KICAgIDxnIGlkPSLpobXpnaItMSIgc3Ryb2tlPSJub25lIiBzdHJva2Utd2lkdGg9IjEiIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+CiAgICAgICAgPGcgaWQ9IuaWh+eroOWkh+S7vSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTkyNy4wMDAwMDAsIC0yMi4wMDAwMDApIj4KICAgICAgICAgICAgPGcgaWQ9Iue8lue7hCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTI3LjE5NDc1NywgMjIuMzk1NzA2KSI+CiAgICAgICAgICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwgMC4wMDA0NzApIj4KICAgICAgICAgICAgICAgICAgICA8bWFzayBpZD0ibWFzay0yIiBmaWxsPSJ3aGl0ZSI+CiAgICAgICAgICAgICAgICAgICAgICAgIDx1c2UgeGxpbms6aHJlZj0iI3BhdGgtMSI+PC91c2U+CiAgICAgICAgICAgICAgICAgICAgPC9tYXNrPgogICAgICAgICAgICAgICAgICAgIDxnIGlkPSJDbGlwLTIiPjwvZz4KICAgICAgICAgICAgICAgICAgICA8cGF0aCBkPSJNMzAuMDg4ODU2OCwzLjA2MTY0MjY3IEMyOC44NDIxMjk2LDEuODc4MzA4MzggMjcuMjE1MDQ1LDEuMDY0NzY2MDcgMjUuMjUxMDM4OCwwLjY0NDQ5NDU2NCBDMjMuMjU2NTEsMC4yMTcxNzk0MDcgMjAuOTM3OTczMSwwIDE4LjM2MzUxNjcsMCBMNS4zMDQ1Nzc2NywwIEw0LjEwODMzMDAxLDcuNDYxNTgwMDYgTDE2LjQ3MzQ2ODksNy40NjE1ODAwNiBDMTcuODk4NjM1NCw3LjQ2MTU4MDA2IDE5LjA4MTk2OTcsNy41OTU0MDk1MyAxOS45OTc2NDUsNy44NjA3MjA1OSBDMjAuOTUzMjM0NCw4LjEzNjU5NzEzIDIxLjY4OTI5NjUsOC42Mjk2NTMwOCAyMi4xODkzOTYxLDkuMzI0NjI3MTggQzIyLjY4MjQ1MiwxMC4wMTAyMDk3IDIyLjk2MDY3NjUsMTAuOTYzNDUxMiAyMy4wMTM1MDM5LDEyLjE1NjE3NzEgQzIzLjA2MTYzNTYsMTMuMzI4OTQ1OSAyMi45NDQyNDEzLDE0LjgwMzQxOCAyMi42NjEzMjExLDE2LjU0MDg1MzIgQzIyLjM5NjAxLDE4LjIxNDg5NTYgMjIuMDU5MDg4NSwxOS42MzA2NzA1IDIxLjY1NzYsMjAuNzUwNjExOSBDMjEuMjUzNzYzNywyMS44Nzk5NDQ4IDIwLjcwMzE4NDYsMjIuODAxNDg5OCAyMC4wMTk5NDk5LDIzLjQ5MDU5NDIgQzE5LjMyNDk3NTgsMjQuMTg2NzQyMyAxOC40NDY4NjY2LDI0LjY3NjI3NjQgMTcuNDEwMjc1MiwyNC45NDYyODMyIEMxNi4zOTgzMzY2LDI1LjIwOTI0NjQgMTUuMTQ4MDg3NSwyNS4zNDMwNzU5IDEzLjY5MjM5ODUsMjUuMzQzMDc1OSBMMTAuNjAyNTgxMywyNS4zNDMwNzU5IEwxMi43Mzc5ODMxLDEyLjkyODYzMTQgTDMuMjUwMTc3ODcsMTIuOTI4NjMxNCBMMC4wNTcwNTM2MTcyLDMyLjY3MDgyNjUgTC0wLjAwMDQ2OTU3NzA5NiwzMi45OTk1MzA0IEwxMi45NzE1OTc3LDMyLjk5OTUzMDQgQzE1LjU0MDE4NDQsMzIuOTk5NTMwNCAxNy45MzI2Nzk3LDMyLjczNDIxOTQgMjAuMDgyMTY4OSwzMi4yMTA2NDA5IEMyMi4yMjEwOTI1LDMxLjY5MDU4NDMgMjQuMTQxNjYyOSwzMC43ODc4MjIzIDI1Ljc5MTA1MjQsMjkuNTI5MzU1NyBDMjcuNDQxNjE1OSwyOC4yNzQ0MTA5IDI4Ljg0NTY1MTQsMjYuNTcxMDIgMjkuOTY5MTE0NiwyNC40Njk2NjI1IEMzMS4wOTE0MDM5LDIyLjM3MDY1MjkgMzEuOTIzNzI5MywxOS42NzI5MzI0IDMyLjQ0MTQzOCwxNi40NTM5ODE0IEMzMi45OTQzNjUxLDEzLjAyMTM3MjkgMzMuMDQ5NTQwNCwxMC4xOTA5OTY5IDMyLjYxMTY1OTcsOC4wNDE1MDc3NyBDMzIuMTc3MzAwOSw1LjkyMDE5MzI0IDMxLjMyOTcxNDMsNC4yNDM4MDMwMSAzMC4wODg4NTY4LDMuMDYxNjQyNjciIGlkPSJGaWxsLTEiIGZpbGw9IiMyMTZDRjciIG1hc2s9InVybCgjbWFzay0yKSI+PC9wYXRoPgogICAgICAgICAgICAgICAgPC9nPgogICAgICAgICAgICAgICAgPHBvbHlnb24gaWQ9IkZpbGwtMyIgZmlsbD0iIzIxNkNGNyIgcG9pbnRzPSIzMi44MzQwMDQ1IDAgMzYuMzYwNTI4NSA3Ljg0ODk4MTE2IDQ0LjQyNjY4OTEgNy44NDg5ODExNiA0MC4zODk1IDMyLjk5OTUzMDQgNDkuNzAyMzg3NyAzMi45OTk1MzA0IDUzLjc0NDI3MjYgNy44NDg5ODExNiA2Mi4xNDk3MDI2IDcuODQ4OTgxMTYgNjUuNjEwNDg1OCAwIj48L3BvbHlnb24+CiAgICAgICAgICAgIDwvZz4KICAgICAgICA8L2c+CiAgICA8L2c+Cjwvc3ZnPg==",
      "ownerUserId": null,
      "siteUrl": "https://dt.yicai.com/article",
      "title": "全部文章 | DT商业观察",
      "type": "feed",
      "url": "rsshub://yicai/dt/article"
    },
    {
      "description": "用数据度量商业 让数据自由跨界 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84474888108006400",
      "image": "data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iNjZweCIgaGVpZ2h0PSIzNHB4IiB2aWV3Qm94PSIwIDAgNjYgMzQiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayI+CiAgICA8IS0tIEdlbmVyYXRvcjogU2tldGNoIDYzICg5MjQ0NSkgLSBodHRwczovL3NrZXRjaC5jb20gLS0+CiAgICA8dGl0bGU+57yW57uEPC90aXRsZT4KICAgIDxkZXNjPkNyZWF0ZWQgd2l0aCBTa2V0Y2guPC9kZXNjPgogICAgPGRlZnM+CiAgICAgICAgPHBvbHlnb24gaWQ9InBhdGgtMSIgcG9pbnRzPSIwIDAgMzIuOTAyOTA5NyAwIDMyLjkwMjkwOTcgMzIuOTk5NTMwNCAwIDMyLjk5OTUzMDQiPjwvcG9seWdvbj4KICAgIDwvZGVmcz4KICAgIDxnIGlkPSLpobXpnaItMSIgc3Ryb2tlPSJub25lIiBzdHJva2Utd2lkdGg9IjEiIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+CiAgICAgICAgPGcgaWQ9IuaWh+eroOWkh+S7vSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTkyNy4wMDAwMDAsIC0yMi4wMDAwMDApIj4KICAgICAgICAgICAgPGcgaWQ9Iue8lue7hCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTI3LjE5NDc1NywgMjIuMzk1NzA2KSI+CiAgICAgICAgICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwgMC4wMDA0NzApIj4KICAgICAgICAgICAgICAgICAgICA8bWFzayBpZD0ibWFzay0yIiBmaWxsPSJ3aGl0ZSI+CiAgICAgICAgICAgICAgICAgICAgICAgIDx1c2UgeGxpbms6aHJlZj0iI3BhdGgtMSI+PC91c2U+CiAgICAgICAgICAgICAgICAgICAgPC9tYXNrPgogICAgICAgICAgICAgICAgICAgIDxnIGlkPSJDbGlwLTIiPjwvZz4KICAgICAgICAgICAgICAgICAgICA8cGF0aCBkPSJNMzAuMDg4ODU2OCwzLjA2MTY0MjY3IEMyOC44NDIxMjk2LDEuODc4MzA4MzggMjcuMjE1MDQ1LDEuMDY0NzY2MDcgMjUuMjUxMDM4OCwwLjY0NDQ5NDU2NCBDMjMuMjU2NTEsMC4yMTcxNzk0MDcgMjAuOTM3OTczMSwwIDE4LjM2MzUxNjcsMCBMNS4zMDQ1Nzc2NywwIEw0LjEwODMzMDAxLDcuNDYxNTgwMDYgTDE2LjQ3MzQ2ODksNy40NjE1ODAwNiBDMTcuODk4NjM1NCw3LjQ2MTU4MDA2IDE5LjA4MTk2OTcsNy41OTU0MDk1MyAxOS45OTc2NDUsNy44NjA3MjA1OSBDMjAuOTUzMjM0NCw4LjEzNjU5NzEzIDIxLjY4OTI5NjUsOC42Mjk2NTMwOCAyMi4xODkzOTYxLDkuMzI0NjI3MTggQzIyLjY4MjQ1MiwxMC4wMTAyMDk3IDIyLjk2MDY3NjUsMTAuOTYzNDUxMiAyMy4wMTM1MDM5LDEyLjE1NjE3NzEgQzIzLjA2MTYzNTYsMTMuMzI4OTQ1OSAyMi45NDQyNDEzLDE0LjgwMzQxOCAyMi42NjEzMjExLDE2LjU0MDg1MzIgQzIyLjM5NjAxLDE4LjIxNDg5NTYgMjIuMDU5MDg4NSwxOS42MzA2NzA1IDIxLjY1NzYsMjAuNzUwNjExOSBDMjEuMjUzNzYzNywyMS44Nzk5NDQ4IDIwLjcwMzE4NDYsMjIuODAxNDg5OCAyMC4wMTk5NDk5LDIzLjQ5MDU5NDIgQzE5LjMyNDk3NTgsMjQuMTg2NzQyMyAxOC40NDY4NjY2LDI0LjY3NjI3NjQgMTcuNDEwMjc1MiwyNC45NDYyODMyIEMxNi4zOTgzMzY2LDI1LjIwOTI0NjQgMTUuMTQ4MDg3NSwyNS4zNDMwNzU5IDEzLjY5MjM5ODUsMjUuMzQzMDc1OSBMMTAuNjAyNTgxMywyNS4zNDMwNzU5IEwxMi43Mzc5ODMxLDEyLjkyODYzMTQgTDMuMjUwMTc3ODcsMTIuOTI4NjMxNCBMMC4wNTcwNTM2MTcyLDMyLjY3MDgyNjUgTC0wLjAwMDQ2OTU3NzA5NiwzMi45OTk1MzA0IEwxMi45NzE1OTc3LDMyLjk5OTUzMDQgQzE1LjU0MDE4NDQsMzIuOTk5NTMwNCAxNy45MzI2Nzk3LDMyLjczNDIxOTQgMjAuMDgyMTY4OSwzMi4yMTA2NDA5IEMyMi4yMjEwOTI1LDMxLjY5MDU4NDMgMjQuMTQxNjYyOSwzMC43ODc4MjIzIDI1Ljc5MTA1MjQsMjkuNTI5MzU1NyBDMjcuNDQxNjE1OSwyOC4yNzQ0MTA5IDI4Ljg0NTY1MTQsMjYuNTcxMDIgMjkuOTY5MTE0NiwyNC40Njk2NjI1IEMzMS4wOTE0MDM5LDIyLjM3MDY1MjkgMzEuOTIzNzI5MywxOS42NzI5MzI0IDMyLjQ0MTQzOCwxNi40NTM5ODE0IEMzMi45OTQzNjUxLDEzLjAyMTM3MjkgMzMuMDQ5NTQwNCwxMC4xOTA5OTY5IDMyLjYxMTY1OTcsOC4wNDE1MDc3NyBDMzIuMTc3MzAwOSw1LjkyMDE5MzI0IDMxLjMyOTcxNDMsNC4yNDM4MDMwMSAzMC4wODg4NTY4LDMuMDYxNjQyNjciIGlkPSJGaWxsLTEiIGZpbGw9IiMyMTZDRjciIG1hc2s9InVybCgjbWFzay0yKSI+PC9wYXRoPgogICAgICAgICAgICAgICAgPC9nPgogICAgICAgICAgICAgICAgPHBvbHlnb24gaWQ9IkZpbGwtMyIgZmlsbD0iIzIxNkNGNyIgcG9pbnRzPSIzMi44MzQwMDQ1IDAgMzYuMzYwNTI4NSA3Ljg0ODk4MTE2IDQ0LjQyNjY4OTEgNy44NDg5ODExNiA0MC4zODk1IDMyLjk5OTUzMDQgNDkuNzAyMzg3NyAzMi45OTk1MzA0IDUzLjc0NDI3MjYgNy44NDg5ODExNiA2Mi4xNDk3MDI2IDcuODQ4OTgxMTYgNjUuNjEwNDg1OCAwIj48L3BvbHlnb24+CiAgICAgICAgICAgIDwvZz4KICAgICAgICA8L2c+CiAgICA8L2c+Cjwvc3ZnPg==",
      "ownerUserId": null,
      "siteUrl": "https://dt.yicai.com/article",
      "title": "全部文章 | DT商业观察",
      "type": "feed",
      "url": "rsshub://yicai/dt"
    }
  ]
}
```
