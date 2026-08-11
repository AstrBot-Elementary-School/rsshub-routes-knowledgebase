# Smashing Magazine - Category

## Coverage
`index-only`

## Route
- Namespace: `smashingmagazine`
- Namespace Name: `Smashing Magazine`
- Route Path: `/smashingmagazine/:category?`
- Route Name: `Category`
- Example: `/smashingmagazine/react`
- URL: `smashingmagazine.com/articles/`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Rjnishant530`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| **Category**       |                    |
| ------------------ | ------------------ |
| Accessibility      | accessibility      |
| Best practices     | best-practices     |
| Business           | business           |
| Career             | career             |
| Checklists         | checklists         |
| CSS                | css                |
| Data Visualization | data-visualization |
| Design             | design             |
| Design Patterns    | design-patterns    |
| Design Systems     | design-systems     |
| E-Commerce         | e-commerce         |
| Figma              | figma              |
| Freebies           | freebies           |
| HTML               | html               |
| Illustrator        | illustrator        |
| Inspiration        | inspiration        |
| JavaScript         | javascript         |
| Mobile             | mobile             |
| Performance        | performance        |
| Privacy            | privacy            |
| React              | react              |
| Responsive Design  | responsive-design  |
| Round-Ups          | round-ups          |
| SEO                | seo                |
| Typography         | typography         |
| Tools              | tools              |
| UI                 | ui                 |
| Usability          | usability          |
| UX                 | ux                 |
| Vue                | vue                |
| Wallpapers         | wallpapers         |
| Web Design         | web-design         |
| Workflow           | workflow           |

## Parameters
- `category`: Find in URL or Table below


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
  - `smashingmagazine.com/category/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| **Category**       |                    |\n| ------------------ | ------------------ |\n| Accessibility      | accessibility      |\n| Best practices     | best-practices     |\n| Business           | business           |\n| Career             | career             |\n| Checklists         | checklists         |\n| CSS                | css                |\n| Data Visualization | data-visualization |\n| Design             | design             |\n| Design Patterns    | design-patterns    |\n| Design Systems     | design-systems     |\n| E-Commerce         | e-commerce         |\n| Figma              | figma              |\n| Freebies           | freebies           |\n| HTML               | html               |\n| Illustrator        | illustrator        |\n| Inspiration        | inspiration        |\n| JavaScript         | javascript         |\n| Mobile             | mobile             |\n| Performance        | performance        |\n| Privacy            | privacy            |\n| React              | react              |\n| Responsive Design  | responsive-design  |\n| Round-Ups          | round-ups          |\n| SEO                | seo                |\n| Typography         | typography         |\n| Tools              | tools              |\n| UI                 | ui                 |\n| Usability          | usability          |\n| UX                 | ux                 |\n| Vue                | vue                |\n| Wallpapers         | wallpapers         |\n| Web Design         | web-design         |\n| Workflow           | workflow           |",
  "example": "/smashingmagazine/react",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 19,
  "location": "category.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Category",
  "parameters": {
    "category": "Find in URL or Table below"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "smashingmagazine.com/category/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Latest Articles on Smashingmagazine.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "102715689541183507",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.smashingmagazine.com/articles",
      "title": "Smashing Magazine Articles",
      "type": "feed",
      "url": "rsshub://smashingmagazine"
    },
    {
      "description": "Latest Articles on Smashingmagazine.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71797696073612288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.smashingmagazine.com/category/react",
      "title": "Smashing Magazine Articles",
      "type": "feed",
      "url": "rsshub://smashingmagazine/react"
    }
  ],
  "url": "smashingmagazine.com/articles/"
}
```
