# Grist - Topic

## Coverage
`index-only`

## Route
- Namespace: `grist`
- Namespace Name: `Grist`
- Route Path: `/grist/topic/:topic`
- Route Name: `Topic`
- Example: `/grist/topic/extreme-heat`
- URL: `grist.org/articles/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Rjnishant530`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
Topics

| Topic Name               | Topic Link         |
| ------------------------ | ------------------ |
| Accountability           | accountability     |
| Agriculture              | agriculture        |
| Ask Umbra                | ask-umbra-series   |
| Buildings                | buildings          |
| Cities                   | cities             |
| Climate & Energy         | climate-energy     |
| Climate Fiction          | climate-fiction    |
| Climate of Courage       | climate-of-courage |
| COP26                    | cop26              |
| COP27                    | cop27              |
| Culture                  | culture            |
| Economics                | economics          |
| Energy                   | energy             |
| Equity                   | equity             |
| Extreme Weather          | extreme-weather    |
| Fix                      | fix                |
| Food                     | food               |
| Grist                    | grist              |
| Grist News               | grist-news         |
| Health                   | health             |
| Housing                  | housing            |
| Indigenous Affairs       | indigenous         |
| International            | international      |
| Labor                    | labor              |
| Language                 | language           |
| Migration                | migration          |
| Opinion                  | opinion            |
| Politics                 | politics           |
| Protest                  | protest            |
| Race                     | race               |
| Regulation               | regulation         |
| Science                  | science            |
| Shift Happens Newsletter | shift-happens      |
| Solutions                | solutions          |
| Spanish                  | spanish            |
| Sponsored                | sponsored          |
| Technology               | technology         |
| Temperature Check        | temperature-check  |
| Uncategorized            | article            |
| Updates                  | updates            |
| Video                    | video              |

## Parameters
- `topic`: Any Topic from Table below


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
  - `grist.org/:topic`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Topics\n\n| Topic Name               | Topic Link         |\n| ------------------------ | ------------------ |\n| Accountability           | accountability     |\n| Agriculture              | agriculture        |\n| Ask Umbra                | ask-umbra-series   |\n| Buildings                | buildings          |\n| Cities                   | cities             |\n| Climate & Energy         | climate-energy     |\n| Climate Fiction          | climate-fiction    |\n| Climate of Courage       | climate-of-courage |\n| COP26                    | cop26              |\n| COP27                    | cop27              |\n| Culture                  | culture            |\n| Economics                | economics          |\n| Energy                   | energy             |\n| Equity                   | equity             |\n| Extreme Weather          | extreme-weather    |\n| Fix                      | fix                |\n| Food                     | food               |\n| Grist                    | grist              |\n| Grist News               | grist-news         |\n| Health                   | health             |\n| Housing                  | housing            |\n| Indigenous Affairs       | indigenous         |\n| International            | international      |\n| Labor                    | labor              |\n| Language                 | language           |\n| Migration                | migration          |\n| Opinion                  | opinion            |\n| Politics                 | politics           |\n| Protest                  | protest            |\n| Race                     | race               |\n| Regulation               | regulation         |\n| Science                  | science            |\n| Shift Happens Newsletter | shift-happens      |\n| Solutions                | solutions          |\n| Spanish                  | spanish            |\n| Sponsored                | sponsored          |\n| Technology               | technology         |\n| Temperature Check        | temperature-check  |\n| Uncategorized            | article            |\n| Updates                  | updates            |\n| Video                    | video              |",
  "example": "/grist/topic/extreme-heat",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "topic.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Topic",
  "parameters": {
    "topic": "Any Topic from Table below"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "grist.org/:topic"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Extreme-heat Articles on grist.org - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87131229876341760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://grist.org/extreme-heat",
      "title": "Extreme-heat - Gist Articles",
      "type": "feed",
      "url": "rsshub://grist/topic/extreme-heat"
    },
    {
      "description": "Culture Articles on grist.org - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "108633066455945216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://grist.org/culture",
      "title": "Culture - Gist Articles",
      "type": "feed",
      "url": "rsshub://grist/topic/culture"
    }
  ],
  "url": "grist.org/articles/"
}
```
