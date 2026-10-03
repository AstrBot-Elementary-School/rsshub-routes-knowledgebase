# 秀动网 - 按音乐人 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/showstart/artist/:id`
- Route Name: `按音乐人 - 演出更新`
- Example: `/showstart/artist/301783`
- URL: `www.showstart.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `artist.ts`
- Source Module: `_None_`

## Description
::: tip
音乐人 ID 查询: `/showstart/search/artist/:keyword`，如: [https://rsshub.app/showstart/search/artist/ 周杰伦](https://rsshub.app/showstart/search/artist/周杰伦)
:::

## Parameters
- `id`: 音乐人 ID


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
  - `www.showstart.com/artist/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n音乐人 ID 查询: `/showstart/search/artist/:keyword`，如: [https://rsshub.app/showstart/search/artist/ 周杰伦](https://rsshub.app/showstart/search/artist/周杰伦)\n:::",
  "example": "/showstart/artist/301783",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "artist.ts",
  "maintainers": [
    "lchtao26"
  ],
  "name": "按音乐人 - 演出更新",
  "parameters": {
    "id": "音乐人 ID"
  },
  "path": "/artist/:id",
  "radar": [
    {
      "source": [
        "www.showstart.com/artist/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "成员： 老梁 / 佳明 / 赵鑫 / 亦真 流派：说唱 Rap 风格： Jazz ITSOGOO ITSOGOO是一个来自北京的爵士说唱团体 由Snarelop/ 佳明/ AlienKey/ 周士爵组成 长年活跃于音乐国 ITSOGOO接受了各种音乐带来的教养 并将多样的元素融合进入自己的创作 做出了中国少有的说唱风格 团队认为一切都很好 并相信美好的可能性 故取名ITSOGOO 即\"IT'S ALL GOOD\" 至今已发行两张专辑《It’s All Good》和《It’s No Good》 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59223475853337600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/artist/205470",
      "title": "秀动网 - ITSOGOO",
      "type": "feed",
      "url": "rsshub://showstart/artist/205470"
    },
    {
      "description": "内地独立流行乐团，由主唱乔西、词曲创作刘冠南组成。代表作《呼吸决定》、《忘了我》、《没有人不比我快乐》。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73918360042176532",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/artist/992554",
      "title": "秀动网 - Fine乐团",
      "type": "feed",
      "url": "rsshub://showstart/artist/992554"
    }
  ]
}
```
