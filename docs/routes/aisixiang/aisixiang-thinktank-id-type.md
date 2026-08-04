# 爱思想 - 思想库（专栏）

## Coverage
`index-only`

## Route
- Namespace: `aisixiang`
- Namespace Name: `爱思想`
- Route Path: `/aisixiang/thinktank/:id/:type?`
- Route Name: `思想库（专栏）`
- Example: `/aisixiang/thinktank/WuQine/论文`
- URL: `aisixiang.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `hoilc, nczitzk`
- Source Location: `thinktank.ts`
- Source Module: `_None_`

## Description
| 论文 | 时评 | 随笔 | 演讲 | 访谈 | 著作 | 读书 | 史论 | 译作 | 诗歌 | 书信 | 科学 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `id`: 专栏 ID，一般为作者拼音，可在URL中找到
- `type`: 栏目类型，参考下表，默认为全部


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
    "reading"
  ],
  "description": "| 论文 | 时评 | 随笔 | 演讲 | 访谈 | 著作 | 读书 | 史论 | 译作 | 诗歌 | 书信 | 科学 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/aisixiang/thinktank/WuQine/论文",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 203,
  "location": "thinktank.ts",
  "maintainers": [
    "hoilc",
    "nczitzk"
  ],
  "name": "思想库（专栏）",
  "parameters": {
    "id": "专栏 ID，一般为作者拼音，可在URL中找到",
    "type": "栏目类型，参考下表，默认为全部"
  },
  "path": "/thinktank/:id/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "陈嘉映，1952年出生于上海。宾夕法尼亚州立大学博士。曾任教于北京大学、华东师范大学，现为首都师范大学哲学系特聘教授，外国哲学学科专业负责人。主要研究领域为分析哲学、现象学和科学哲学。著有《海德格尔哲学概论》、《语言哲学》、《思远道》、《泠风集》、《哲学 科学 常识》等。（<a href=\"http://www.aisixiang.com/data/detail.php?id=22792\" target=\"_blank\"><font color=#990033><u>陈嘉映简介</u></font></a>） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98011535417850905",
      "image": "https://oss.aisixiang.com/images/logo_thinktank.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/thinktank/chenjiaying.html",
      "title": "爱思想 - 陈嘉映",
      "type": "feed",
      "url": "rsshub://aisixiang/thinktank/chenjiaying"
    },
    {
      "description": "秦晖，1953年12月生，清华大学人文社会科学学院教授。1981年作为中国文革后首批硕士毕业于兰州大学(研究生)，曾任陕西师范大学教授(1992年起)、中国农村发展信托投资公司研究员(1994年)，现为中国经济史学会理事、中国农民史研究会理事。中国青少年发展基金会理事、青基会社区文化委员会委员、研究委员会委员、北京天则经济研究所特邀研究员、《方法》、《开放时代》、《中国学术》和《中国社会科学季刊》等学术刊物的编委。(<a href=\"http://www.aisixiang.com/data/detail.php?id=18368\" target=\"_blank\"><u>秦晖学术简历</u></a>) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55135298544042022",
      "image": "https://oss.aisixiang.com/images/logo_thinktank.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/thinktank/qinhui.html",
      "title": "爱思想 - 秦晖",
      "type": "feed",
      "url": "rsshub://aisixiang/thinktank/qinhui"
    }
  ]
}
```
