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
      "description": "有些事你總會為怕惹麻煩，選擇最不傷腦、最省時的方式，過一些時間可以就不去想、然後邪惡地選擇性忘記最初的意念。 deca joins，需要有中文名字的存在（嗎）。 其實它並無特別的釋義方式，若一字一句拆解：decadent 為頹廢之意，decaffeination 是無咖啡因； joins 是接合點複數，整個字彙合在一起即為「 頹廢接合點 」、「 無咖啡因接合點 」。 從一個最混沌的狀態裡發芽，有過暴裂有過激熱，很快的就開始等待最後一秒的墜地了。他需要溫柔而抽離的酒精，唱漫天舞地的歌；乾枯的浴室他留不住，用僅剩的個人傾向跳入藍色的海，裸身浮沉到海口，靜而凝視的姿態、擰氣閉眼。 ＿＿＿無法排遣、無法打發，無法灑脫地丟棄，只能坦坦面對，豁豁地與之相處。去去回回，堵了那扇門有另一散扇窗，用緩慢拖沈的喃喃說一種潮濕的快樂，悶著黏著困著，不留餘地得把痛苦也合而為一。 夢裡路恍惚悠長。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60264889995165696",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/artist/969774",
      "title": "秀动网 - Deca joins",
      "type": "feed",
      "url": "rsshub://showstart/artist/969774"
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
