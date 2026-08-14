# 네이버 - 검색

## Coverage
`index-only`

## Route
- Namespace: `naver`
- Namespace Name: `네이버`
- Route Path: `/naver/search/:category/:keyword`
- Route Name: `검색`
- Example: `/naver/search/all/송소희`
- URL: `naver.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `slowmande`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "all", "description": "검색 카테고리. 기본값: all (통합검색)", "options": [{"label": "통합검색", "value": "all"}, {"label": "블로그", "value": "blog"}, {"label": "카페", "value": "cafe"}, {"label": "뉴스", "value": "news"}, {"label": "동영상", "value": "video"}]}
- `keyword`: 검색 키워드


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
  - `m.search.naver.com/search.naver`
- `target`: `/search/:category/:keyword`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/naver/search/all/송소희",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "search.ts",
  "maintainers": [
    "slowmande"
  ],
  "name": "검색",
  "parameters": {
    "category": {
      "default": "all",
      "description": "검색 카테고리. 기본값: all (통합검색)",
      "options": [
        {
          "label": "통합검색",
          "value": "all"
        },
        {
          "label": "블로그",
          "value": "blog"
        },
        {
          "label": "카페",
          "value": "cafe"
        },
        {
          "label": "뉴스",
          "value": "news"
        },
        {
          "label": "동영상",
          "value": "video"
        }
      ]
    },
    "keyword": "검색 키워드"
  },
  "path": "/search/:category/:keyword",
  "radar": [
    {
      "source": [
        "m.search.naver.com/search.naver"
      ],
      "target": "/search/:category/:keyword"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "송소희의 네이버 통합검색 검색 결과입니다. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1147948156013379584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.search.naver.com/search.naver?ssc=tab.m.all&where=m&sm=mtb_opt&query=%EC%86%A1%EC%86%8C%ED%9D%AC&nso=so%3Add&nso_open=1",
      "title": "송소희 - 네이버 통합검색",
      "type": "feed",
      "url": "rsshub://naver/search/all/%EC%86%A1%EC%86%8C%ED%9D%AC"
    },
    {
      "description": "송소희의 네이버 블로그 검색 결과입니다. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1147950450062786560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.search.naver.com/search.naver?ssc=tab.m_blog.all&sm=mtb_jum&query=%EC%86%A1%EC%86%8C%ED%9D%AC&nso=so%3Add",
      "title": "송소희 - 네이버 블로그",
      "type": "feed",
      "url": "rsshub://naver/search/blog/%EC%86%A1%EC%86%8C%ED%9D%AC"
    }
  ]
}
```
