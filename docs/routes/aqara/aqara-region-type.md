# Aqara - 新闻、博客

## Coverage
`index-only`

## Route
- Namespace: `aqara`
- Namespace Name: `Aqara`
- Route Path: `/aqara/:region/:type?`
- Route Name: `新闻、博客`
- Example: `/aqara/en/news`
- URL: `aqara.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `region.ts`
- Source Module: `_None_`

## Description
| 中国 / 大陆 | 대한민국 | Europe | United States | Russia | Global |
| ----------- | -------- | ------ | ------------- | ------ | ------ |
| cn          | kr       | eu     | us            | ru     | en     |

| 新闻 | 博客 |
| ---- | ---- |
| news | blog |

## Parameters
- `region`: 地区 id，可在对应新闻页 URL 中找到，默认为 en，即 Global
- `type`: 类型，见下表，默认为 news，即新闻


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 中国 / 大陆 | 대한민국 | Europe | United States | Russia | Global |\n| ----------- | -------- | ------ | ------------- | ------ | ------ |\n| cn          | kr       | eu     | us            | ru     | en     |\n\n| 新闻 | 博客 |\n| ---- | ---- |\n| news | blog |",
  "example": "/aqara/en/news",
  "heat": 0,
  "location": "region.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻、博客",
  "parameters": {
    "region": "地区 id，可在对应新闻页 URL 中找到，默认为 en，即 Global",
    "type": "类型，见下表，默认为 news，即新闻"
  },
  "path": "/:region/:type?",
  "topFeeds": []
}
```
