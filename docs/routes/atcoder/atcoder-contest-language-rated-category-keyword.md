# AtCoder - Contests Archive

## Coverage
`index-only`

## Route
- Namespace: `atcoder`
- Namespace Name: `AtCoder`
- Route Path: `/atcoder/contest/:language?/:rated?/:category?/:keyword?`
- Route Name: `Contests Archive`
- Example: `/atcoder/contest`
- URL: `atcoder.jp`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `contest.ts`
- Source Module: `_None_`

## Description
Rated Range

| ABC Class (Rated for \~1999) | ARC Class (Rated for \~2799) | AGC Class (Rated for \~9999) |
| ---------------------------- | ---------------------------- | ---------------------------- |
| 1                            | 2                            | 3                            |

Category

| All | AtCoder Typical Contest | PAST Archive | Unofficial(unrated) |
| --- | ----------------------- | ------------ | ------------------- |
| 0   | 6                       | 50           | 101                 |

| JOI Archive | Sponsored Tournament | Sponsored Parallel(rated) |
| ----------- | -------------------- | ------------------------- |
| 200         | 1000                 | 1001                      |

| Sponsored Parallel(unrated) | Optimization Contest |
| --------------------------- | -------------------- |
| 1002                        | 1200                 |

## Parameters
- `language`: Language, `jp` as Japanese or `en` as English, English by default
- `rated`: Rated Range, see below, all by default
- `category`: Category, see below, all by default
- `keyword`: Keyword


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
    "programming"
  ],
  "description": "Rated Range\n\n| ABC Class (Rated for \\~1999) | ARC Class (Rated for \\~2799) | AGC Class (Rated for \\~9999) |\n| ---------------------------- | ---------------------------- | ---------------------------- |\n| 1                            | 2                            | 3                            |\n\nCategory\n\n| All | AtCoder Typical Contest | PAST Archive | Unofficial(unrated) |\n| --- | ----------------------- | ------------ | ------------------- |\n| 0   | 6                       | 50           | 101                 |\n\n| JOI Archive | Sponsored Tournament | Sponsored Parallel(rated) |\n| ----------- | -------------------- | ------------------------- |\n| 200         | 1000                 | 1001                      |\n\n| Sponsored Parallel(unrated) | Optimization Contest |\n| --------------------------- | -------------------- |\n| 1002                        | 1200                 |",
  "example": "/atcoder/contest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "contest.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Contests Archive",
  "parameters": {
    "category": "Category, see below, all by default",
    "keyword": "Keyword",
    "language": "Language, `jp` as Japanese or `en` as English, English by default",
    "rated": "Rated Range, see below, all by default"
  },
  "path": "/contest/:language?/:rated?/:category?/:keyword?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Contest Archive - AtCoder - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56948849407992836",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://atcoder.jp/contests/archive?lang=en&ratedType=0&category=0",
      "title": "Contest Archive - AtCoder",
      "type": "feed",
      "url": "rsshub://atcoder/contest"
    }
  ]
}
```
