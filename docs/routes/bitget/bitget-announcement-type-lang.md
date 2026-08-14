# Bitget - Announcement

## Coverage
`index-only`

## Route
- Namespace: `bitget`
- Namespace Name: `Bitget`
- Route Path: `/bitget/announcement/:type/:lang?`
- Route Name: `Announcement`
- Example: `/bitget/announcement/all/zh-CN`
- URL: `bitget.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `YukiCoco`
- Source Location: `announcement.ts`
- Source Module: `_None_`

## Description
type:

| Type              | Description |
| ----------------- | ----------- |
| all               | 全部通知    |
| new-listing       | 新币上线    |
| latest-activities | 最新活动    |
| new-announcement  | 最新公告    |

lang:

| Lang  | Description |
| ----- | ----------- |
| zh-CN | 中文        |
| en-US | English     |
| es-ES | Español     |
| fr-FR | Français    |
| de-DE | Deutsch     |
| ja-JP | 日本語      |
| ru-RU | Русский     |
| ar-SA | العربية     |

## Parameters
- `type`: {"default": "all", "description": "Bitget 通知类型", "options": [{"label": "全部通知", "value": "all"}, {"label": "新币上线", "value": "new-listing"}, {"label": "最新活动", "value": "latest-activities"}, {"label": "最新公告", "value": "new-announcement"}]}
- `lang`: {"default": "zh-CN", "description": "语言", "options": [{"label": "中文", "value": "zh-CN"}, {"label": "English", "value": "en-US"}, {"label": "Español", "value": "es-ES"}, {"label": "Français", "value": "fr-FR"}, {"label": "Deutsch", "value": "de-DE"}, {"label": "日本語", "value": "ja-JP"}, {"label": "Русский", "value": "ru-RU"}, {"label": "العربية", "value": "ar-SA"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bitget.com/:lang/inmail`
- `target`: `/announcement/all/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "type:\n\n| Type              | Description |\n| ----------------- | ----------- |\n| all               | 全部通知    |\n| new-listing       | 新币上线    |\n| latest-activities | 最新活动    |\n| new-announcement  | 最新公告    |\n\nlang:\n\n| Lang  | Description |\n| ----- | ----------- |\n| zh-CN | 中文        |\n| en-US | English     |\n| es-ES | Español     |\n| fr-FR | Français    |\n| de-DE | Deutsch     |\n| ja-JP | 日本語      |\n| ru-RU | Русский     |\n| ar-SA | العربية     |",
  "example": "/bitget/announcement/all/zh-CN",
  "heat": 612,
  "location": "announcement.ts",
  "maintainers": [
    "YukiCoco"
  ],
  "name": "Announcement",
  "parameters": {
    "lang": {
      "default": "zh-CN",
      "description": "语言",
      "options": [
        {
          "label": "中文",
          "value": "zh-CN"
        },
        {
          "label": "English",
          "value": "en-US"
        },
        {
          "label": "Español",
          "value": "es-ES"
        },
        {
          "label": "Français",
          "value": "fr-FR"
        },
        {
          "label": "Deutsch",
          "value": "de-DE"
        },
        {
          "label": "日本語",
          "value": "ja-JP"
        },
        {
          "label": "Русский",
          "value": "ru-RU"
        },
        {
          "label": "العربية",
          "value": "ar-SA"
        }
      ]
    },
    "type": {
      "default": "all",
      "description": "Bitget 通知类型",
      "options": [
        {
          "label": "全部通知",
          "value": "all"
        },
        {
          "label": "新币上线",
          "value": "new-listing"
        },
        {
          "label": "最新活动",
          "value": "latest-activities"
        },
        {
          "label": "最新公告",
          "value": "new-announcement"
        }
      ]
    }
  },
  "path": "/announcement/:type/:lang?",
  "radar": [
    {
      "source": [
        "www.bitget.com/:lang/inmail"
      ],
      "target": "/announcement/all/:lang"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Bitget | All - Powered by RSSHub",
      "errorAt": "2026-06-06T06:32:19.917Z",
      "errorMessage": "Unexpected end of JSON input\n",
      "id": "72615354761558016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bitget.com/zh-CN/inmail",
      "title": "Bitget | All",
      "type": "feed",
      "url": "rsshub://bitget/announcement/all"
    },
    {
      "description": "Bitget | New Listing - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73649080120641536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bitget.com/zh-CN/inmail",
      "title": "Bitget | New Listing",
      "type": "feed",
      "url": "rsshub://bitget/announcement/new-listing"
    }
  ],
  "view": 0
}
```
