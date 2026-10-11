# LinkedIn - Jobs

## Coverage
`index-only`

## Route
- Namespace: `linkedin`
- Namespace Name: `LinkedIn`
- Route Path: `/linkedin/jobs/:job_types/:exp_levels/:keywords?/:routeParams?`
- Route Name: `Jobs`
- Example: `/linkedin/jobs/C-P/1/software engineer`
- URL: `linkedin.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `BrandNewLifeJackie26, zhoukuncheng`
- Source Location: `jobs.ts`
- Source Module: `_None_`

## Description
#### `job_types` list

| Full Time | Part Time | Contractor | All |
| --------- | --------- | ---------- | --- |
| F         | P         | C          | all |

#### `exp_levels` list

| Intership | Entry Level | Associate | Mid-Senior Level | Director | All |
| --------- | ----------- | --------- | ---------------- | -------- | --- |
| 1         | 2           | 3         | 4                | 5        | all |

#### `routeParams` additional query parameters

##### `f_WT` list

| Onsite | Remote | Hybrid |
| ------ | ------ | ------ |
| 1      | 2      | 3      |

##### `geoId`

Geographic location ID. You can find this ID in the URL of a LinkedIn job search page that is filtered by location.

For example:
91000012 is the ID of East Asia.

##### `f_TPR`

Time posted range. Here are some possible values:

- `r86400`: Past 24 hours
- `r604800`: Past week
- `r2592000`: Past month

For example:

1. If we want to search software engineer jobs of all levels and all job types, use `/linkedin/jobs/all/all/software engineer`
2. If we want to search all entry level contractor/part time software engineer jobs, use `/linkedin/jobs/P-C/2/software engineer`
3. If we want to search remote mid-senior level software engineer jobs in APAC posted within the last month, use `/linkedin/jobs/F/4/software%20engineer/f_WT=2&geoId=91000003&f_TPR=r2592000`

**To make it easier, the recommended way is to start a search on [LinkedIn](https://www.linkedin.com/jobs/search) and use [RSSHub Radar](https://github.com/DIYgod/RSSHub-Radar) to load the specific feed.**

## Parameters
- `job_types`: See the following table for details, use '-' as delimiter
- `exp_levels`: See the following table for details, use '-' as delimiter
- `keywords`: keywords
- `routeParams`: additional query parameters, see the table below


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
  - `www.linkedin.com/jobs/search`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "#### `job_types` list\n\n| Full Time | Part Time | Contractor | All |\n| --------- | --------- | ---------- | --- |\n| F         | P         | C          | all |\n\n#### `exp_levels` list\n\n| Intership | Entry Level | Associate | Mid-Senior Level | Director | All |\n| --------- | ----------- | --------- | ---------------- | -------- | --- |\n| 1         | 2           | 3         | 4                | 5        | all |\n\n#### `routeParams` additional query parameters\n\n##### `f_WT` list\n\n| Onsite | Remote | Hybrid |\n| ------ | ------ | ------ |\n| 1      | 2      | 3      |\n\n##### `geoId`\n\nGeographic location ID. You can find this ID in the URL of a LinkedIn job search page that is filtered by location.\n\nFor example:\n91000012 is the ID of East Asia.\n\n##### `f_TPR`\n\nTime posted range. Here are some possible values:\n\n- `r86400`: Past 24 hours\n- `r604800`: Past week\n- `r2592000`: Past month\n\nFor example:\n\n1. If we want to search software engineer jobs of all levels and all job types, use `/linkedin/jobs/all/all/software engineer`\n2. If we want to search all entry level contractor/part time software engineer jobs, use `/linkedin/jobs/P-C/2/software engineer`\n3. If we want to search remote mid-senior level software engineer jobs in APAC posted within the last month, use `/linkedin/jobs/F/4/software%20engineer/f_WT=2&geoId=91000003&f_TPR=r2592000`\n\n**To make it easier, the recommended way is to start a search on [LinkedIn](https://www.linkedin.com/jobs/search) and use [RSSHub Radar](https://github.com/DIYgod/RSSHub-Radar) to load the specific feed.**",
  "example": "/linkedin/jobs/C-P/1/software engineer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 256,
  "location": "jobs.ts",
  "maintainers": [
    "BrandNewLifeJackie26",
    "zhoukuncheng"
  ],
  "name": "Jobs",
  "parameters": {
    "exp_levels": "See the following table for details, use '-' as delimiter",
    "job_types": "See the following table for details, use '-' as delimiter",
    "keywords": "keywords",
    "routeParams": "additional query parameters, see the table below"
  },
  "path": "/jobs/:job_types/:exp_levels/:keywords?/:routeParams?",
  "radar": [
    {
      "source": [
        "www.linkedin.com/jobs/search"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "This feed gets LinkedIn job posts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72488728159150080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linkedin.com/jobs-guest/jobs/api/seeMoreJobPostings/search?keywords=&f_JT=&f_E=",
      "title": "LinkedIn Job Listing",
      "type": "feed",
      "url": "rsshub://linkedin/jobs/all/all"
    },
    {
      "description": "This feed gets LinkedIn job posts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74290869863543808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linkedin.com/jobs-guest/jobs/api/seeMoreJobPostings/search?keywords=software+engineer&f_JT=&f_E=",
      "title": "LinkedIn Job Listing | Keywords: software engineer",
      "type": "feed",
      "url": "rsshub://linkedin/jobs/all/all/software%20engineer"
    }
  ],
  "view": 5
}
```
