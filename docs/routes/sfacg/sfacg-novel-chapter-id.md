# SF 轻小说 - 章节

## Coverage
`index-only`

## Route
- Namespace: `sfacg`
- Namespace Name: `SF 轻小说`
- Route Path: `/sfacg/novel/chapter/:id`
- Route Name: `章节`
- Example: `/sfacg/novel/chapter/672431`
- URL: `book.sfacg.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `keocheung`
- Source Location: `novel-chapter.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  - `book.sfacg.com/Novel/:id`
  - `book.sfacg.com/Novel/:id/*`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/sfacg/novel/chapter/672431",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "novel-chapter.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/novel/chapter/:id",
  "radar": [
    {
      "source": [
        "book.sfacg.com/Novel/:id",
        "book.sfacg.com/Novel/:id/*"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "如果有人告诉你，世界上的怪异从未消失，反而因为互联网的发达而愈发深入人心、扎根人世呢？ 他与大多数普通人一样，过着一眼望到头的生活，上学，工作，结婚，生子，枯燥，平淡，如果那一天那红发的少女没有向他伸出手，他也许将平庸地度过余生。 他们说她是疯子。然而他们不曾知晓…… ... - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154692661911148544",
      "image": "https://rs.sfacg.com/web/novel/images/NovelCover/Big/2025/07/33268ec7-6330-41a6-b8c4-4c5b3da27a2d.jpg",
      "ownerUserId": null,
      "siteUrl": "https://book.sfacg.com/Novel/747572",
      "title": "SF轻小说 都市怪谈症候群",
      "type": "feed",
      "url": "rsshub://sfacg/novel/chapter/747572"
    },
    {
      "description": "寻仙山脚下的莲子镇民都知道，寻仙山里根本没有神仙，这世上也从未有过神仙。对杜玉来说，倘若把骑着白鹿，身着白衣的女子叫做仙人的话，他估计不会反对。虽然他觉得没有哪个仙人还需要弟子给她洗贴身衣物，也没有哪个仙人一天天懒到躺在藤椅上一动不动。在他心中，师尊就是仙人。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59070877359809536",
      "image": "https://rs.sfacg.com/web/novel/images/NovelCover/Big/2025/01/aca22e84-e5e8-445c-9d1e-7a0d72f091fd.jpg",
      "ownerUserId": null,
      "siteUrl": "https://book.sfacg.com/Novel/672431",
      "title": "SF轻小说 从前有座寻仙山",
      "type": "feed",
      "url": "rsshub://sfacg/novel/chapter/672431"
    }
  ]
}
```
