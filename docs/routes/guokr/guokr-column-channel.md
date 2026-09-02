# 果壳网 - 果壳网专栏

## Coverage
`index-only`

## Route
- Namespace: `guokr`
- Namespace Name: `果壳网`
- Route Path: `/guokr/column/:channel`
- Route Name: `果壳网专栏`
- Example: `/guokr/column/calendar`
- URL: `guokr.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `DHPO, hoilc`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
| 物种日历 | 吃货研究所 | 美丽也是技术活 |
| -------- | ---------- | -------------- |
| calendar | institute  | beauty         |

## Parameters
- `channel`: 专栏类别


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `guokr.com/:channel`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 物种日历 | 吃货研究所 | 美丽也是技术活 |\n| -------- | ---------- | -------------- |\n| calendar | institute  | beauty         |",
  "example": "/guokr/column/calendar",
  "heat": 150,
  "location": "channel.ts",
  "maintainers": [
    "DHPO",
    "hoilc"
  ],
  "name": "果壳网专栏",
  "parameters": {
    "channel": "专栏类别"
  },
  "path": "/column/:channel",
  "radar": [
    {
      "source": [
        "guokr.com/:channel"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "果壳网 物种日历 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42595855568252928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.guokr.com/scientific/channel/pac/",
      "title": "果壳网 物种日历",
      "type": "feed",
      "url": "rsshub://guokr/column/calendar"
    },
    {
      "description": "果壳网 吃货研究所 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41843304175275008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.guokr.com/scientific/channel/predator/",
      "title": "果壳网 吃货研究所",
      "type": "feed",
      "url": "rsshub://guokr/column/institute"
    }
  ],
  "url": "guokr.com/"
}
```
