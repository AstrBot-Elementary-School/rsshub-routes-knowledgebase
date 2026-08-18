# YouTube - Music Charts

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/charts/:category?/:country?/:embed?`
- Route Name: `Music Charts`
- Example: `/youtube/charts`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `charts.ts`
- Source Module: `_None_`

## Description
Chart

| Top artists | Top songs | Top music videos | Trending       |
| ----------- | --------- | ---------------- | -------------- |
| TopArtists  | TopSongs  | TopVideos        | TrendingVideos |

Country Code

| Argentina | Australia | Austria | Belgium | Bolivia | Brazil | Canada |
| --------- | --------- | ------- | ------- | ------- | ------ | ------ |
| ar        | au        | at      | be      | bo      | br     | ca     |

| Chile | Colombia | Costa Rica | Czechia | Denmark | Dominican Republic | Ecuador |
| ----- | -------- | ---------- | ------- | ------- | ------------------ | ------- |
| cl    | co       | cr         | cz      | dk      | do                 | ec      |

| Egypt | El Salvador | Estonia | Finland | France | Germany | Guatemala |
| ----- | ----------- | ------- | ------- | ------ | ------- | --------- |
| eg    | sv          | ee      | fi      | fr     | de      | gt        |

| Honduras | Hungary | Iceland | India | Indonesia | Ireland | Israel | Italy |
| -------- | ------- | ------- | ----- | --------- | ------- | ------ | ----- |
| hn       | hu      | is      | in    | id        | ie      | il     | it    |

| Japan | Kenya | Luxembourg | Mexico | Netherlands | New Zealand | Nicaragua |
| ----- | ----- | ---------- | ------ | ----------- | ----------- | --------- |
| jp    | ke    | lu         | mx     | nl          | nz          | ni        |

| Nigeria | Norway | Panama | Paraguay | Peru | Poland | Portugal | Romania |
| ------- | ------ | ------ | -------- | ---- | ------ | -------- | ------- |
| ng      | no     | pa     | py       | pe   | pl     | pt       | ro      |

| Russia | Saudi Arabia | Serbia | South Africa | South Korea | Spain | Sweden | Switzerland |
| ------ | ------------ | ------ | ------------ | ----------- | ----- | ------ | ----------- |
| ru     | sa           | rs     | za           | kr          | es    | se     | ch          |

| Tanzania | Turkey | Uganda | Ukraine | United Arab Emirates | United Kingdom | United States |
| -------- | ------ | ------ | ------- | -------------------- | -------------- | ------------- |
| tz       | tr     | ug     | ua      | ae                   | gb             | us            |

| Uruguay | Zimbabwe |
| ------- | -------- |
| uy      | zw       |

## Parameters
- `category`: Chart, see table below, default to `TopVideos`
- `country`: Country Code, see table below, default to global
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Chart\n\n| Top artists | Top songs | Top music videos | Trending       |\n| ----------- | --------- | ---------------- | -------------- |\n| TopArtists  | TopSongs  | TopVideos        | TrendingVideos |\n\nCountry Code\n\n| Argentina | Australia | Austria | Belgium | Bolivia | Brazil | Canada |\n| --------- | --------- | ------- | ------- | ------- | ------ | ------ |\n| ar        | au        | at      | be      | bo      | br     | ca     |\n\n| Chile | Colombia | Costa Rica | Czechia | Denmark | Dominican Republic | Ecuador |\n| ----- | -------- | ---------- | ------- | ------- | ------------------ | ------- |\n| cl    | co       | cr         | cz      | dk      | do                 | ec      |\n\n| Egypt | El Salvador | Estonia | Finland | France | Germany | Guatemala |\n| ----- | ----------- | ------- | ------- | ------ | ------- | --------- |\n| eg    | sv          | ee      | fi      | fr     | de      | gt        |\n\n| Honduras | Hungary | Iceland | India | Indonesia | Ireland | Israel | Italy |\n| -------- | ------- | ------- | ----- | --------- | ------- | ------ | ----- |\n| hn       | hu      | is      | in    | id        | ie      | il     | it    |\n\n| Japan | Kenya | Luxembourg | Mexico | Netherlands | New Zealand | Nicaragua |\n| ----- | ----- | ---------- | ------ | ----------- | ----------- | --------- |\n| jp    | ke    | lu         | mx     | nl          | nz          | ni        |\n\n| Nigeria | Norway | Panama | Paraguay | Peru | Poland | Portugal | Romania |\n| ------- | ------ | ------ | -------- | ---- | ------ | -------- | ------- |\n| ng      | no     | pa     | py       | pe   | pl     | pt       | ro      |\n\n| Russia | Saudi Arabia | Serbia | South Africa | South Korea | Spain | Sweden | Switzerland |\n| ------ | ------------ | ------ | ------------ | ----------- | ----- | ------ | ----------- |\n| ru     | sa           | rs     | za           | kr          | es    | se     | ch          |\n\n| Tanzania | Turkey | Uganda | Ukraine | United Arab Emirates | United Kingdom | United States |\n| -------- | ------ | ------ | ------- | -------------------- | -------------- | ------------- |\n| tz       | tr     | ug     | ua      | ae                   | gb             | us            |\n\n| Uruguay | Zimbabwe |\n| ------- | -------- |\n| uy      | zw       |",
  "example": "/youtube/charts",
  "heat": 38,
  "location": "charts.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Music Charts",
  "parameters": {
    "category": "Chart, see table below, default to `TopVideos`",
    "country": "Country Code, see table below, default to global",
    "embed": "Default to embed the video, set to any value to disable embedding"
  },
  "path": "/charts/:category?/:country?/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "YouTube Music Charts - Top music videos - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57506261522656256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://charts.youtube.com/charts/TopVideos/global",
      "title": "YouTube Music Charts - Top music videos",
      "type": "feed",
      "url": "rsshub://youtube/charts"
    },
    {
      "description": "YouTube Music Charts - Top songs - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57503645768295424",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://charts.youtube.com/charts/TopSongs/global",
      "title": "YouTube Music Charts - Top songs",
      "type": "feed",
      "url": "rsshub://youtube/charts/TopSongs"
    }
  ]
}
```
