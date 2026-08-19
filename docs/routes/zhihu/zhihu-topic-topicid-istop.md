# 知乎 - 话题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/topic/:topicId/:isTop?`
- Route Name: `话题`
- Example: `/zhihu/topic/19828946`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topicId`: 话题 id
- `isTop`: 仅精华，默认为否，其他值为是


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/topic/:topicId/:type`
- `target`: `/topic/:topicId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/topic/19828946",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "topic.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "话题",
  "parameters": {
    "isTop": "仅精华，默认为否，其他值为是",
    "topicId": "话题 id"
  },
  "path": "/topic/:topicId/:isTop?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/topic/:topicId/:type"
      ],
      "target": "/topic/:topicId"
    }
  ],
  "topFeeds": [
    {
      "description": "知乎话题-19783871-讨论 - Powered by RSSHub",
      "errorAt": "2025-10-29T08:17:58.014Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/topics/19783871/intro?include=content.meta.content.photos\": 403 Forbidden\n",
      "id": "105261369151721472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/topic/19783871/newest",
      "title": "知乎话题-19783871-讨论",
      "type": "feed",
      "url": "rsshub://zhihu/topic/19783871"
    },
    {
      "description": "渐进阅读是一种学习技巧，它使人们能够同时阅读成千上万篇文章而不会遗忘。渐进阅读从电子渠道（如互联网）导入文章开始。然后，学生摘录个别文章中最重要的片段供进一步复习。摘录的片段在复习后转换成问题和答案。然后经过系统性的间隔复习后转换为长期记忆。间隔复习过程就是被称为SuperMemo方法的间隔复习算法。 - Powered by RSSHub",
      "errorAt": "2025-10-29T10:08:20.394Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/topics/21754100/intro?include=content.meta.content.photos\": 403 Forbidden\n",
      "id": "105268398559082496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/topic/21754100/newest",
      "title": "知乎话题-21754100-讨论",
      "type": "feed",
      "url": "rsshub://zhihu/topic/21754100"
    }
  ]
}
```
