# Kantar Worldpanel - News Centre

## Coverage
`index-only`

## Route
- Namespace: `kantarworldpanel`
- Namespace Name: `Kantar Worldpanel`
- Route Path: `/kantarworldpanel/:region?/:category{.+}?`
- Route Name: `News Centre`
- Example: `/kantarworldpanel/cn-en/news`
- URL: `kantarworldpanel.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| Region      | id    |
| ----------- | ----- |
| China Eng   | cn-en |
| China 中文  | cn    |
| Indonesia   | id    |
| Korea       | kr    |
| Malaysia    | my    |
| Philippines | ph    |
| Taiwan      | tw    |
| Thailand    | th    |
| Vietnam     | vn    |

<details>
  <summary>More categories</summary>

#### China Eng

| News | Retail Snapshot | Publications         | In the media |
| ---- | --------------- | -------------------- | ------------ |
| news | publications    | publications/Reports | In-the-media |

#### China 中文

| 新闻发布 | 零售市场快报 | 市场报告                    | 媒体报道       |
| -------- | ------------ | --------------------------- | -------------- |
| news     | publications | publications/China-Insights | press-releases |

#### Indonesia

| News | Kantar Scoop                  | Video Series      | Podcast      | Ready, Steady, Shop!     | Asia Pulse      |
| ---- | ----------------------------- | ----------------- | ------------ | ------------------------ | --------------- |
| News | News/Kantar-Worldpanel-Series | News/video-series | News/podcast | News/asia-shopper-series | News/Asia-Pulse |

#### Korea

| News | Insight Reports | In the Media   |
| ---- | --------------- | -------------- |
| news | publications    | press-releases |

#### Malaysia

| News |
| ---- |
| news |

#### Philippines

| Latest Insights | In the Media | Events |
| --------------- | ------------ | ------ |
| Latest-Insights | In-the-Media | events |

#### Taiwan

| 聚焦台灣                 | WOW SPOT     | 市場報告     | 媒體報導       | 活動   |
| ------------------------ | ------------ | ------------ | -------------- | ------ |
| news/spotlight-on-taiwan | news/wowspot | publications | press-releases | events |

#### Thailand

| News |
| ---- |
| news |

#### Vietnam

| Insights | FMCG Monitor      | Ready, Steady, Shop!   | Asia Pulse      | IN THE MEDIA |
| -------- | ----------------- | ---------------------- | --------------- | ------------ |
| news     | news/FMCG-Monitor | news/ready-steady-shop | news/asia-pulse | In-the-media |

</details>

## Parameters
- `region`: Region id, see below, Chinese Mainland English by default
- `category`: Category, can be found in URL, News by default


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
  "description": "| Region      | id    |\n| ----------- | ----- |\n| China Eng   | cn-en |\n| China 中文  | cn    |\n| Indonesia   | id    |\n| Korea       | kr    |\n| Malaysia    | my    |\n| Philippines | ph    |\n| Taiwan      | tw    |\n| Thailand    | th    |\n| Vietnam     | vn    |\n\n<details>\n  <summary>More categories</summary>\n\n#### China Eng\n\n| News | Retail Snapshot | Publications         | In the media |\n| ---- | --------------- | -------------------- | ------------ |\n| news | publications    | publications/Reports | In-the-media |\n\n#### China 中文\n\n| 新闻发布 | 零售市场快报 | 市场报告                    | 媒体报道       |\n| -------- | ------------ | --------------------------- | -------------- |\n| news     | publications | publications/China-Insights | press-releases |\n\n#### Indonesia\n\n| News | Kantar Scoop                  | Video Series      | Podcast      | Ready, Steady, Shop!     | Asia Pulse      |\n| ---- | ----------------------------- | ----------------- | ------------ | ------------------------ | --------------- |\n| News | News/Kantar-Worldpanel-Series | News/video-series | News/podcast | News/asia-shopper-series | News/Asia-Pulse |\n\n#### Korea\n\n| News | Insight Reports | In the Media   |\n| ---- | --------------- | -------------- |\n| news | publications    | press-releases |\n\n#### Malaysia\n\n| News |\n| ---- |\n| news |\n\n#### Philippines\n\n| Latest Insights | In the Media | Events |\n| --------------- | ------------ | ------ |\n| Latest-Insights | In-the-Media | events |\n\n#### Taiwan\n\n| 聚焦台灣                 | WOW SPOT     | 市場報告     | 媒體報導       | 活動   |\n| ------------------------ | ------------ | ------------ | -------------- | ------ |\n| news/spotlight-on-taiwan | news/wowspot | publications | press-releases | events |\n\n#### Thailand\n\n| News |\n| ---- |\n| news |\n\n#### Vietnam\n\n| Insights | FMCG Monitor      | Ready, Steady, Shop!   | Asia Pulse      | IN THE MEDIA |\n| -------- | ----------------- | ---------------------- | --------------- | ------------ |\n| news     | news/FMCG-Monitor | news/ready-steady-shop | news/asia-pulse | In-the-media |\n\n</details>",
  "example": "/kantarworldpanel/cn-en/news",
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News Centre",
  "parameters": {
    "category": "Category, can be found in URL, News by default",
    "region": "Region id, see below, Chinese Mainland English by default"
  },
  "path": "/:region?/:category{.+}?",
  "topFeeds": []
}
```
