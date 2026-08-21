# Syosetu - Search

## Coverage
`index-only`

## Route
- Namespace: `syosetu`
- Namespace Name: `Syosetu`
- Route Path: `/syosetu/search/:sub/:query`
- Route Name: `Search`
- Example: `/syosetu/search/noc/word=ハーレム&notword=&type=r&mintime=&maxtime=&minlen=30000&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&isgl=1&notbl=1&order=new?limit=5`
- URL: `syosetu.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `SnowAgar25`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sub`: {"description": "The target Syosetu subsite.", "options": [{"label": "小説を読もう", "value": "yomou"}, {"label": "ノクターン", "value": "noc"}, {"label": "ムーンライト", "value": "mnlt"}, {"label": "ミッドナイト", "value": "mid"}]}
- `query`: Search parameters in Syosetu format.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
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
    "reading"
  ],
  "example": "/syosetu/search/noc/word=ハーレム&notword=&type=r&mintime=&maxtime=&minlen=30000&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&isgl=1&notbl=1&order=new?limit=5",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "search.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Search",
  "parameters": {
    "query": "Search parameters in Syosetu format.",
    "sub": {
      "description": "The target Syosetu subsite.",
      "options": [
        {
          "label": "小説を読もう",
          "value": "yomou"
        },
        {
          "label": "ノクターン",
          "value": "noc"
        },
        {
          "label": "ムーンライト",
          "value": "mnlt"
        },
        {
          "label": "ミッドナイト",
          "value": "mid"
        }
      ]
    }
  },
  "path": "/search/:sub/:query",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Syosetu Search: ハーレム - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "133418121074728960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://noc.syosetu.com/search/search/search.php?word=%E3%83%8F%E3%83%BC%E3%83%AC%E3%83%A0&notword=&type=r&mintime=&maxtime=&minlen=30000&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&isgl=1&notbl=1&order=new",
      "title": "Syosetu Search: ハーレム",
      "type": "feed",
      "url": "rsshub://syosetu/search/noc/word=%E3%83%8F%E3%83%BC%E3%83%AC%E3%83%A0&notword=&type=r&mintime=&maxtime=&minlen=30000&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&isgl=1&notbl=1&order=new"
    },
    {
      "description": "Syosetu Search: 百合 -男主人公 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "101361819062948864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://noc.syosetu.com/search/search/search.php?word=%E7%99%BE%E5%90%88&notword=%E7%94%B7%E4%B8%BB%E4%BA%BA%E5%85%AC&type=&mintime=&maxtime=&minlen=&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&order=dailypoint",
      "title": "Syosetu Search: 百合 -男主人公",
      "type": "feed",
      "url": "rsshub://syosetu/search/noc/word=%E7%99%BE%E5%90%88&notword=%E7%94%B7%E4%B8%BB%E4%BA%BA%E5%85%AC&type=&mintime=&maxtime=&minlen=&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&order=dailypoint"
    }
  ]
}
```
