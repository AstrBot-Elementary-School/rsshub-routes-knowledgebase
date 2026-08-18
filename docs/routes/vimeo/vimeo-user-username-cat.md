# Vimeo - User Profile

## Coverage
`index-only`

## Route
- Namespace: `vimeo`
- Namespace Name: `Vimeo`
- Route Path: `/vimeo/user/:username/:cat?`
- Route Name: `User Profile`
- Example: `/vimeo/user/filmsupply/picks`
- URL: `vimeo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `MisteryMonster`
- Source Location: `usr-videos.ts`
- Source Module: `_None_`

## Description
::: tip Special category name attention
Some of the categories contain slash like `3D/CG` , must change the slash `/` to the vertical bar`|`.
:::

## Parameters
- `username`: In this example [https://vimeo.com/filmsupply](https://vimeo.com/filmsupply)  is `filmsupply`
- `cat`: deafult for all latest videos, others categories in this example such as `Docmentary`, `Narrative`, `Drama`. Set `picks` for promote orders, just orderd like web page. When `picks` added, published date won't show up


## Features
- `requireConfig`: false
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
  "description": "::: tip Special category name attention\nSome of the categories contain slash like `3D/CG` , must change the slash `/` to the vertical bar`|`.\n:::",
  "example": "/vimeo/user/filmsupply/picks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 27,
  "location": "usr-videos.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "User Profile",
  "parameters": {
    "cat": "deafult for all latest videos, others categories in this example such as `Docmentary`, `Narrative`, `Drama`. Set `picks` for promote orders, just orderd like web page. When `picks` added, published date won't show up",
    "username": "In this example [https://vimeo.com/filmsupply](https://vimeo.com/filmsupply)  is `filmsupply`"
  },
  "path": "/user/:username/:cat?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "LOOCreative는 다양한 분야의 최고의 크리에이터들이 만나 새로운 기획, 제작 능력을 기반으로 영화, 광고, 소셜, 뮤직 비디오 및 TV 산업에서 독특한 시각과 기술로 창의적인 성과를 창출합니다. 변화하는 빠른 트렌드를 반영하여 IT 기술기반의 다양한 콘텐츠 비즈니스의 범위를 넓혀가며 미래기술 기반의 콘텐츠 영역까지 확장해 나가는 창의적 문화 콘텐츠 기업입니다. - Powered by RSSHub",
      "errorAt": "2026-03-26T22:16:22.589Z",
      "errorMessage": "[GET] \"https://api.vimeo.com/users/loocreative?fields=name,gender,bio,uri,link,categories&fetch_user_profile=1\": 406 Not Acceptable\n",
      "id": "79414875841087488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vimeo.com/loocreative",
      "title": "LOOC | Vimeo",
      "type": "feed",
      "url": "rsshub://vimeo/user/loocreative"
    },
    {
      "description": "[a_a] Amused art, are defined as arts with fun and delight.[a_a] is, powerful service infrastructure and best in class technical support, delivered by highly skilled professionals, and led by strategic thinking and innovative execution. [a_a] has service footprint across various industries. We uncover the core driving force of your brand using our visual language expertise. We establish branding image by developing comprehensive and creative solutions, backed by strategic support and cross-media marketing. In short, [a_a] is a brand marketing/integration company, or simply an advertisement company. But we envision ourselves as an amused art creativity studio. [a_a]'s work has been spreaded across Asia and UK on various media, and been widely passed on through marketing platforms, dancing club, experimental film festival, magazine, art gallery and newspaper. [a_a] has established sound branding image in the industry by its powerful and effective production ability and acute strategies, as well as the rich innovation and specialized customer service. We has in-depth working relationships with domestic production agencies, and we have extended reach in Hong Kong and Taiwan, making joint effort to promote and co-develop the markets. [a_a] Amused art, fun and delightful art. We are not merely a studio specialized in adverting productions, image integration and visual design, but also a group of people leading an artistic and delightful life style. - Powered by RSSHub",
      "errorAt": "2026-03-26T14:11:46.811Z",
      "errorMessage": "[GET] \"https://api.vimeo.com/users/amusedart?fields=name,gender,bio,uri,link,categories&fetch_user_profile=1\": 406 Not Acceptable\n",
      "id": "79416106914161664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vimeo.com/amusedart",
      "title": "[ a _ a ] Amused Art | Vimeo",
      "type": "feed",
      "url": "rsshub://vimeo/user/amusedart"
    }
  ],
  "view": 3
}
```
