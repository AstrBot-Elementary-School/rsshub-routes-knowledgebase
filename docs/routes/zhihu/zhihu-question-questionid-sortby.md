# 知乎 - 问题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/question/:questionId/:sortBy?`
- Route Name: `问题`
- Example: `/zhihu/question/59895982`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer, hacklu`
- Source Location: `question.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `questionId`: 问题 id
- `sortBy`: 排序方式：`default`, `created`, `updated`。默认为 `default`


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/question/:questionId`
- `target`: `/question/:questionId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/question/59895982",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 201,
  "location": "question.ts",
  "maintainers": [
    "xyqfer",
    "hacklu"
  ],
  "name": "问题",
  "parameters": {
    "questionId": "问题 id",
    "sortBy": "排序方式：`default`, `created`, `updated`。默认为 `default`"
  },
  "path": "/question/:questionId/:sortBy?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/question/:questionId"
      ],
      "target": "/question/:questionId"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "知乎-你读过最冷门，但「含金量极高」的书是什么？ - Powered by RSSHub",
      "errorAt": "2026-02-04T21:58:31.300Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/questions/438708854/answers?include=data%5B*%5D.is_normal%2Cadmin_closed_comment%2Creward_info%2Cis_collapsed%2Cannotation_action%2Cannotation_detail%2Ccollapse_reason%2Cis_sticky%2Ccollapsed_by%2Csuggest_edit%2Ccomment_count%2Ccan_comment%2Ccontent%2Ceditable_content%2Cattachment%2Cvoteup_count%2Creshipment_settings%2Ccomment_permission%2Ccreated_time%2Cupdated_time%2Creview_info%2Crelevant_info%2Cquestion%2Cexcerpt%2Cis_labeled%2Cpaid_info%2Cpaid_info_content%2Crelationship.is_authorized%2Cis_author%2Cvoting%2Cis_thanked%2Cis_nothelp%2Cis_recognized%3Bdata%5B*%5D.mark_infos%5B*%5D.url%3Bdata%5B*%5D.author.follower_count%2Cbadge%5B*%5D.topics%3Bdata%5B*%5D.settings.table_of_content.enabled%26offset%3D0&limit=20&sort_by=default&platform=desktop\": 403 Forbidden\n",
      "id": "59054113995476992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/question/438708854",
      "title": "知乎-你读过最冷门，但「含金量极高」的书是什么？",
      "type": "feed",
      "url": "rsshub://zhihu/question/438708854"
    },
    {
      "description": "知乎-王阳明的心学精髓是什么? - Powered by RSSHub",
      "errorAt": "2026-02-10T20:36:06.009Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/questions/28052564/answers?include=data%5B*%5D.is_normal%2Cadmin_closed_comment%2Creward_info%2Cis_collapsed%2Cannotation_action%2Cannotation_detail%2Ccollapse_reason%2Cis_sticky%2Ccollapsed_by%2Csuggest_edit%2Ccomment_count%2Ccan_comment%2Ccontent%2Ceditable_content%2Cattachment%2Cvoteup_count%2Creshipment_settings%2Ccomment_permission%2Ccreated_time%2Cupdated_time%2Creview_info%2Crelevant_info%2Cquestion%2Cexcerpt%2Cis_labeled%2Cpaid_info%2Cpaid_info_content%2Crelationship.is_authorized%2Cis_author%2Cvoting%2Cis_thanked%2Cis_nothelp%2Cis_recognized%3Bdata%5B*%5D.mark_infos%5B*%5D.url%3Bdata%5B*%5D.author.follower_count%2Cbadge%5B*%5D.topics%3Bdata%5B*%5D.settings.table_of_content.enabled%26offset%3D0&limit=20&sort_by=default&platform=desktop\": 403 Forbidden\n[GET] \"https://www.zhihu.com/api/v4/questions/28052564/answers?include=data%5B*%5D.is_normal%2Cadmin_closed_comment%2Creward_info%2Cis_collapsed%2Cannotation_action%2Cannotation_detail%2Ccollapse_reason%2Cis_sticky%2Ccollapsed_by%2Csuggest_edit%2Ccomment_count%2Ccan_comment%2Ccontent%2Ceditable_content%2Cattachment%2Cvoteup_count%2Creshipment_settings%2Ccomment_permission%2Ccreated_time%2Cupdated_time%2Creview_info%2Crelevant_info%2Cquestion%2Cexcerpt%2Cis_labeled%2Cpaid_info%2Cpaid_info_content%2Crelationship.is_authorized%2Cis_author%2Cvoting%2Cis_thanked%2Cis_nothelp%2Cis_recognized%3Bdata%5B*%5D.mark_infos%5B*%5D.url%3Bdata%5B*%5D.author.follower_count%2Cbadge%5B*%5D.topics%3Bdata%5B*%5D.settings.table_of_content.enabled%26offset%3D0&limit=20&sort_by=default&platform=desktop\": 403 Forbidden\n",
      "id": "85730470475032576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/question/28052564",
      "title": "知乎-王阳明的心学精髓是什么?",
      "type": "feed",
      "url": "rsshub://zhihu/question/28052564"
    }
  ]
}
```
