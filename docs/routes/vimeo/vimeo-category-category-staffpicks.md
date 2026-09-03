# Vimeo - Category

## Coverage
`index-only`

## Route
- Namespace: `vimeo`
- Namespace Name: `Vimeo`
- Route Path: `/vimeo/category/:category/:staffpicks?`
- Route Name: `Category`
- Example: `/vimeo/category/documentary/staffpicks`
- URL: `vimeo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `MisteryMonster`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category name can get from url like `documentary` in [https://vimeo.com/categories/documentary/videos](https://vimeo.com/categories/documentary/videos)
- `staffpicks`: type `staffpicks` to sort with staffpicks


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
    "social-media"
  ],
  "example": "/vimeo/category/documentary/staffpicks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 38,
  "location": "category.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category name can get from url like `documentary` in [https://vimeo.com/categories/documentary/videos](https://vimeo.com/categories/documentary/videos) ",
    "staffpicks": "type `staffpicks` to sort with staffpicks"
  },
  "path": "/category/:category/:staffpicks?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Watch documentaries online, including films and videos featuring true stories, character and artist profiles, and more. - Powered by RSSHub",
      "errorAt": "2025-11-14T00:40:29.030Z",
      "errorMessage": "500 \n",
      "id": "67892393839925248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vimeo.com/categories/documentary/videos/sort:latest",
      "title": "documentary | Vimeo category",
      "type": "feed",
      "url": "rsshub://vimeo/category/documentary"
    },
    {
      "description": "Watch documentaries online, including films and videos featuring true stories, character and artist profiles, and more. - Powered by RSSHub",
      "errorAt": "2025-11-14T01:11:29.498Z",
      "errorMessage": "[GET] \"https://api.vimeo.com/categories/documentary/videos?page=1&per_page=18&direction=desc&sort=date&filter=conditional_featured\": 404 Not Found\n",
      "id": "60197856983408640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vimeo.com/categories/documentary/videos/sort:latest?staffpicked=true",
      "title": "documentary: documentary staffpicks | Vimeo category",
      "type": "feed",
      "url": "rsshub://vimeo/category/documentary/staffpicks"
    }
  ],
  "view": 3
}
```
