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
  "heat": 26,
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
    },
    {
      "description": "<p>人工智能（Artificial Intelligence），英文缩写为AI。它是研究、开发用于模拟、延伸和扩展人的智能的理论、方法、技术及应用系统的一门新的技术科学。人工智能是计算机科学的一个分支，它企图了解智能的实质，并生产出一种新的能以人类智能相似的方式做出反应的智能机器，该领域的研究包括机器人、语言识别、图像识别、自然语言处理和专家系统等。人工智能从诞生以来，理论和技术日益成熟，应用领域也不断扩大，可以设想，未来人工智能带来的科技产品，将会是人类智慧的&ldquo;容器&rdquo;。人工智能可以对人的意识、思维的信息过程的模拟。人工智能不是人的智能，但能像人那样思考、也可能超过人的智能。人工智能是一门极富挑战性的科学，从事这项工作的人必须懂得计算机知识，心理学和哲学。人工智能是包括十分广泛的科学，它由不同的领域组成，如机器学习，计算机视觉等等，总的说来，人工智能研究的一个主要目标是使机器能够胜任一些通常需要人类智能才能完成的复杂工作。但不同的时代、不同的人对这种&ldquo;复杂工作&rdquo;的理解是不同的。2017年12月，人工智能入选&ldquo;2017年度中国媒体十大流行语&rdquo;。</p> - Powered by RSSHub",
      "errorAt": "2025-10-29T06:16:17.901Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/topics/19551275/intro?include=content.meta.content.photos\": 403 Forbidden\n",
      "id": "151850021267056752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/topic/19551275/newest",
      "title": "知乎话题-19551275-讨论",
      "type": "feed",
      "url": "rsshub://zhihu/topic/19551275"
    }
  ]
}
```
