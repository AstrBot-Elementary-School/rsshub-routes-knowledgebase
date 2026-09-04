# Notefolio - Works

## Coverage
`index-only`

## Route
- Namespace: `notefolio`
- Namespace Name: `Notefolio`
- Route Path: `/notefolio/search/:category?/:order?/:time?/:query?`
- Route Name: `Works`
- Example: `/notefolio/search/1/pick/all/life`
- URL: `notefolio.net/search`
- Language: `_None_`
- Categories: `design`
- Maintainers: `BianTan`
- Source Location: `search.tsx`
- Source Module: `_None_`

## Description
| Category | Name in Korean     | Name in English         |
| -------- | ------------------ | ----------------------- |
| all      | 전체               | All                     |
| 1        | 영상/모션그래픽    | Video / Motion Graphics |
| 2        | 그래픽 디자인      | Graphic Design          |
| 3        | 브랜딩/편집        | Branding / Editing      |
| 4        | UI/UX              | UI/UX                   |
| 5        | 일러스트레이션     | Illustration            |
| 6        | 디지털 아트        | Digital Art             |
| 7        | 캐릭터 디자인      | Character Design        |
| 8        | 제품/패키지 디자인 | Product Package Design  |
| 9        | 포토그래피         | Photography             |
| 10       | 타이포그래피       | Typography              |
| 11       | 공예               | Crafts                  |
| 12       | 파인아트           | Fine Art                |

## Parameters
- `category`: {"default": "all", "description": "Category, see below", "options": [{"label": "All (전체)", "value": "all"}, {"label": "Video / Motion Graphics (영상/모션그래픽)", "value": "1"}, {"label": "Graphic Design (그래픽 디자인)", "value": "2"}, {"label": "Branding / Editing (브랜딩/편집)", "value": "3"}, {"label": "UI/UX (UI/UX)", "value": "4"}, {"label": "Illustration (일러스트레이션)", "value": "5"}, {"label": "Digital Art (디지털 아트)", "value": "6"}, {"label": "Character Design (캐릭터 디자인)", "value": "7"}, {"label": "Product Package Design (제품/패키지 디자인)", "value": "8"}, {"label": "Photography (포토그래피)", "value": "9"}, {"label": "Typography (타이포그래피)", "value": "10"}, {"label": "Crafts (공예)", "value": "11"}, {"label": "Fine Art (파인아트)", "value": "12"}]}
- `order`: {"default": "pick", "description": "Order, `pick` as Notefolio Pick, `published` as Newest, `like` as like, `pick` by default", "options": [{"label": "Notefolio Pick", "value": "pick"}, {"label": "Newest", "value": "published"}, {"label": "Like", "value": "like"}]}
- `time`: {"default": "all", "description": "Time", "options": [{"label": "All the time", "value": "all"}, {"label": "Latest 24 hours", "value": "one-day"}, {"label": "Latest week", "value": "week"}, {"label": "Latest month", "value": "month"}, {"label": "Latest 3 months", "value": "three-month"}]}
- `query`: Keyword, empty by default


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
  - `notefolio.net/search`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "| Category | Name in Korean     | Name in English         |\n| -------- | ------------------ | ----------------------- |\n| all      | 전체               | All                     |\n| 1        | 영상/모션그래픽    | Video / Motion Graphics |\n| 2        | 그래픽 디자인      | Graphic Design          |\n| 3        | 브랜딩/편집        | Branding / Editing      |\n| 4        | UI/UX              | UI/UX                   |\n| 5        | 일러스트레이션     | Illustration            |\n| 6        | 디지털 아트        | Digital Art             |\n| 7        | 캐릭터 디자인      | Character Design        |\n| 8        | 제품/패키지 디자인 | Product Package Design  |\n| 9        | 포토그래피         | Photography             |\n| 10       | 타이포그래피       | Typography              |\n| 11       | 공예               | Crafts                  |\n| 12       | 파인아트           | Fine Art                |",
  "example": "/notefolio/search/1/pick/all/life",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 272,
  "location": "search.tsx",
  "maintainers": [
    "BianTan"
  ],
  "name": "Works",
  "parameters": {
    "category": {
      "default": "all",
      "description": "Category, see below",
      "options": [
        {
          "label": "All (전체)",
          "value": "all"
        },
        {
          "label": "Video / Motion Graphics (영상/모션그래픽)",
          "value": "1"
        },
        {
          "label": "Graphic Design (그래픽 디자인)",
          "value": "2"
        },
        {
          "label": "Branding / Editing (브랜딩/편집)",
          "value": "3"
        },
        {
          "label": "UI/UX (UI/UX)",
          "value": "4"
        },
        {
          "label": "Illustration (일러스트레이션)",
          "value": "5"
        },
        {
          "label": "Digital Art (디지털 아트)",
          "value": "6"
        },
        {
          "label": "Character Design (캐릭터 디자인)",
          "value": "7"
        },
        {
          "label": "Product Package Design (제품/패키지 디자인)",
          "value": "8"
        },
        {
          "label": "Photography (포토그래피)",
          "value": "9"
        },
        {
          "label": "Typography (타이포그래피)",
          "value": "10"
        },
        {
          "label": "Crafts (공예)",
          "value": "11"
        },
        {
          "label": "Fine Art (파인아트)",
          "value": "12"
        }
      ]
    },
    "order": {
      "default": "pick",
      "description": "Order, `pick` as Notefolio Pick, `published` as Newest, `like` as like, `pick` by default",
      "options": [
        {
          "label": "Notefolio Pick",
          "value": "pick"
        },
        {
          "label": "Newest",
          "value": "published"
        },
        {
          "label": "Like",
          "value": "like"
        }
      ]
    },
    "query": "Keyword, empty by default",
    "time": {
      "default": "all",
      "description": "Time",
      "options": [
        {
          "label": "All the time",
          "value": "all"
        },
        {
          "label": "Latest 24 hours",
          "value": "one-day"
        },
        {
          "label": "Latest week",
          "value": "week"
        },
        {
          "label": "Latest month",
          "value": "month"
        },
        {
          "label": "Latest 3 months",
          "value": "three-month"
        }
      ]
    }
  },
  "path": "/search/:category?/:order?/:time?/:query?",
  "radar": [
    {
      "source": [
        "notefolio.net/search"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "all/pick/all/ search - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72683914070868992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "all/pick/all/ search",
      "type": "feed",
      "url": "rsshub://notefolio/search/all/pick/all"
    },
    {
      "description": "4/pick/all/ search - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80060928310239232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "4/pick/all/ search",
      "type": "feed",
      "url": "rsshub://notefolio/search/4/pick/all"
    }
  ],
  "url": "notefolio.net/search",
  "view": 2
}
```
