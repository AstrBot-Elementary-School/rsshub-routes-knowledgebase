# 文学城 - 博客

## Coverage
`index-only`

## Route
- Namespace: `wenxuecity`
- Namespace Name: `文学城`
- Route Path: `/wenxuecity/blog/:id`
- Route Name: `博客`
- Example: `/wenxuecity/blog/43626`
- URL: `wenxuecity.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `changlan`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 博客 ID, 可在 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `blog.wenxuecity.com/myblog/:id`
  - `blog.wenxuecity.com/myoverview/:id`
- `target`: `/blog/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/wenxuecity/blog/43626",
  "heat": 0,
  "location": "blog.ts",
  "maintainers": [
    "changlan"
  ],
  "name": "博客",
  "parameters": {
    "id": "博客 ID, 可在 URL 中找到"
  },
  "path": "/blog/:id",
  "radar": [
    {
      "source": [
        "blog.wenxuecity.com/myblog/:id",
        "blog.wenxuecity.com/myoverview/:id"
      ],
      "target": "/blog/:id"
    }
  ],
  "topFeeds": []
}
```
