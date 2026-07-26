# LinkedIn - Company Posts

## Coverage
`index-only`

## Route
- Namespace: `linkedin`
- Namespace Name: `LinkedIn`
- Route Path: `/linkedin/company/:company_id/posts`
- Route Name: `Company Posts`
- Example: `/linkedin/company/google/posts`
- URL: `linkedin.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `saifazmi`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
Get company's LinkedIn posts by company ID

## Parameters
- `company_id`: Company's LinkedIn profile ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportRadar`: false
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
  "description": "Get company's LinkedIn posts by company ID",
  "example": "/linkedin/company/google/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 35,
  "location": "posts.ts",
  "maintainers": [
    "saifazmi"
  ],
  "name": "Company Posts",
  "parameters": {
    "company_id": "Company's LinkedIn profile ID"
  },
  "path": "/company/:company_id/posts",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "This feed gets GreatFrontEnd's posts from LinkedIn - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "173633672770214912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linkedin.com/company/greatfrontend",
      "title": "LinkedIn - GreatFrontEnd's Posts",
      "type": "feed",
      "url": "rsshub://linkedin/company/greatfrontend/posts"
    },
    {
      "description": "This feed gets CellMark's posts from LinkedIn - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155076041493307392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linkedin.com/company/cellmark",
      "title": "LinkedIn - CellMark's Posts",
      "type": "feed",
      "url": "rsshub://linkedin/company/cellmark/posts"
    }
  ]
}
```
