# 格隆汇 - 主题文章

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/gelonghui/subject/:id`
- Route Name: `主题文章`
- Example: `/gelonghui/subject/4`
- URL: `gelonghui.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `subject.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 主题编号，可在主题页 URL 中找到


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
  - `gelonghui.com/subject/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/gelonghui/subject/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 247,
  "location": "subject.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "主题文章",
  "parameters": {
    "id": "主题编号，可在主题页 URL 中找到"
  },
  "path": "/subject/:id",
  "radar": [
    {
      "source": [
        "gelonghui.com/subject/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "我们密切关注A股的市场动态，为你搜集最及时的A股资讯和分析解读。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59829598270902276",
      "image": "https://img7.gelonghui.com/apply/211719_20181221/column_article_file_20181221170139302.png",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/subject/4",
      "title": "格隆汇 - 主题 A股投资策略 的文章",
      "type": "feed",
      "url": "rsshub://gelonghui/subject/4"
    },
    {
      "description": "2024年政策产业共振，有望成为低空经济元年，后续载人客运市场应用场景打开有望为eVTOL市场提速。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68144523718124544",
      "image": "https://img2.gelonghui.com/04d2f-fe73f446-87c6-4203-a828-0959554dfcba.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/subject/888",
      "title": "格隆汇 - 主题 低空经济/飞行汽车(eVTOL) 的文章",
      "type": "feed",
      "url": "rsshub://gelonghui/subject/888"
    }
  ],
  "view": 0
}
```
