# 世界新聞網 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `worldjournal`
- Namespace Name: `世界新聞網`
- Route Path: `/worldjournal/:path{.+}?`
- Route Name: `新聞`
- Example: `/worldjournal`
- URL: `worldjournal.com/wj/*path`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: URL 中 `/wj/` 後的路徑，預設為 `cate/breaking`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `worldjournal.com/wj/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/worldjournal",
  "heat": 12,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新聞",
  "parameters": {
    "path": "URL 中 `/wj/` 後的路徑，預設為 `cate/breaking`"
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "worldjournal.com/wj/*path"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "世界新聞網提供全球華人關心的即時新聞；除美、中、台與港澳等地的政經、社會、生活、理財等新聞與深度報導外，更關切國際現勢與紐約、洛杉磯、舊金山等美國主要城市的社區動態。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "101992545694702592",
      "image": "https://www.worldjournal.com/static/img/icons/icon-144x144.png",
      "ownerUserId": null,
      "siteUrl": "https://www.worldjournal.com/wj/cate/breaking",
      "title": "即時 | 世界新聞網",
      "type": "feed",
      "url": "rsshub://worldjournal"
    },
    {
      "description": "世界新聞網提供全球華人關心的即時新聞；除美、中、台與港澳等地的政經、社會、生活、理財等新聞與深度報導外，更關切國際現勢與紐約、洛杉磯、舊金山等美國主要城市的社區動態。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "102181776735440896",
      "image": "https://www.worldjournal.com/static/img/icons/icon-144x144.png",
      "ownerUserId": null,
      "siteUrl": "https://www.worldjournal.com/wj/cate/breaking/121010",
      "title": "即時 | 世界新聞網",
      "type": "feed",
      "url": "rsshub://worldjournal/cate/breaking/121010"
    }
  ],
  "url": "worldjournal.com/wj/*path"
}
```
