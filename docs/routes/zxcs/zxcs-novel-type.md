# 知轩藏书 - 小说列表

## Coverage
`index-only`

## Route
- Namespace: `zxcs`
- Namespace Name: `知轩藏书`
- Route Path: `/zxcs/novel/:type`
- Route Name: `小说列表`
- Example: `/zxcs/novel/jinqigengxin`
- URL: `zxcs.click`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `liaochuan`
- Source Location: `novel.ts`
- Source Module: `_None_`

## Description
支持小说类型：jinqigengxin-近期更新,dushi-都市,xianxia-仙侠,xuanhuan-玄幻,qihuan-奇幻,lishi-历史,youxi-游戏,wuxia-武侠,kehuan-科幻,tiyu-体育,lingyi-灵异,junshi-军事,erciyuan-轻小说

## Parameters
- `type`: 小说类型, 可在对应类型页 URL 中找到


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
  - `zxcs.click/:type`
- `target`: `/novel/:type`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "支持小说类型：jinqigengxin-近期更新,dushi-都市,xianxia-仙侠,xuanhuan-玄幻,qihuan-奇幻,lishi-历史,youxi-游戏,wuxia-武侠,kehuan-科幻,tiyu-体育,lingyi-灵异,junshi-军事,erciyuan-轻小说",
  "example": "/zxcs/novel/jinqigengxin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 97,
  "location": "novel.ts",
  "maintainers": [
    "liaochuan"
  ],
  "name": "小说列表",
  "parameters": {
    "type": "小说类型, 可在对应类型页 URL 中找到"
  },
  "path": "/novel/:type",
  "radar": [
    {
      "source": [
        "zxcs.click/:type"
      ],
      "target": "/novel/:type"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "知轩藏书 - 近期更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "140456340902353920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zxcs.click/jinqigengxin",
      "title": "知轩藏书 - 近期更新",
      "type": "feed",
      "url": "rsshub://zxcs/novel/jinqigengxin"
    },
    {
      "description": "知轩藏书 - 仙侠 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "156621875112397824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zxcs.click/xianxia",
      "title": "知轩藏书 - 仙侠",
      "type": "feed",
      "url": "rsshub://zxcs/novel/xianxia"
    }
  ],
  "url": "zxcs.click"
}
```
