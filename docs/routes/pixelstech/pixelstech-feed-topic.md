# PixelsTech - Feed

## Coverage
`index-only`

## Route
- Namespace: `pixelstech`
- Namespace Name: `PixelsTech`
- Route Path: `/pixelstech/feed/:topic?`
- Route Name: `Feed`
- Example: `/pixelstech/feed/ai`
- URL: `www.pixelstech.net`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [AI](https://www.pixelstech.net/feed/ai), where the source URL is `https://www.pixelstech.net/feed/ai`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/pixelstech/feed/ai`](https://rsshub.app/pixelstech/feed/ai).
:::

<details>
  <summary>More topics</summary>

| Topic                                                    | ID                                                          |
| -------------------------------------------------------- | ----------------------------------------------------------- |
| [AI](https://www.pixelstech.net/feed/ai)                 | [ai](https://rsshub.app/pixelstech/feed/ai)                 |
| [Alibaba](https://www.pixelstech.net/feed/alibaba)       | [alibaba](https://rsshub.app/pixelstech/feed/alibaba)       |
| [Apple](https://www.pixelstech.net/feed/apple)           | [apple](https://rsshub.app/pixelstech/feed/apple)           |
| [Database](https://www.pixelstech.net/feed/database)     | [database](https://rsshub.app/pixelstech/feed/database)     |
| [Go](https://www.pixelstech.net/feed/go)                 | [go](https://rsshub.app/pixelstech/feed/go)                 |
| [Huawei](https://www.pixelstech.net/feed/huawei)         | [huawei](https://rsshub.app/pixelstech/feed/huawei)         |
| [Java](https://www.pixelstech.net/feed/java)             | [java](https://rsshub.app/pixelstech/feed/java)             |
| [JavaScript](https://www.pixelstech.net/feed/javascript) | [javascript](https://rsshub.app/pixelstech/feed/javascript) |
| [Linux](https://www.pixelstech.net/feed/linux)           | [linux](https://rsshub.app/pixelstech/feed/linux)           |
| [LLM](https://www.pixelstech.net/feed/llm)               | [llm](https://rsshub.app/pixelstech/feed/llm)               |
| [Nvidia](https://www.pixelstech.net/feed/nvidia)         | [nvidia](https://rsshub.app/pixelstech/feed/nvidia)         |
| [Python](https://www.pixelstech.net/feed/python)         | [python](https://rsshub.app/pixelstech/feed/python)         |
| [Rust](https://www.pixelstech.net/feed/rust)             | [rust](https://rsshub.app/pixelstech/feed/rust)             |
| [Tesla](https://www.pixelstech.net/feed/tesla)           | [tesla](https://rsshub.app/pixelstech/feed/tesla)           |
| [Web](https://www.pixelstech.net/feed/web)               | [web](https://rsshub.app/pixelstech/feed/web)               |
| [Web3](https://www.pixelstech.net/feed/web3)             | [web3](https://rsshub.app/pixelstech/feed/web3)             |
| [Zig](https://www.pixelstech.net/feed/zig)               | [zig](https://rsshub.app/pixelstech/feed/zig)               |

</details>

## Parameters
- `topic`: {"description": "Topic, all by default", "options": [{"label": "All", "value": ""}, {"label": "AI", "value": "ai"}, {"label": "Alibaba", "value": "alibaba"}, {"label": "Apple", "value": "apple"}, {"label": "Database", "value": "database"}, {"label": "Go", "value": "go"}, {"label": "Huawei", "value": "huawei"}, {"label": "Java", "value": "java"}, {"label": "JavaScript", "value": "javascript"}, {"label": "Linux", "value": "linux"}, {"label": "LLM", "value": "llm"}, {"label": "Nvidia", "value": "nvidia"}, {"label": "Python", "value": "python"}, {"label": "Rust", "value": "rust"}, {"label": "Tesla", "value": "tesla"}, {"label": "Web", "value": "web"}, {"label": "Web3", "value": "web3"}, {"label": "Zig", "value": "zig"}]}


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
  - `www.pixelstech.net/feed/:topic?`
- `target`: `/feed/:topic`
### Rule 2
- `title`: `All`
- `source`:
  - `www.pixelstech.net/feed/`
- `target`: `/feed`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nTo subscribe to [AI](https://www.pixelstech.net/feed/ai), where the source URL is `https://www.pixelstech.net/feed/ai`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/pixelstech/feed/ai`](https://rsshub.app/pixelstech/feed/ai).\n:::\n\n<details>\n  <summary>More topics</summary>\n\n| Topic                                                    | ID                                                          |\n| -------------------------------------------------------- | ----------------------------------------------------------- |\n| [AI](https://www.pixelstech.net/feed/ai)                 | [ai](https://rsshub.app/pixelstech/feed/ai)                 |\n| [Alibaba](https://www.pixelstech.net/feed/alibaba)       | [alibaba](https://rsshub.app/pixelstech/feed/alibaba)       |\n| [Apple](https://www.pixelstech.net/feed/apple)           | [apple](https://rsshub.app/pixelstech/feed/apple)           |\n| [Database](https://www.pixelstech.net/feed/database)     | [database](https://rsshub.app/pixelstech/feed/database)     |\n| [Go](https://www.pixelstech.net/feed/go)                 | [go](https://rsshub.app/pixelstech/feed/go)                 |\n| [Huawei](https://www.pixelstech.net/feed/huawei)         | [huawei](https://rsshub.app/pixelstech/feed/huawei)         |\n| [Java](https://www.pixelstech.net/feed/java)             | [java](https://rsshub.app/pixelstech/feed/java)             |\n| [JavaScript](https://www.pixelstech.net/feed/javascript) | [javascript](https://rsshub.app/pixelstech/feed/javascript) |\n| [Linux](https://www.pixelstech.net/feed/linux)           | [linux](https://rsshub.app/pixelstech/feed/linux)           |\n| [LLM](https://www.pixelstech.net/feed/llm)               | [llm](https://rsshub.app/pixelstech/feed/llm)               |\n| [Nvidia](https://www.pixelstech.net/feed/nvidia)         | [nvidia](https://rsshub.app/pixelstech/feed/nvidia)         |\n| [Python](https://www.pixelstech.net/feed/python)         | [python](https://rsshub.app/pixelstech/feed/python)         |\n| [Rust](https://www.pixelstech.net/feed/rust)             | [rust](https://rsshub.app/pixelstech/feed/rust)             |\n| [Tesla](https://www.pixelstech.net/feed/tesla)           | [tesla](https://rsshub.app/pixelstech/feed/tesla)           |\n| [Web](https://www.pixelstech.net/feed/web)               | [web](https://rsshub.app/pixelstech/feed/web)               |\n| [Web3](https://www.pixelstech.net/feed/web3)             | [web3](https://rsshub.app/pixelstech/feed/web3)             |\n| [Zig](https://www.pixelstech.net/feed/zig)               | [zig](https://rsshub.app/pixelstech/feed/zig)               |\n\n</details>",
  "example": "/pixelstech/feed/ai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Feed",
  "parameters": {
    "topic": {
      "description": "Topic, all by default",
      "options": [
        {
          "label": "All",
          "value": ""
        },
        {
          "label": "AI",
          "value": "ai"
        },
        {
          "label": "Alibaba",
          "value": "alibaba"
        },
        {
          "label": "Apple",
          "value": "apple"
        },
        {
          "label": "Database",
          "value": "database"
        },
        {
          "label": "Go",
          "value": "go"
        },
        {
          "label": "Huawei",
          "value": "huawei"
        },
        {
          "label": "Java",
          "value": "java"
        },
        {
          "label": "JavaScript",
          "value": "javascript"
        },
        {
          "label": "Linux",
          "value": "linux"
        },
        {
          "label": "LLM",
          "value": "llm"
        },
        {
          "label": "Nvidia",
          "value": "nvidia"
        },
        {
          "label": "Python",
          "value": "python"
        },
        {
          "label": "Rust",
          "value": "rust"
        },
        {
          "label": "Tesla",
          "value": "tesla"
        },
        {
          "label": "Web",
          "value": "web"
        },
        {
          "label": "Web3",
          "value": "web3"
        },
        {
          "label": "Zig",
          "value": "zig"
        }
      ]
    }
  },
  "path": "/feed/:topic?",
  "radar": [
    {
      "source": [
        "www.pixelstech.net/feed/:topic?"
      ],
      "target": "/feed/:topic"
    },
    {
      "source": [
        "www.pixelstech.net/feed/"
      ],
      "target": "/feed",
      "title": "All"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Latest Ai programming news, tutorials and articles. Stay updated with Ai development trends, coding tips, and technical insights for developers. - Powered by RSSHub",
      "errorAt": "2026-05-02T18:01:31.187Z",
      "errorMessage": "[GET] \"https://www.pixelstech.net/feed/ai\": 403 Forbidden\n",
      "id": "198999405359780864",
      "image": "https://www.pixelstech.net/images/feed/thumbnail/ai-128.png",
      "ownerUserId": null,
      "siteUrl": "https://www.pixelstech.net/feed/ai",
      "title": "AI Feed | PixelsTech",
      "type": "feed",
      "url": "rsshub://pixelstech/feed/ai"
    }
  ],
  "url": "www.pixelstech.net",
  "view": 0
}
```
