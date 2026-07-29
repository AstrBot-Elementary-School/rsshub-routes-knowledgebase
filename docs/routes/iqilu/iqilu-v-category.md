# 齐鲁网 - 电视节目

## Coverage
`index-only`

## Route
- Namespace: `iqilu`
- Namespace Name: `齐鲁网`
- Route Path: `/iqilu/v/:category{.+}?`
- Route Name: `电视节目`
- Example: `/iqilu/v/sdws/sdxwlb`
- URL: `v.iqilu.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `program.ts`
- Source Module: `_None_`

## Description
| 节目名称         | 节目 id        |
| ---------------- | -------------- |
| 山东新闻联播     | sdws/sdxwlb    |
| 闪电大视野       | ggpd/sddsy     |
| 山东三农新闻联播 | nkpd/snxw      |
| 每日新闻         | qlpd/mrxw      |
| 新闻午班车       | ggpd/xwwbc     |
| 戏宇宙           | sdws/xyz/      |
| 中国礼 中国乐    | qlpd/zglzgy    |
| 超级语文课       | sdws/cjywk     |
| 文物里的山东     | yspd/wwldsd    |
| 拉呱             | qlpd/l0        |
| 生活帮           | shpd/shb       |
| 快乐大赢家       | zypd/kldyj     |
| 乡村季风         | nkpd/xcjf      |
| 健康是 1         | ggpd/jks1      |
| 此时此刻         | sdws/cishicike |

## Parameters
- `category`: 节目 id，可在对应节目页 URL 中找到，见下表，默认为 `sdws/sdxwlb`，即山东新闻联播


## Features
- `supportPodcast`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 节目名称         | 节目 id        |\n| ---------------- | -------------- |\n| 山东新闻联播     | sdws/sdxwlb    |\n| 闪电大视野       | ggpd/sddsy     |\n| 山东三农新闻联播 | nkpd/snxw      |\n| 每日新闻         | qlpd/mrxw      |\n| 新闻午班车       | ggpd/xwwbc     |\n| 戏宇宙           | sdws/xyz/      |\n| 中国礼 中国乐    | qlpd/zglzgy    |\n| 超级语文课       | sdws/cjywk     |\n| 文物里的山东     | yspd/wwldsd    |\n| 拉呱             | qlpd/l0        |\n| 生活帮           | shpd/shb       |\n| 快乐大赢家       | zypd/kldyj     |\n| 乡村季风         | nkpd/xcjf      |\n| 健康是 1         | ggpd/jks1      |\n| 此时此刻         | sdws/cishicike |",
  "example": "/iqilu/v/sdws/sdxwlb",
  "features": {
    "supportPodcast": true
  },
  "heat": 1,
  "location": "program.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "电视节目",
  "parameters": {
    "category": "节目 id，可在对应节目页 URL 中找到，见下表，默认为 `sdws/sdxwlb`，即山东新闻联播"
  },
  "path": "/v/:category{.+}?",
  "topFeeds": [
    {
      "description": "404 - Powered by RSSHub",
      "errorAt": "2025-11-27T05:18:11.166Z",
      "errorMessage": "[GET] \"http://v.iqilu.com/qdyaowen\": <no response> fetch failed\n",
      "id": "178028763735837697",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://v.iqilu.com/qdyaowen",
      "title": "404",
      "type": "feed",
      "url": "rsshub://iqilu/v/qdyaowen"
    }
  ]
}
```
