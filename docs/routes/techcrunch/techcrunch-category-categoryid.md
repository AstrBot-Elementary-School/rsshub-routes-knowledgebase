# TechCrunch - Category

## Coverage
`index-only`

## Route
- Namespace: `techcrunch`
- Namespace Name: `TechCrunch`
- Route Path: `/techcrunch/category/:categoryId`
- Route Name: `Category`
- Example: `/techcrunch/category/577047203`
- URL: `techcrunch.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `MilliumOrion`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
Use the category ID to retrieve a list of articles, category ID.\
From the page source of `https://techcrunch.com/category/***`, locate the `{category_id}`\
Example:\
`html` -> `head` -> `<link rel="alternate" title="JSON" type="application/json" href="https://techcrunch.com/wp-json/wp/v2/categories/{category_id}">`

## Parameters
- `categoryId`: 分类id


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Use the category ID to retrieve a list of articles, category ID.\\\nFrom the page source of `https://techcrunch.com/category/***`, locate the `{category_id}`\\\nExample:\\\n`html` -> `head` -> `<link rel=\"alternate\" title=\"JSON\" type=\"application/json\" href=\"https://techcrunch.com/wp-json/wp/v2/categories/{category_id}\">`",
  "example": "/techcrunch/category/577047203",
  "heat": 1,
  "location": "category.ts",
  "maintainers": [
    "MilliumOrion"
  ],
  "name": "Category",
  "parameters": {
    "categoryId": "分类id"
  },
  "path": "/category/:categoryId",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2026-05-11T03:02:37.085Z",
      "errorMessage": "[GET] \"https://techcrunch.com/wp-json/wp/v2/posts?categories=artificial-intelligence\": 400 Bad Request\n",
      "id": "250564935356404743",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://techcrunch/category/artificial-intelligence"
    }
  ]
}
```
