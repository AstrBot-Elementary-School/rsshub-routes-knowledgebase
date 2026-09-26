# Fortnite - News

## Coverage
`index-only`

## Route
- Namespace: `fortnite`
- Namespace Name: `Fortnite`
- Route Path: `/fortnite/news/:options?`
- Route Name: `News`
- Example: `/fortnite/news`
- URL: `www.fortnite.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `lyqluis`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
- `lang`, default `en-US`, one of `ar`, `de`, `en-US`, `es-ES`, `es-MX`, `fr`, `it`, `ja`, `ko`, `pl`, `pt-BR`, `ru`, `tr`, `zh-Hans`
- `tag`, optional, one of `battle-royale` (Battle Royale), `fortnite-competitive` (Fortnite Competitive), `fortnite-festival` (Fortnite Festival), `fortnite-news` (Fortnite News), `fortnite-og` (Fortnite OG), `fortnite-uefn-and-creative` (UEFN and Creative), `lego-fortnite` (LEGO Fortnite Odyssey), `lego-fortnite-brick-life` (LEGO Fortnite Brick Life), `ranked` (Ranked Battle Royale), `reload` (Reload), `rocket-racing` (Rocket Racing), `save-the-world` (Save the World)

## Parameters
- `options`: Query-style options, `lang` and `tag`, see below


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
  - `www.fortnite.com/news`
- `target`: `/news`
### Rule 2
- `source`:
  - `www.fortnite.com/news/tag/:tag`
- `target`: `/news/tag=:tag`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "- `lang`, default `en-US`, one of `ar`, `de`, `en-US`, `es-ES`, `es-MX`, `fr`, `it`, `ja`, `ko`, `pl`, `pt-BR`, `ru`, `tr`, `zh-Hans`\n- `tag`, optional, one of `battle-royale` (Battle Royale), `fortnite-competitive` (Fortnite Competitive), `fortnite-festival` (Fortnite Festival), `fortnite-news` (Fortnite News), `fortnite-og` (Fortnite OG), `fortnite-uefn-and-creative` (UEFN and Creative), `lego-fortnite` (LEGO Fortnite Odyssey), `lego-fortnite-brick-life` (LEGO Fortnite Brick Life), `ranked` (Ranked Battle Royale), `reload` (Reload), `rocket-racing` (Rocket Racing), `save-the-world` (Save the World)",
  "example": "/fortnite/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "news.ts",
  "maintainers": [
    "lyqluis"
  ],
  "name": "News",
  "parameters": {
    "options": "Query-style options, `lang` and `tag`, see below"
  },
  "path": "/news/:options?",
  "radar": [
    {
      "source": [
        "www.fortnite.com/news"
      ],
      "target": "/news"
    },
    {
      "source": [
        "www.fortnite.com/news/tag/:tag"
      ],
      "target": "/news/tag=:tag"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Fortnite News - Powered by RSSHub",
      "errorAt": "2025-05-15T04:29:52.956Z",
      "errorMessage": "[GET] \"https://www.fortnite.com/news.data?lang=en-US\": 403 Forbidden\n",
      "id": "68983907798491136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fortnite.com/news?lang=en-US",
      "title": "Fortnite News",
      "type": "feed",
      "url": "rsshub://fortnite/news"
    }
  ],
  "url": "www.fortnite.com/news"
}
```
