# 库洛游戏 | Kuro Games - 鸣潮 — 游戏公告、新闻与活动

## Coverage
`index-only`

## Route
- Namespace: `kurogames`
- Namespace Name: `库洛游戏 | Kuro Games`
- Route Path: `/kurogames/wutheringwaves/news/:language?`
- Route Name: `鸣潮 — 游戏公告、新闻与活动`
- Example: `/kurogames/wutheringwaves/news`
- URL: `www.kurogames.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `goestav, enpitsulin`
- Source Location: `wutheringwaves/news.ts`
- Source Module: `_None_`

## Description
Language codes for the `language` parameter:

| Language | Code         |
|----------|--------------|
| English  | en           |
| 日本語    | jp           |
| 한국어     | kr           |
| 简体中文   | zh (default) |
| 繁體中文   | zh-tw        |
| Español  | es           |
| Français | fr           |
| Deutsch  | de           |

## Parameters
- `language`: The language to use for the content. Default: `zh`.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mc.kurogames.com/m/main/news`
  - `mc.kurogames.com/main`
### Rule 2
- `title`: `Wuthering Waves — Game announcements, news and events`
- `source`:
  - `wutheringwaves.kurogames.com/en/main/news`
  - `wutheringwaves.kurogames.com/en/main`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "\nLanguage codes for the `language` parameter:\n\n| Language | Code         |\n|----------|--------------|\n| English  | en           |\n| 日本語    | jp           |\n| 한국어     | kr           |\n| 简体中文   | zh (default) |\n| 繁體中文   | zh-tw        |\n| Español  | es           |\n| Français | fr           |\n| Deutsch  | de           |\n    ",
  "example": "/kurogames/wutheringwaves/news",
  "heat": 39,
  "location": "wutheringwaves/news.ts",
  "maintainers": [
    "goestav",
    "enpitsulin"
  ],
  "name": "鸣潮 — 游戏公告、新闻与活动",
  "parameters": {
    "language": "The language to use for the content. Default: `zh`."
  },
  "path": "/wutheringwaves/news/:language?",
  "radar": [
    {
      "source": [
        "mc.kurogames.com/m/main/news",
        "mc.kurogames.com/main"
      ]
    },
    {
      "source": [
        "wutheringwaves.kurogames.com/en/main/news",
        "wutheringwaves.kurogames.com/en/main"
      ],
      "title": "Wuthering Waves — Game announcements, news and events"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "《鸣潮》— 游戏公告、新闻和活动 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41645808521081856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mc.kurogames.com/main#news",
      "title": "《鸣潮》— 游戏公告、新闻和活动",
      "type": "feed",
      "url": "rsshub://kurogames/wutheringwaves/news"
    },
    {
      "description": "《鸣潮》— 游戏公告、新闻和活动 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "134789849205955584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mc.kurogames.com/main#news",
      "title": "《鸣潮》— 游戏公告、新闻和活动",
      "type": "feed",
      "url": "rsshub://kurogames/wutheringwaves/news/zh"
    }
  ]
}
```
