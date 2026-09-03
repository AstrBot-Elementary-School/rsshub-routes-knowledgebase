# Reuters - Category/Topic/Author

## Coverage
`index-only`

## Route
- Namespace: `reuters`
- Namespace Name: `Reuters`
- Route Path: `/reuters/:category/:topic?`
- Route Name: `Category/Topic/Author`
- Example: `/reuters/world/us`
- URL: `reuters.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `LyleLee, HenryQW, proletarius101, black-desk, nczitzk, pseudoyu`
- Source Location: `common.tsx`
- Source Module: `_None_`

## Description
- `:category`:

  | World | Business | Legal | Markets | Breakingviews | Technology | Graphics |
  | ----- | -------- | ----- | ------- | ------------- | ---------- | -------- |
  | world | business | legal | markets | breakingviews | technology | graphics |

- `world/:topic`:

  | All | Africa | Americas | Asia Pacific | China | Europe | India | Middle East | United Kingdom | United States | The Great Reboot | Reuters Next |
  | --- | ------ | -------- | ------------ | ----- | ------ | ----- | ----------- | -------------- | ------------- | ---------------- | ------------ |
  |     | africa | americas | asia-pacific | china | europe | india | middle-east | uk             | us            | the-great-reboot | reuters-next |

- `business/:topic`:

  | All | Aerospace & Defense | Autos & Transportation | Energy | Environment | Finance | Healthcare & Pharmaceuticals | Media & Telecom | Retail & Consumer | Sustainable Business | Charged | Future of Health | Future of Money | Take Five | Reuters Impact |
  | --- | ------------------- | ---------------------- | ------ | ----------- | ------- | ---------------------------- | --------------- | ----------------- | -------------------- | ------- | ---------------- | --------------- | --------- | -------------- |
  |     | aerospace-defense   | autos-transportation   | energy | environment | finance | healthcare-pharmaceuticals   | media-telecom   | retail-consumer   | sustainable-business | charged | future-of-health | future-of-money | take-five | reuters-impact |

- `legal/:topic`:

  | All | Government | Legal Industry | Litigation | Transactional |
  | --- | ---------- | -------------- | ---------- | ------------- |
  |     | government | legalindustry  | litigation | transactional |

- `authors/:topic`:

  | Default | Jonathan Landay | any other authors |
  | ------- | --------------- | ----------------- |
  | reuters | jonathan-landay | their name in URL |

More could be found in the URL of the category/topic page.

## Parameters
- `category`: {"default": "world", "description": "find it in the URL, or tables below", "options": [{"label": "World", "value": "world"}, {"label": "Business", "value": "business"}, {"label": "Legal", "value": "legal"}, {"label": "Markets", "value": "markets"}, {"label": "Breakingviews", "value": "breakingviews"}, {"label": "Technology", "value": "technology"}, {"label": "Graphics", "value": "graphics"}, {"label": "Authors", "value": "authors"}]}
- `topic`: find it in the URL, or tables below, leave empty for `All`


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
  - `reuters.com/:category/:topic?`
  - `reuters.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "- `:category`:\n\n  | World | Business | Legal | Markets | Breakingviews | Technology | Graphics |\n  | ----- | -------- | ----- | ------- | ------------- | ---------- | -------- |\n  | world | business | legal | markets | breakingviews | technology | graphics |\n\n- `world/:topic`:\n\n  | All | Africa | Americas | Asia Pacific | China | Europe | India | Middle East | United Kingdom | United States | The Great Reboot | Reuters Next |\n  | --- | ------ | -------- | ------------ | ----- | ------ | ----- | ----------- | -------------- | ------------- | ---------------- | ------------ |\n  |     | africa | americas | asia-pacific | china | europe | india | middle-east | uk             | us            | the-great-reboot | reuters-next |\n\n- `business/:topic`:\n\n  | All | Aerospace & Defense | Autos & Transportation | Energy | Environment | Finance | Healthcare & Pharmaceuticals | Media & Telecom | Retail & Consumer | Sustainable Business | Charged | Future of Health | Future of Money | Take Five | Reuters Impact |\n  | --- | ------------------- | ---------------------- | ------ | ----------- | ------- | ---------------------------- | --------------- | ----------------- | -------------------- | ------- | ---------------- | --------------- | --------- | -------------- |\n  |     | aerospace-defense   | autos-transportation   | energy | environment | finance | healthcare-pharmaceuticals   | media-telecom   | retail-consumer   | sustainable-business | charged | future-of-health | future-of-money | take-five | reuters-impact |\n\n- `legal/:topic`:\n\n  | All | Government | Legal Industry | Litigation | Transactional |\n  | --- | ---------- | -------------- | ---------- | ------------- |\n  |     | government | legalindustry  | litigation | transactional |\n\n- `authors/:topic`:\n\n  | Default | Jonathan Landay | any other authors |\n  | ------- | --------------- | ----------------- |\n  | reuters | jonathan-landay | their name in URL |\n\nMore could be found in the URL of the category/topic page.",
  "example": "/reuters/world/us",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6064,
  "location": "common.tsx",
  "maintainers": [
    "LyleLee",
    "HenryQW",
    "proletarius101",
    "black-desk",
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Category/Topic/Author",
  "parameters": {
    "category": {
      "default": "world",
      "description": "find it in the URL, or tables below",
      "options": [
        {
          "label": "World",
          "value": "world"
        },
        {
          "label": "Business",
          "value": "business"
        },
        {
          "label": "Legal",
          "value": "legal"
        },
        {
          "label": "Markets",
          "value": "markets"
        },
        {
          "label": "Breakingviews",
          "value": "breakingviews"
        },
        {
          "label": "Technology",
          "value": "technology"
        },
        {
          "label": "Graphics",
          "value": "graphics"
        },
        {
          "label": "Authors",
          "value": "authors"
        }
      ]
    },
    "topic": "find it in the URL, or tables below, leave empty for `All`"
  },
  "path": "/:category/:topic?",
  "radar": [
    {
      "source": [
        "reuters.com/:category/:topic?",
        "reuters.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Follow the latest international and world news, breaking stories and global current events from your trusted online news source. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42371779203556352",
      "image": "https://www.reuters.com/pf/resources/images/reuters/logo-vertical-default-512x512.png?d=116",
      "ownerUserId": null,
      "siteUrl": "https://www.reuters.com/world/",
      "title": "World News | Latest Top Stories | Reuters",
      "type": "feed",
      "url": "rsshub://reuters/world"
    },
    {
      "description": "Reuters.com is your online source for the latest China news stories and current events, ensuring our readers up to date with any breaking news developments - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41479290346361856",
      "image": "https://www.reuters.com/pf/resources/images/reuters/logo-vertical-default-512x512.png?d=116",
      "ownerUserId": null,
      "siteUrl": "https://www.reuters.com/world/china/",
      "title": "China News | Today's Breaking Stories | Reuters",
      "type": "feed",
      "url": "rsshub://reuters/world/china"
    }
  ],
  "view": 0
}
```
