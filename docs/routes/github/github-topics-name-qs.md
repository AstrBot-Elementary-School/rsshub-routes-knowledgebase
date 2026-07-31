# GitHub - Topics

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/topics/:name/:qs?`
- Route Name: `Topics`
- Example: `/github/topics/framework`
- URL: `github.com/topics`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `queensferryme`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| Parameter | Description      | Values                                                                                                                          |
| --------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| `l`       | Language         | For instance `php`, which can be found in the URL of the corresponding [Topics page](https://github.com/topics/framework?l=php) |
| `o`       | Sorting Order    | `asc`, `desc`                                                                                                                   |
| `s`       | Sorting Criteria | `stars`, `forks`, `updated`                                                                                                     |

For instance, the `/github/topics/framework/l=php&o=desc&s=stars` route will generate the RSS feed corresponding to this [page](https://github.com/topics/framework?l=php\&o=desc\&s=stars).

## Parameters
- `name`: Topic name, which can be found in the URL of the corresponding [Topics Page](https://github.com/topics/framework)
- `qs`: Query string, like `l=php&o=desc&s=stars`. Details listed as follows:


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
  - `github.com/topics`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| Parameter | Description      | Values                                                                                                                          |\n| --------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------- |\n| `l`       | Language         | For instance `php`, which can be found in the URL of the corresponding [Topics page](https://github.com/topics/framework?l=php) |\n| `o`       | Sorting Order    | `asc`, `desc`                                                                                                                   |\n| `s`       | Sorting Criteria | `stars`, `forks`, `updated`                                                                                                     |\n\nFor instance, the `/github/topics/framework/l=php&o=desc&s=stars` route will generate the RSS feed corresponding to this [page](https://github.com/topics/framework?l=php\\&o=desc\\&s=stars).",
  "example": "/github/topics/framework",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 97,
  "location": "topic.ts",
  "maintainers": [
    "queensferryme"
  ],
  "name": "Topics",
  "parameters": {
    "name": "Topic name, which can be found in the URL of the corresponding [Topics Page](https://github.com/topics/framework)",
    "qs": "Query string, like `l=php&o=desc&s=stars`. Details listed as follows:"
  },
  "path": "/topics/:name/:qs?",
  "radar": [
    {
      "source": [
        "github.com/topics"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "A framework is a reusable set of libraries or classes in software. In an effort to help developers focus their work on higher level tasks, a framework provides a functional solution for lower level elements of coding. While a framework might add more code than is necessary, they also provide a reusable pattern to speed up development. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60991851974661120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "framework · GitHub Topics · GitHub",
      "type": "feed",
      "url": "rsshub://github/topics/framework"
    },
    {
      "description": "The branch of computer science dealing with the reproduction, or mimicking of human-level intelligence, self-awareness, knowledge, conscience, and thought in computer programs. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73606836817679360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "ai · GitHub Topics · GitHub",
      "type": "feed",
      "url": "rsshub://github/topics/ai"
    }
  ],
  "url": "github.com/topics"
}
```
