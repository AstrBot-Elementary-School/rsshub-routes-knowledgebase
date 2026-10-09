# DeepSeek - Change Log

## Coverage
`index-only`

## Route
- Namespace: `deepseek`
- Namespace Name: `DeepSeek`
- Route Path: `/deepseek/changelog/:language?`
- Route Name: `Change Log`
- Example: `/deepseek/changelog`
- URL: `api-docs.deepseek.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `ljh12138164`
- Source Location: `changelog.ts`
- Source Module: `_None_`

## Description
DeepSeek API change log in Chinese and English.

## Parameters
- `language`: Language, use `en` for English; defaults to Chinese


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
  - `api-docs.deepseek.com/updates`
- `target`: `/changelog/en`
### Rule 2
- `source`:
  - `api-docs.deepseek.com/zh-cn/updates`
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "DeepSeek API change log in Chinese and English.",
  "example": "/deepseek/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "changelog.ts",
  "maintainers": [
    "ljh12138164"
  ],
  "name": "Change Log",
  "parameters": {
    "language": "Language, use `en` for English; defaults to Chinese"
  },
  "path": "/changelog/:language?",
  "radar": [
    {
      "source": [
        "api-docs.deepseek.com/updates"
      ],
      "target": "/changelog/en"
    },
    {
      "source": [
        "api-docs.deepseek.com/zh-cn/updates"
      ],
      "target": "/changelog"
    }
  ],
  "topFeeds": [],
  "url": "api-docs.deepseek.com",
  "zh": {
    "description": "DeepSeek API 更新日志，支持中文和英文。",
    "name": "更新日志",
    "parameters": {
      "language": "语言，可选 `en`，默认为中文"
    }
  }
}
```
