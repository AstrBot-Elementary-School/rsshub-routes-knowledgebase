# Link Research - Articles

## Coverage
`index-only`

## Route
- Namespace: `linkresearcher`
- Namespace Name: `Link Research`
- Route Path: `/linkresearcher/:params`
- Route Name: `Articles`
- Example: `/linkresearcher/category=theses&columns=Nature%20导读&subject=生物`
- URL: `www.linkresearcher.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, KarasuShin`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `params`: {"description": "search parameters, support `category`, `subject`, `columns`, `query`"}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/linkresearcher/category=theses&columns=Nature%20导读&subject=生物",
  "heat": 150,
  "location": "index.tsx",
  "maintainers": [
    "y9c",
    "KarasuShin"
  ],
  "name": "Articles",
  "parameters": {
    "params": {
      "description": "search parameters, support `category`, `subject`, `columns`, `query`"
    }
  },
  "path": "/:params",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "领研是链接华人学者的人才及成果平台。领研为国内外高校、科研机构及科技企业提供科研人才招聘服务，也是青年研究者的职业发展指导及线上培训平台；研究者还可将自己的研究论文上传至领研，与超过五十万华人学者分享工作的最新进展。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "94633935514907648",
      "image": "https://www.linkresearcher.com/assets/images/logo-app.png",
      "ownerUserId": null,
      "siteUrl": "https://www.linkresearcher.com/",
      "title": "领研 | 论文「计算机」",
      "type": "feed",
      "url": "rsshub://linkresearcher/category=theses&subject=%E8%AE%A1%E7%AE%97%E6%9C%BA"
    },
    {
      "description": "领研是链接华人学者的人才及成果平台。领研为国内外高校、科研机构及科技企业提供科研人才招聘服务，也是青年研究者的职业发展指导及线上培训平台；研究者还可将自己的研究论文上传至领研，与超过五十万华人学者分享工作的最新进展。 - Powered by RSSHub",
      "errorAt": "2026-07-26T13:44:07.328Z",
      "errorMessage": "[POST] \"https://www.linkresearcher.com/api/theses/search?from=0&size=20&type=SEARCH\": <no response> fetch failed (certificate has expired)\n[POST] \"https://www.linkresearcher.com/api/theses/search?from=0&size=20&type=SEARCH\": <no response> fetch failed (certificate has expired)\n",
      "id": "89936086961615886",
      "image": "https://www.linkresearcher.com/assets/images/logo-app.png",
      "ownerUserId": null,
      "siteUrl": "https://www.linkresearcher.com/",
      "title": "领研 | 论文「医学」",
      "type": "feed",
      "url": "rsshub://linkresearcher/category=theses&subject=%E5%8C%BB%E5%AD%A6"
    }
  ],
  "view": 0,
  "zh": {
    "name": "文章"
  }
}
```
