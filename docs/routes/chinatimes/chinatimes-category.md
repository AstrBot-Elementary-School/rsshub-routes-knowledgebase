# 中時新聞網 - 分類

## Coverage
`index-only`

## Route
- Namespace: `chinatimes`
- Namespace Name: `中時新聞網`
- Route Path: `/chinatimes/:category?`
- Route Name: `分類`
- Example: `/chinatimes/realtimenews`
- URL: `www.chinatimes.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `KingJem`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
|     即時     |   熱門  |   政治  | 生活 | 娛樂 |  財經 |  國際 |   言論  |   兩岸  |   軍事   |   社會  |  健康  |  體育  |      科技      |   運勢  | 有影 |  寶島  |
| :----------: | :-----: | :-----: | :--: | :--: | :---: | :---: | :-----: | :-----: | :------: | :-----: | :----: | :----: | :------------: | :-----: | :--: | :----: |
| realtimenews | hotnews | politic | life | star | money | world | opinion | chinese | armament | society | health | sports | technologynews | fortune | tube | taiwan |

## Parameters
- `category`: 分類，見下表，留空為 `realtimenews`


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
  - `www.chinatimes.com/:category/`
  - `www.chinatimes.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "|     即時     |   熱門  |   政治  | 生活 | 娛樂 |  財經 |  國際 |   言論  |   兩岸  |   軍事   |   社會  |  健康  |  體育  |      科技      |   運勢  | 有影 |  寶島  |\n| :----------: | :-----: | :-----: | :--: | :--: | :---: | :---: | :-----: | :-----: | :------: | :-----: | :----: | :----: | :------------: | :-----: | :--: | :----: |\n| realtimenews | hotnews | politic | life | star | money | world | opinion | chinese | armament | society | health | sports | technologynews | fortune | tube | taiwan |",
  "example": "/chinatimes/realtimenews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "index.ts",
  "maintainers": [
    "KingJem"
  ],
  "name": "分類",
  "parameters": {
    "category": "分類，見下表，留空為 `realtimenews`"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.chinatimes.com/:category/",
        "www.chinatimes.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "《中時新聞網》 即時新聞最新列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197798198610638848",
      "image": "https://www.chinatimes.com/images/2020/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.chinatimes.com/realtimenews/?chdtv",
      "title": "即時新聞 - 中時新聞網",
      "type": "feed",
      "url": "rsshub://chinatimes/realtimenews"
    },
    {
      "description": "《中時新聞網》 即時新聞最新列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "223581630864617472",
      "image": "https://www.chinatimes.com/images/2020/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.chinatimes.com/realtimenews/?chdtv",
      "title": "即時新聞 - 中時新聞網",
      "type": "feed",
      "url": "rsshub://chinatimes/star"
    }
  ],
  "url": "www.chinatimes.com/"
}
```
