# SoBooks - 标签

## Coverage
`index-only`

## Route
- Namespace: `sobooks`
- Namespace Name: `SoBooks`
- Route Path: `/sobooks/tag/:id?`
- Route Name: `标签`
- Example: `/sobooks/tag/小说`
- URL: `sobooks.cc`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
热门标签

| 小说 | 文学 | 历史 | 日本 | 科普 | 管理 | 推理 | 社会 | 经济   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |
| 传记 | 美国 | 悬疑 | 哲学 | 心理 | 商业 | 金融 | 思维 | 经典   |
| 随笔 | 投资 | 文化 | 励志 | 科幻 | 成长 | 中国 | 英国 | 政治   |
| 漫画 | 纪实 | 艺术 | 科学 | 生活 | 职场 | 散文 | 法国 | 互联网 |
| 营销 | 奇幻 | 二战 | 股票 | 女性 | 德国 | 学习 | 战争 | 创业   |
| 绘本 | 名著 | 爱情 | 军事 | 理财 | 教育 | 世界 | 人物 | 沟通   |

## Parameters
- `id`: 标签, 见下表，默认为小说


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sobooks.net/books/tag/:tag`
- `target`: `/tag/:tag`
### Rule 2
- `source`:
  - `sobooks.cc/books/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "热门标签\n\n| 小说 | 文学 | 历史 | 日本 | 科普 | 管理 | 推理 | 社会 | 经济   |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |\n| 传记 | 美国 | 悬疑 | 哲学 | 心理 | 商业 | 金融 | 思维 | 经典   |\n| 随笔 | 投资 | 文化 | 励志 | 科幻 | 成长 | 中国 | 英国 | 政治   |\n| 漫画 | 纪实 | 艺术 | 科学 | 生活 | 职场 | 散文 | 法国 | 互联网 |\n| 营销 | 奇幻 | 二战 | 股票 | 女性 | 德国 | 学习 | 战争 | 创业   |\n| 绘本 | 名著 | 爱情 | 军事 | 理财 | 教育 | 世界 | 人物 | 沟通   |",
  "example": "/sobooks/tag/小说",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "id": "标签, 见下表，默认为小说"
  },
  "path": "/tag/:id?",
  "radar": [
    {
      "source": [
        "sobooks.net/books/tag/:tag"
      ],
      "target": "/tag/:tag"
    },
    {
      "source": [
        "sobooks.cc/books/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-11T10:10:17.803Z",
      "errorMessage": "[GET] \"https://www.sobooks.net/books/tag/教育\": <no response> fetch failed (self-signed certificate; if the root CA is installed locally, try running Node.js with --use-system-ca)\n",
      "id": "177651896288583693",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://sobooks/tag/%E6%95%99%E8%82%B2"
    }
  ]
}
```
