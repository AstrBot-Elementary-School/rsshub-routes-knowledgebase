# ScienceDirect - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `sciencedirect`
- Namespace Name: `ScienceDirect`
- Route Path: `/sciencedirect/journal/:id/current`
- Route Name: `Current Issue`
- Example: `/sciencedirect/journal/journal-of-financial-economics/current`
- URL: `sciencedirect.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `current-issue.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Journal id, can be found in URL


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
  - `sciencedirect.com/journal/:id`
  - `sciencedirect.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/sciencedirect/journal/journal-of-financial-economics/current",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "current-issue.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Current Issue",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id/current",
  "radar": [
    {
      "source": [
        "sciencedirect.com/journal/:id",
        "sciencedirect.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "<p><i>Computers & Education</i> aims to increase knowledge and understanding of ways in which digital technology can enhance education, through the publication of high-quality research, which extends theory and practice. The Editors welcome research papers on the pedagogical uses of digital technology, where the focus is broad enough to be of interest to a wider education community.</p><p>We do not publish small-scale evaluations of specific software/systems in specialist domains or particular courses in individual institutions (unless the findings have broader relevance that is explicitly drawn out in the paper). Papers that include discussions of the implementation of software and/or hardware should focus on the context of use, the user/system interface, usability issues and evaluations of the user experience and impacts on and particularly on the implications for learning and teaching. Computers as a delivery platform only is insufficient. Detailed information on implementation architecture should NOT be included in the paper, but may be provided via URLs.</p><p>We welcome systematic review papers and meta-analyses that include clear research questions, a framework of analysis, and conclusions that reflect the aims of the paper. See <a href=\"http://www.prisma-statement.org/\">PRISMA guidelines</a> for further advice.</p><p>Authors should take care to refer to and abide by the author guidelines. Papers that do not address the criteria outlined in the author guidelines will be returned without review. <br/> Authors are also welcome to submit to the journal's open access companion titles, <a href=\"https://www.journals.elsevier.com/computers-and-education-open/\">Computers & Education Open</a> or <a href=\"https://www.journals.elsevier.com/computers-and-education-artificial-intelligence\">Computers & Education: Artificial Intelligence</a>.</p> - Powered by RSSHub",
      "errorAt": "2025-11-28T07:52:33.306Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/journal/computers-and-education\": 403 Forbidden\n",
      "id": "129868828817993728",
      "image": "https://ars.els-cdn.com/content/image/X03601315.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.sciencedirect.com/journal/computers-and-education/vol/242/suppl/C",
      "title": "Computers & Education | Volume 242, (March 2026) | ScienceDirect.com by Elsevier",
      "type": "feed",
      "url": "rsshub://sciencedirect/journal/computers-and-education/current"
    },
    {
      "description": "<p>The Official Journal of the <a href=\"http://hevra.haifa.ac.il/rc28/\">ISA RC28</a> on Social Stratification and Mobility</p><p>The study of <b>social inequality</b> is and has been one of the central preoccupations of social scientists. <i>Research in Social Stratification and Mobility</i> is dedicated to publishing the highest, most innovative research on issues of social inequality from a broad diversity of theoretical and methodological perspectives. The journal is also dedicated to cutting edge summaries of prior research and fruitful exchanges that will stimulate future research on issues of social inequality.</p><p><b>Benefits to authors</b> <br/> We also provide many author benefits, such as free PDFs, a liberal copyright policy, special discounts on Elsevier publications and much more. Please click here for more information on our <a href=\"https://www.elsevier.com/authors/author-services\">author services</a>.</p><p>Please see our <a href=\"https://www.elsevier.com/journals/research-in-social-stratification-and-mobility/0276-5624/guide-for-authors\">Guide for Authors</a> for information on article submission. If you require any further information or help, please visit our <a href=\"https://service.elsevier.com/app/home/supporthub/publishing/\">Support Center</a></p> - Powered by RSSHub",
      "errorAt": "2025-11-27T14:25:42.094Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/journal/research-in-social-stratification-and-mobility\": 403 Forbidden\n",
      "id": "183441145151288320",
      "image": "https://ars.els-cdn.com/content/image/X02765624.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.sciencedirect.com/journal/research-in-social-stratification-and-mobility/vol/100/suppl/C",
      "title": "Research in Social Stratification and Mobility | Volume 100, (December 2025) | ScienceDirect.com by Elsevier",
      "type": "feed",
      "url": "rsshub://sciencedirect/journal/research-in-social-stratification-and-mobility/current"
    }
  ]
}
```
