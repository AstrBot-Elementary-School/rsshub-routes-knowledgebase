# Instructables - Projects

## Coverage
`index-only`

## Route
- Namespace: `instructables`
- Namespace Name: `Instructables`
- Route Path: `/instructables/projects/:category?`
- Route Name: `Projects`
- Example: `/instructables/projects/circuits`
- URL: `instructables.com/projects`
- Language: `_None_`
- Categories: `other`
- Maintainers: `wolfg1969`
- Source Location: `projects.ts`
- Source Module: `_None_`

## Description
| All | Circuits | Workshop | Craft | Cooking | Living | Outside | Teachers |
| --- | -------- | -------- | ----- | ------- | ------ | ------- | -------- |
|     | circuits | workshop | craft | cooking | living | outside | teachers |

## Parameters
- `category`: Category, empty by default, can be found in URL or see the table below


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
  - `instructables.com/projects`
- `target`: `/projects`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| All | Circuits | Workshop | Craft | Cooking | Living | Outside | Teachers |\n| --- | -------- | -------- | ----- | ------- | ------ | ------- | -------- |\n|     | circuits | workshop | craft | cooking | living | outside | teachers |",
  "example": "/instructables/projects/circuits",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "projects.ts",
  "maintainers": [
    "wolfg1969"
  ],
  "name": "Projects",
  "parameters": {
    "category": "Category, empty by default, can be found in URL or see the table below"
  },
  "path": "/projects/:category?",
  "radar": [
    {
      "source": [
        "instructables.com/projects"
      ],
      "target": "/projects"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Instructables Projects - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59119316294575104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://instructables.com/projects",
      "title": "Instructables Projects",
      "type": "feed",
      "url": "rsshub://instructables/projects"
    },
    {
      "description": "Instructables Projects - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76976459015504896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://instructables.com/projects",
      "title": "Instructables Projects",
      "type": "feed",
      "url": "rsshub://instructables/projects/circuits"
    }
  ],
  "url": "instructables.com/projects"
}
```
