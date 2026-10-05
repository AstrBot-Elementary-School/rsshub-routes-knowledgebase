# Science Magazine - Blogs

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/science/blogs/:name?`
- Route Name: `Blogs`
- Example: `/science/blogs/pipeline`
- URL: `science.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TomHodson`
- Source Location: `blogs.ts`
- Source Module: `_None_`

## Description
To subscribe to [IN THE PIPELINE by Derek Lowe’s](https://science.org/blogs/pipeline) or the [science editor's blog](https://science.org/blogs/editors-blog), use the name parameter `pipeline` or `editors-blog`.

## Parameters
- `name`: Short name for the blog, get this from the url. Defaults to pipeline


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `science.org/blogs/:name`
- `target`: `/blogs/:name`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "To subscribe to [IN THE PIPELINE by Derek Lowe’s](https://science.org/blogs/pipeline) or the [science editor's blog](https://science.org/blogs/editors-blog), use the name parameter `pipeline` or `editors-blog`.",
  "example": "/science/blogs/pipeline",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 273,
  "location": "blogs.ts",
  "maintainers": [
    "TomHodson"
  ],
  "name": "Blogs",
  "parameters": {
    "name": "Short name for the blog, get this from the url. Defaults to pipeline"
  },
  "path": "/blogs/:name?",
  "radar": [
    {
      "source": [
        "science.org/blogs/:name"
      ],
      "target": "/blogs/:name"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "A Science.org blog called In the Pipeline - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "94573901566286848",
      "image": "https://www.science.org/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.science.org/blogs/pipeline",
      "title": "Science Blogs: In the Pipeline",
      "type": "feed",
      "url": "rsshub://science/blogs"
    },
    {
      "description": "A Science.org blog called In the Pipeline - Powered by RSSHub",
      "errorAt": "2026-09-27T22:23:06.788Z",
      "errorMessage": "[GET] \"https://www.science.org/blogs/pipeline/feed\": 403 Forbidden\n",
      "id": "65419023785781248",
      "image": "https://www.science.org/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.science.org/blogs/pipeline",
      "title": "Science Blogs: In the Pipeline",
      "type": "feed",
      "url": "rsshub://science/blogs/pipeline"
    }
  ]
}
```
