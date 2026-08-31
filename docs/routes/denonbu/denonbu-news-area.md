# 電音部 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `denonbu`
- Namespace Name: `電音部`
- Route Path: `/denonbu/news/:area?`
- Route Name: `新闻`
- Example: `/denonbu/news/azabu`
- URL: `denonbu.jp`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `outloudvi`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
**Area**

| ID            | Group name/Area name                              |
| ------------- | ------------------------------------------------- |
| akiba         | 外神田文芸高校                                    |
| harajuku      | 神宮前参道學園                                    |
| azabu         | 港白金女学院                                      |
| shibuya       | 帝音国際学院                                      |
| kabuki        | 真新宿 GR 学園                                    |
| deep-okubo    | Bellemule（深大久保 DJ＆ダンスアカデミー）        |
| deep-okubo-k  | 輝きノスタルジア（深大久保 DJ＆ダンスアカデミー） |
| shinsaibashi  | OKINI☆PARTY'S（心斎橋演芸高校）                   |
| ikebukuro     | 池袋電音部（池袋空乗院高校）                      |
| neotokyo      | 東京電脳（東京電脳学園）                          |
| neonakano     | 中野電脳（中野電脳学園）                          |
| shimokitazawa | Ma'Scar'Piece（北沢音箱高校）                     |

**Category**
Working category IDs include `news` (the default), `event`, `goods`, `comic`, `movie`, `music` or `livearchives`.

## Parameters
- `area`: The id of the area or category; values are as follows.


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
  - `denonbu.jp/news`
- `target`: `/news`
### Rule 2
- `source`:
  - `denonbu.jp/event`
- `target`: `/news/event`
### Rule 3
- `source`:
  - `denonbu.jp/goods`
- `target`: `/news/goods`
### Rule 4
- `source`:
  - `denonbu.jp/comic`
- `target`: `/news/comic`
### Rule 5
- `source`:
  - `denonbu.jp/movie`
- `target`: `/news/movie`
### Rule 6
- `source`:
  - `denonbu.jp/music`
- `target`: `/news/music`
### Rule 7
- `source`:
  - `denonbu.jp/livearchives`
- `target`: `/news/livearchives`
### Rule 8
- `source`:
  - `denonbu.jp/area/:area`
- `target`: `/news/:area`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "**Area**\n\n| ID            | Group name/Area name                              |\n| ------------- | ------------------------------------------------- |\n| akiba         | 外神田文芸高校                                    |\n| harajuku      | 神宮前参道學園                                    |\n| azabu         | 港白金女学院                                      |\n| shibuya       | 帝音国際学院                                      |\n| kabuki        | 真新宿 GR 学園                                    |\n| deep-okubo    | Bellemule（深大久保 DJ＆ダンスアカデミー）        |\n| deep-okubo-k  | 輝きノスタルジア（深大久保 DJ＆ダンスアカデミー） |\n| shinsaibashi  | OKINI☆PARTY'S（心斎橋演芸高校）                   |\n| ikebukuro     | 池袋電音部（池袋空乗院高校）                      |\n| neotokyo      | 東京電脳（東京電脳学園）                          |\n| neonakano     | 中野電脳（中野電脳学園）                          |\n| shimokitazawa | Ma'Scar'Piece（北沢音箱高校）                     |\n\n**Category**\nWorking category IDs include `news` (the default), `event`, `goods`, `comic`, `movie`, `music` or `livearchives`.",
  "example": "/denonbu/news/azabu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "outloudvi"
  ],
  "name": "新闻",
  "parameters": {
    "area": "The id of the area or category; values are as follows."
  },
  "path": "/news/:area?",
  "radar": [
    {
      "source": [
        "denonbu.jp/news"
      ],
      "target": "/news"
    },
    {
      "source": [
        "denonbu.jp/event"
      ],
      "target": "/news/event"
    },
    {
      "source": [
        "denonbu.jp/goods"
      ],
      "target": "/news/goods"
    },
    {
      "source": [
        "denonbu.jp/comic"
      ],
      "target": "/news/comic"
    },
    {
      "source": [
        "denonbu.jp/movie"
      ],
      "target": "/news/movie"
    },
    {
      "source": [
        "denonbu.jp/music"
      ],
      "target": "/news/music"
    },
    {
      "source": [
        "denonbu.jp/livearchives"
      ],
      "target": "/news/livearchives"
    },
    {
      "source": [
        "denonbu.jp/area/:area"
      ],
      "target": "/news/:area"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "denonbu.jp"
}
```
