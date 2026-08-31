# 连享会 - 精彩资讯

## Coverage
`index-only`

## Route
- Namespace: `lianxh`
- Namespace Name: `连享会`
- Route Path: `/lianxh/:category?`
- Route Name: `精彩资讯`
- Example: `/lianxh`
- URL: `www.lianxh.cn/`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 分类                 | id  |
| -------------------- | --- |
| 全部                 | all |
| Stata 入门           | 16  |
| Stata 教程           | 17  |
| 计量专题             | 18  |
| 内生性 - 因果推断    | 19  |
| 面板数据             | 20  |
| 交乘项 - 调节 - 中介 | 21  |
| 结果输出             | 22  |
| 工具软件             | 23  |
| Stata 绘图           | 24  |
| 数据处理             | 25  |
| Stata 程序           | 26  |
| Probit-Logit         | 27  |
| 时间序列             | 28  |
| 空间计量 - 网络分析  | 29  |
| Markdown-LaTeX       | 30  |
| 论文写作             | 31  |
| 回归分析             | 32  |
| 其它                 | 33  |
| 数据分享             | 34  |
| Stata 资源           | 35  |
| 文本分析 - 爬虫      | 36  |
| Python-R-Matlab      | 37  |
| IV-GMM               | 38  |
| 倍分法 DID           | 39  |
| 断点回归 RDD         | 40  |
| PSM-Matching         | 41  |
| 合成控制法           | 42  |
| Stata 命令           | 43  |
| 专题课程             | 44  |
| 风险管理             | 45  |
| 生存分析             | 46  |
| 机器学习             | 47  |
| 分位数回归           | 48  |
| SFA-DEA - 效率分析   | 49  |
| 答疑 - 板书          | 50  |
| 论文重现             | 51  |
| 最新课程             | 52  |
| 公开课               | 53  |

## Parameters
- `category`: 分类 id，可在对应分类页 URL 中找到，默认为 `all`，即全部


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.lianxh.cn/blogs/all.html`
  - `www.lianxh.cn/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 分类                 | id  |\n| -------------------- | --- |\n| 全部                 | all |\n| Stata 入门           | 16  |\n| Stata 教程           | 17  |\n| 计量专题             | 18  |\n| 内生性 - 因果推断    | 19  |\n| 面板数据             | 20  |\n| 交乘项 - 调节 - 中介 | 21  |\n| 结果输出             | 22  |\n| 工具软件             | 23  |\n| Stata 绘图           | 24  |\n| 数据处理             | 25  |\n| Stata 程序           | 26  |\n| Probit-Logit         | 27  |\n| 时间序列             | 28  |\n| 空间计量 - 网络分析  | 29  |\n| Markdown-LaTeX       | 30  |\n| 论文写作             | 31  |\n| 回归分析             | 32  |\n| 其它                 | 33  |\n| 数据分享             | 34  |\n| Stata 资源           | 35  |\n| 文本分析 - 爬虫      | 36  |\n| Python-R-Matlab      | 37  |\n| IV-GMM               | 38  |\n| 倍分法 DID           | 39  |\n| 断点回归 RDD         | 40  |\n| PSM-Matching         | 41  |\n| 合成控制法           | 42  |\n| Stata 命令           | 43  |\n| 专题课程             | 44  |\n| 风险管理             | 45  |\n| 生存分析             | 46  |\n| 机器学习             | 47  |\n| 分位数回归           | 48  |\n| SFA-DEA - 效率分析   | 49  |\n| 答疑 - 板书          | 50  |\n| 论文重现             | 51  |\n| 最新课程             | 52  |\n| 公开课               | 53  |",
  "example": "/lianxh",
  "heat": 23,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "精彩资讯",
  "parameters": {
    "category": "分类 id，可在对应分类页 URL 中找到，默认为 `all`，即全部"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.lianxh.cn/blogs/all.html",
        "www.lianxh.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -9152227372 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "连享会 - 全部专题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71511658456989696",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lianxh.cn/blogs/all.html",
      "title": "连享会 - 全部专题",
      "type": "feed",
      "url": "rsshub://lianxh"
    }
  ],
  "url": "www.lianxh.cn/"
}
```
