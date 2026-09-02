# TVer - Series

## Coverage
`index-only`

## Route
- Namespace: `tver`
- Namespace Name: `TVer`
- Route Path: `/tver/series/:id`
- Route Name: `Series`
- Example: `/tver/series/srx2o7o3c8`
- URL: `tver.jp`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `yuikisaito`
- Source Location: `series.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Series ID (as it appears in URLs). For example, in https://tver.jp/series/srx2o7o3c8, the ID is "srx2o7o3c8".


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `tver.jp/series/:id`
- `target`: `/series/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/tver/series/srx2o7o3c8",
  "heat": 5,
  "location": "series.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "name": "Series",
  "parameters": {
    "id": "Series ID (as it appears in URLs). For example, in https://tver.jp/series/srx2o7o3c8, the ID is \"srx2o7o3c8\"."
  },
  "path": "/series/:id",
  "radar": [
    {
      "source": [
        "tver.jp/series/:id"
      ],
      "target": "/series/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "2025年4月13日、大阪・関西万博に響き渡った1万人の歌声。ベートーヴェン交響曲第九番「歓喜の歌」の大合唱は、参加者だけでなく、世界中の人々の心を揺さぶりました。 万博という特別な空間で迎えるクライマックス。彼らの歌声は、喜び、希望、そして未来へのメッセージを力強く世界に届けます。 - Powered by RSSHub",
      "errorAt": "2026-06-24T15:40:24.645Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "157466645136707584",
      "image": "https://statics.tver.jp/images/content/thumbnail/series/xlarge/sr5nj30c4q.jpg",
      "ownerUserId": null,
      "siteUrl": "https://tver.jp/series/sr5nj30c4q",
      "title": "TVer - １万人の第九 EXPO2025",
      "type": "feed",
      "url": "rsshub://tver/series/sr5nj30c4q"
    },
    {
      "description": "WBS（ワールドビジネスサテライト）は1988年4月にスタートした、日本で最も長く続く経済ニュース番組です。バブル崩壊やその後の金融危機、リーマンショック、東日本大震災、そして新型コロナショックと、激動の時代を「経済」という独自の切り口で報じ続けてきました。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "157453847056912384",
      "image": "https://statics.tver.jp/images/content/thumbnail/series/xlarge/srx2o7o3c8.jpg",
      "ownerUserId": null,
      "siteUrl": "https://tver.jp/series/srx2o7o3c8",
      "title": "TVer - ＷＢＳ（ワールドビジネスサテライト）",
      "type": "feed",
      "url": "rsshub://tver/series/srx2o7o3c8"
    }
  ]
}
```
