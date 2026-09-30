# Uber - Engineering

## Coverage
`index-only`

## Route
- Namespace: `uber`
- Namespace Name: `Uber`
- Route Path: `/uber/blog/:category?`
- Route Name: `Engineering`
- Example: `/uber/blog`
- URL: `www.uber.com/us/en/blog/engineering`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `hulb, zhsama`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
The optional category parameter uses the slug from an Uber Engineering category URL. Deprecated numeric `maxPage` values remain accepted and return the overview feed.

## Parameters
- `category`: {"description": "Category slug from `/blog/engineering/:category`. Defaults to all engineering articles.", "options": [{"label": "AI / ML", "value": "uber-ai"}, {"label": "Backend", "value": "backend"}, {"label": "Culture", "value": "culture"}, {"label": "Data", "value": "data"}, {"label": "Mobile", "value": "mobile"}, {"label": "Security", "value": "security"}, {"label": "Web", "value": "web"}]}


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
- `source`:
  - `eng.uber.com/`
  - `www.uber.com/:country/:language/blog/engineering`
- `target`: `/blog`
### Rule 2
- `source`:
  - `www.uber.com/:country/:language/blog/engineering/:category`
- `target`: `/blog/:category`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "The optional category parameter uses the slug from an Uber Engineering category URL. Deprecated numeric `maxPage` values remain accepted and return the overview feed.",
  "example": "/uber/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 97,
  "location": "blog.ts",
  "maintainers": [
    "hulb",
    "zhsama"
  ],
  "name": "Engineering",
  "parameters": {
    "category": {
      "description": "Category slug from `/blog/engineering/:category`. Defaults to all engineering articles.",
      "options": [
        {
          "label": "AI / ML",
          "value": "uber-ai"
        },
        {
          "label": "Backend",
          "value": "backend"
        },
        {
          "label": "Culture",
          "value": "culture"
        },
        {
          "label": "Data",
          "value": "data"
        },
        {
          "label": "Mobile",
          "value": "mobile"
        },
        {
          "label": "Security",
          "value": "security"
        },
        {
          "label": "Web",
          "value": "web"
        }
      ]
    }
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "eng.uber.com/",
        "www.uber.com/:country/:language/blog/engineering"
      ],
      "target": "/blog"
    },
    {
      "source": [
        "www.uber.com/:country/:language/blog/engineering/:category"
      ],
      "target": "/blog/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "The technology behind Uber Engineering. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56764323854292992",
      "image": "https://tb-static.uber.com/prod/udam-assets/6b65f287-0bee-44e7-868a-e26b8722364e.png",
      "ownerUserId": null,
      "siteUrl": "https://www.uber.com/us/en/blog/engineering/",
      "title": "Uber Engineering Blog",
      "type": "feed",
      "url": "rsshub://uber/blog"
    }
  ],
  "url": "www.uber.com/us/en/blog/engineering",
  "zh": {
    "description": "可选的分类参数使用 Uber Engineering 分类 URL 中的 slug。已弃用的数字 `maxPage` 参数仍然兼容，并返回全部文章。"
  }
}
```
