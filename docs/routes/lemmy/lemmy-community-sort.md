# Lemmy - Community

## Coverage
`index-only`

## Route
- Namespace: `lemmy`
- Namespace Name: `Lemmy`
- Route Path: `/lemmy/:community/:sort?`
- Route Name: `Community`
- Example: `/lemmy/technology@lemmy.world/Hot`
- URL: `join-lemmy.org`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `wb14123, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `community`: Lemmmy community, for example technology@lemmy.world
- `sort`: {"default": "Active", "description": "Sort by", "options": [{"label": "Active", "value": "Active"}, {"label": "Hot", "value": "Hot"}, {"label": "New", "value": "New"}, {"label": "Old", "value": "Old"}, {"label": "TopDay", "value": "TopDay"}, {"label": "TopWeek", "value": "TopWeek"}, {"label": "TopMonth", "value": "TopMonth"}, {"label": "TopYear", "value": "TopYear"}, {"label": "TopAll", "value": "TopAll"}, {"label": "MostComments", "value": "MostComments"}, {"label": "NewComments", "value": "NewComments"}, {"label": "TopHour", "value": "TopHour"}, {"label": "TopSixHour", "value": "TopSixHour"}, {"label": "TopTwelveHour", "value": "TopTwelveHour"}, {"label": "TopThreeMonths", "value": "TopThreeMonths"}, {"label": "TopSixMonths", "value": "TopSixMonths"}, {"label": "TopNineMonths", "value": "TopNineMonths"}, {"label": "Controversial", "value": "Controversial"}, {"label": "Scaled", "value": "Scaled"}]}


## Features
- `requireConfig`: [{"description": "", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/lemmy/technology@lemmy.world/Hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "index.ts",
  "maintainers": [
    "wb14123",
    "pseudoyu"
  ],
  "name": "Community",
  "parameters": {
    "community": "Lemmmy community, for example technology@lemmy.world",
    "sort": {
      "default": "Active",
      "description": "Sort by",
      "options": [
        {
          "label": "Active",
          "value": "Active"
        },
        {
          "label": "Hot",
          "value": "Hot"
        },
        {
          "label": "New",
          "value": "New"
        },
        {
          "label": "Old",
          "value": "Old"
        },
        {
          "label": "TopDay",
          "value": "TopDay"
        },
        {
          "label": "TopWeek",
          "value": "TopWeek"
        },
        {
          "label": "TopMonth",
          "value": "TopMonth"
        },
        {
          "label": "TopYear",
          "value": "TopYear"
        },
        {
          "label": "TopAll",
          "value": "TopAll"
        },
        {
          "label": "MostComments",
          "value": "MostComments"
        },
        {
          "label": "NewComments",
          "value": "NewComments"
        },
        {
          "label": "TopHour",
          "value": "TopHour"
        },
        {
          "label": "TopSixHour",
          "value": "TopSixHour"
        },
        {
          "label": "TopTwelveHour",
          "value": "TopTwelveHour"
        },
        {
          "label": "TopThreeMonths",
          "value": "TopThreeMonths"
        },
        {
          "label": "TopSixMonths",
          "value": "TopSixMonths"
        },
        {
          "label": "TopNineMonths",
          "value": "TopNineMonths"
        },
        {
          "label": "Controversial",
          "value": "Controversial"
        },
        {
          "label": "Scaled",
          "value": "Scaled"
        }
      ]
    }
  },
  "path": "/:community/:sort?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "This is a [most excellent](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3N0NmhuODNib3d3Nzg0OHU2bTFqMXAzNW42Y2JsOTVmenNsNG8ycSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l46CDHTqbmnGZyxKo/giphy.gif) place for technology news and articles. --- ## Our Rules --- 1. Follow the [lemmy.world rules.](https://mastodon.world/about) 2. Only tech related news or articles. 3. Be [excellent to each other!](https://www.youtube.com/watch?v=rph_1DODXDU) 4. Mod approved content bots can post up to 10 articles per day. 5. Threads asking for personal tech support may be deleted. 6. Politics threads may be removed. 7. No memes allowed as posts, OK to post as comments. 8. Only approved bots from the list below, this includes using AI responses and summaries. To ask if your bot can be added please contact a mod. 9. Check for duplicates before posting, duplicates may be removed 10. Accounts 7 days and younger will have their posts automatically removed. --- ## Approved Bots --- - [@L4s@lemmy.world](https://lemmy.world/u/L4s) - [@autotldr@lemmings.world](https://lemmings.world/u/autotldr) - [@PipedLinkBot@feddit.rocks](https://feddit.rocks/u/PipedLinkBot) - [@wikibot@lemmy.world](https://lemmy.world/u/wikibot) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61702651840877568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lemmy.world/c/technology",
      "title": "technology@lemmy.world - Active posts",
      "type": "feed",
      "url": "rsshub://lemmy/technology%40lemmy.world"
    },
    {
      "description": "This is a [most excellent](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3N0NmhuODNib3d3Nzg0OHU2bTFqMXAzNW42Y2JsOTVmenNsNG8ycSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l46CDHTqbmnGZyxKo/giphy.gif) place for technology news and articles. --- ## Our Rules --- 1. Follow the [lemmy.world rules.](https://mastodon.world/about) 2. Only tech related news or articles. 3. Be [excellent to each other!](https://www.youtube.com/watch?v=rph_1DODXDU) 4. Mod approved content bots can post up to 10 articles per day. 5. Threads asking for personal tech support may be deleted. 6. Politics threads may be removed. 7. No memes allowed as posts, OK to post as comments. 8. Only approved bots from the list below, this includes using AI responses and summaries. To ask if your bot can be added please contact a mod. 9. Check for duplicates before posting, duplicates may be removed 10. Accounts 7 days and younger will have their posts automatically removed. --- ## Approved Bots --- - [@L4s@lemmy.world](https://lemmy.world/u/L4s) - [@autotldr@lemmings.world](https://lemmings.world/u/autotldr) - [@PipedLinkBot@feddit.rocks](https://feddit.rocks/u/PipedLinkBot) - [@wikibot@lemmy.world](https://lemmy.world/u/wikibot) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67488077733605376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lemmy.world/c/technology",
      "title": "technology@lemmy.world - Hot posts",
      "type": "feed",
      "url": "rsshub://lemmy/technology@lemmy.world/Hot"
    }
  ]
}
```
