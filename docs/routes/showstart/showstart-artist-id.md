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
      "description": "秀动网 - 周士爵 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59224265617690624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/artist/6810007",
      "title": "秀动网 - 周士爵",
      "type": "feed",
      "url": "rsshub://showstart/artist/6810007"
    },
    {
      "description": "邓紫棋（G.E.M.），原名邓诗颖，1991年8月16日生于中国上海，4岁移居香港，中国香港创作型女歌手 。 2009年1月，获得叱咤乐坛流行榜“叱咤乐坛生力军女歌手金奖” 。2011年5月，19岁的邓紫棋在香港红馆举行5场的个人演唱会。2012年，获得IPFI香港唱片销量大奖“全年*销量女歌手奖”；创作的专辑《Xposed》获得“*销量国语唱片奖”。2014年，参加中国内地湖南卫视歌唱类综艺节目《我是歌手第二季》 ，获得总决赛亚军 。3月，获第27届KCA美国儿童选择奖“*亚洲艺人” 。12月10日，邓紫棋在香港杜莎夫人蜡像馆为自己的蜡像揭幕 。2015年2月18日晚，邓紫棋参加2015年中央电视台春节联欢晚会，自弹自唱其自创的歌曲《多远都要在一起》 。截至北京时间2015年5月31日，《G.E.M.X.X.X.Live”世界巡回演唱会》已经完成60场。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142941022923232256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/artist/4434",
      "title": "秀动网 - 邓紫棋",
      "type": "feed",
      "url": "rsshub://showstart/artist/4434"
    }
  ]
}
```
