# The Indian Express - Section

## Coverage
`index-only`

## Route
- Namespace: `indianexpress`
- Namespace Name: `The Indian Express`
- Route Path: `/indianexpress/section/:id{.+}?`
- Route Name: `Section`
- Example: `/indianexpress/section/explained`
- URL: `indianexpress.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `section.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Section](https://indianexpress.com/), where the source URL is `https://indianexpress.com/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/indianexpress/section/explained`](https://rsshub.app/indianexpress/section/explained).
:::

## Parameters
- `id`: {"description": "Section ID, `trending` as Trending by default"}


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
  - `indianexpress.com/section/:id`
- `target`: `/section/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nTo subscribe to [Section](https://indianexpress.com/), where the source URL is `https://indianexpress.com/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/indianexpress/section/explained`](https://rsshub.app/indianexpress/section/explained).\n:::",
  "example": "/indianexpress/section/explained",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 6,
  "location": "section.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Section",
  "parameters": {
    "id": {
      "description": "Section ID, `trending` as Trending by default"
    }
  },
  "path": "/section/:id{.+}?",
  "radar": [
    {
      "source": [
        "indianexpress.com/section/:id"
      ],
      "target": "/section/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Indian Express Explained: Check here latest India and world news explained, current affairs today, latest current affairs news. Read expert opinion, facts and research on india and international trending news at indianexpress.com. The Explained section of The Indian Express helps you make sense of everything that is happening in the world around you. We pick important developments from within India and outside and break them down, giving you all the information and context you need in an easy-to-follow format. The section is subdivided into Explained Economics, Explained Health, Culture, Global, Sports, Ideas, Sci-tech, and Climate. We have also recently begun an Explained Law subsection. Apart from these, an 'Everyday Explainers' section gives you crisp answers to seemingly simple, everyday questions you might have, such as how is the President of India elected, how is your vote counted, what is a narco test, what is ASEAN, what is a Vostro account, etc. Our writers include Nirupama Subramanian, Harish Damodaran, Shubhajit Roy, Udit Misra, Amitabh Sinha, Shyamlal Yadav, Sandeep Dwivedi, among others, who bring to you expertise built over decades of covering their beats. Why should you read The Indian Express Explained? Because in the internet age, it is easy to be bombarded with news, but at Explained, the constant stream of news and noise is distilled into clear, concise, well-researched, accurate, and unbiased information. If you are preparing for a competitive exam such as the UPSC CSE, The Indian Express Explained is where you will find everything you need to know, with all important topics in the news covered in adequate detail. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197289166403892224",
      "image": "https://indianexpress.com/wp-content/themes/indianexpress/images/IE-OGimage.jpg",
      "ownerUserId": null,
      "siteUrl": "https://indianexpress.com/section/explained/",
      "title": "The Indian Express - Explained",
      "type": "feed",
      "url": "rsshub://indianexpress/section/explained"
    },
    {
      "description": "Trending News: Check all the latest trending news, latest viral videos, viral memes, world top trending news, Today's trending events, latest fashion trends only at indianexpress.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "237366416633358336",
      "image": "https://indianexpress.com/wp-content/themes/indianexpress/images/IE-OGimage.jpg",
      "ownerUserId": null,
      "siteUrl": "https://indianexpress.com/section/trending/",
      "title": "The Indian Express - Trending",
      "type": "feed",
      "url": "rsshub://indianexpress/section/trending"
    }
  ],
  "url": "indianexpress.com",
  "view": 0
}
```
