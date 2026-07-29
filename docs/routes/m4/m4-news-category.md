# 四月网 - 要闻

## Coverage
`index-only`

## Route
- Namespace: `m4`
- Namespace Name: `四月网`
- Route Path: `/m4/news/:category?`
- Route Name: `要闻`
- Example: `/m4/news/china`
- URL: `news.m4.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 分类                                  | ID         |
| ------------------------------------- | ---------- |
| [国内新闻](http://news.m4.cn/china/)  | china      |
| [国际新闻](http://news.m4.cn/world/)  | world      |
| [民生](http://news.m4.cn/livelihood/) | livelihood |
| [社会](http://news.m4.cn/society/)    | society    |
| [财经](http://news.m4.cn/finance/)    | finance    |
| [科技](http://news.m4.cn/tech/)       | tech       |

## Parameters
- `category`: 分类，见下表，默认为国内新闻


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `news.m4.cn/:category`
  - `news.m4.cn/`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 分类                                  | ID         |\n| ------------------------------------- | ---------- |\n| [国内新闻](http://news.m4.cn/china/)  | china      |\n| [国际新闻](http://news.m4.cn/world/)  | world      |\n| [民生](http://news.m4.cn/livelihood/) | livelihood |\n| [社会](http://news.m4.cn/society/)    | society    |\n| [财经](http://news.m4.cn/finance/)    | finance    |\n| [科技](http://news.m4.cn/tech/)       | tech       |",
  "example": "/m4/news/china",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "要闻",
  "parameters": {
    "category": "分类，见下表，默认为国内新闻"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.m4.cn/:category",
        "news.m4.cn/"
      ],
      "target": "/news/:category"
    }
  ],
  "topFeeds": [],
  "url": "news.m4.cn"
}
```
