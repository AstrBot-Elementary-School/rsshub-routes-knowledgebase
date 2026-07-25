# 天下雜誌 - 主頻道

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/cw/master/:channel`
- Route Name: `主頻道`
- Example: `/cw/master/8`
- URL: `cw.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `master.ts`
- Source Module: `_None_`

## Description
| 主頻道名稱 | 主頻道 ID |
| ---------- | --------- |
| 財經       | 8         |
| 產業       | 7         |
| 國際       | 9         |
| 管理       | 10        |
| 環境       | 12        |
| 教育       | 13        |
| 人物       | 14        |
| 政治社會   | 77        |
| 調查排行   | 15        |
| 健康關係   | 79        |
| 時尚品味   | 11        |
| 運動生活   | 103       |
| 重磅外媒   | 16        |

## Parameters
- `channel`: 主頻道 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
  "description": "| 主頻道名稱 | 主頻道 ID |\n| ---------- | --------- |\n| 財經       | 8         |\n| 產業       | 7         |\n| 國際       | 9         |\n| 管理       | 10        |\n| 環境       | 12        |\n| 教育       | 13        |\n| 人物       | 14        |\n| 政治社會   | 77        |\n| 調查排行   | 15        |\n| 健康關係   | 79        |\n| 時尚品味   | 11        |\n| 運動生活   | 103       |\n| 重磅外媒   | 16        |",
  "example": "/cw/master/8",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 76,
  "location": "master.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "主頻道",
  "parameters": {
    "channel": "主頻道 ID，可在 URL 中找到"
  },
  "path": "/master/:channel",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "天下雜誌提供最新財經等重要資訊報導。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66757488440144896",
      "image": "https://www.cw.com.tw/assets_new/img/fbshare.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cw.com.tw/masterChannel.action?idMasterChannel=8",
      "title": "財經－天下雜誌",
      "type": "feed",
      "url": "rsshub://cw/master/8"
    },
    {
      "description": "天下雜誌提供最新國際等重要資訊報導。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84170446829198336",
      "image": "https://www.cw.com.tw/assets_new/img/fbshare.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cw.com.tw/masterChannel.action?idMasterChannel=9",
      "title": "國際－天下雜誌",
      "type": "feed",
      "url": "rsshub://cw/master/9"
    }
  ]
}
```
