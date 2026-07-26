# 中伦律师事务所 - 中伦研究专业文章

## Coverage
`index-only`

## Route
- Namespace: `zhonglun`
- Namespace Name: `中伦律师事务所`
- Route Path: `/zhonglun/research/article/:language?`
- Route Name: `中伦研究专业文章`
- Example: `/zhonglun/research/article/zh`
- URL: `zhonglun.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| ENG | 简体中文 | 日本語 | 한국어 |
| --- | -------- | ------ | ------ |
| en  | zh       | ja     | kr     |

## Parameters
- `category`: 语言，默认为 zh，即简体中文，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `专业文章`
- `source`:
  - `zhonglun.com/research/articles`
- `target`: `/research/article/zh`
### Rule 2
- `title`: `Articles`
- `source`:
  - `en.zhonglun.com/research/articles`
- `target`: `/research/article/en`
### Rule 3
- `title`: `論評`
- `source`:
  - `ja.zhonglun.com/research/articles`
- `target`: `/research/article/ja`
### Rule 4
- `title`: `전문기사`
- `source`:
  - `kr.zhonglun.com/research/articles`
- `target`: `/research/article/kr`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| ENG | 简体中文 | 日本語 | 한국어 |\n| --- | -------- | ------ | ------ |\n| en  | zh       | ja     | kr     |",
  "example": "/zhonglun/research/article/zh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 48,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中伦研究专业文章",
  "parameters": {
    "category": "语言，默认为 zh，即简体中文，可在对应分类页 URL 中找到"
  },
  "path": "/research/article/:language?",
  "radar": [
    {
      "source": [
        "zhonglun.com/research/articles"
      ],
      "target": "/research/article/zh",
      "title": "专业文章"
    },
    {
      "source": [
        "en.zhonglun.com/research/articles"
      ],
      "target": "/research/article/en",
      "title": " Articles"
    },
    {
      "source": [
        "ja.zhonglun.com/research/articles"
      ],
      "target": "/research/article/ja",
      "title": "論評"
    },
    {
      "source": [
        "kr.zhonglun.com/research/articles"
      ],
      "target": "/research/article/kr",
      "title": "전문기사"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中伦律师事务所官方网站 - ARTICLES 专业文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58764289153552384",
      "image": "https://www.zhonglun.com/upload/static/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.zhonglun.com/research/articles",
      "title": "中伦律师事务所官方网站 - ARTICLES 专业文章",
      "type": "feed",
      "url": "rsshub://zhonglun/research/article/zh"
    },
    {
      "description": "中伦律师事务所官方网站 - ARTICLES 专业文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "166932773326277632",
      "image": "https://www.zhonglun.com/upload/static/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.zhonglun.com/research/articles",
      "title": "中伦律师事务所官方网站 - ARTICLES 专业文章",
      "type": "feed",
      "url": "rsshub://zhonglun/research/article"
    }
  ],
  "url": "zhonglun.com"
}
```
