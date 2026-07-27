# 梅斯医学 MedSci - 资讯

## Coverage
`index-only`

## Route
- Namespace: `medsci`
- Namespace Name: `梅斯医学 MedSci`
- Route Path: `/medsci/:sid?/:tid?`
- Route Name: `资讯`
- Example: `/medsci`
- URL: `medsci.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
下表为科室对应的 sid，若想获得 tid，可以到对应科室页面 URL 中寻找 `t_id` 字段的值，下面是一个例子：

如 [肿瘤 - NSCLC](https://www.medsci.cn/department/details?s_id=5\&t_id=277) 的 URL 为 `https://www.medsci.cn/department/details?s_id=5&t_id=277`，可以看到此时 `s_id` 对应 `sid` 的值为 5， `t_id` 对应 `tid` 的值为 277，所以可以得到路由 [`/medsci/5/277`](https://rsshub.app/medsci/5/277)
:::

| 心血管 | 内分泌 | 消化 | 呼吸 | 神经科 |
| ------ | ------ | ---- | ---- | ------ |
| 2      | 6      | 4    | 12   | 17     |

| 传染科 | 精神心理 | 肾内科 | 风湿免疫 | 血液科 |
| ------ | -------- | ------ | -------- | ------ |
| 9      | 13       | 14     | 15       | 21     |

| 老年医学 | 胃肠外科 | 血管外科 | 肝胆胰外 | 骨科 |
| -------- | -------- | -------- | -------- | ---- |
| 19       | 76       | 92       | 91       | 10   |

| 普通外科 | 胸心外科 | 神经外科 | 泌尿外科 | 烧伤科 |
| -------- | -------- | -------- | -------- | ------ |
| 23       | 24       | 25       | 26       | 27     |

| 整形科 | 麻醉疼痛 | 罕见病 | 康复医学 | 药械 |
| ------ | -------- | ------ | -------- | ---- |
| 28     | 29       | 304    | 95       | 11   |

| 儿科 | 耳鼻咽喉 | 口腔科 | 眼科 | 政策人文 |
| ---- | -------- | ------ | ---- | -------- |
| 18   | 30       | 31     | 32   | 33       |

| 营养全科 | 预防公卫 | 妇产科 | 中医科 | 急重症 |
| -------- | -------- | ------ | ------ | ------ |
| 34       | 35       | 36     | 37     | 38     |

| 皮肤性病 | 影像放射 | 转化医学 | 检验病理 | 护理 |
| -------- | -------- | -------- | -------- | ---- |
| 39       | 40       | 42       | 69       | 79   |

| 糖尿病 | 冠心病 | 肝病 | 乳腺癌 |
| ------ | ------ | ---- | ------ |
| 8      | 43     | 22   | 89     |

## Parameters
- `sid`: 科室，见下表，默认为推荐
- `tid`: 亚专业，可在对应科室页 URL 中找到，默认为该科室的全部


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
    "new-media"
  ],
  "description": "::: tip\n下表为科室对应的 sid，若想获得 tid，可以到对应科室页面 URL 中寻找 `t_id` 字段的值，下面是一个例子：\n\n如 [肿瘤 - NSCLC](https://www.medsci.cn/department/details?s_id=5\\&t_id=277) 的 URL 为 `https://www.medsci.cn/department/details?s_id=5&t_id=277`，可以看到此时 `s_id` 对应 `sid` 的值为 5， `t_id` 对应 `tid` 的值为 277，所以可以得到路由 [`/medsci/5/277`](https://rsshub.app/medsci/5/277)\n:::\n\n| 心血管 | 内分泌 | 消化 | 呼吸 | 神经科 |\n| ------ | ------ | ---- | ---- | ------ |\n| 2      | 6      | 4    | 12   | 17     |\n\n| 传染科 | 精神心理 | 肾内科 | 风湿免疫 | 血液科 |\n| ------ | -------- | ------ | -------- | ------ |\n| 9      | 13       | 14     | 15       | 21     |\n\n| 老年医学 | 胃肠外科 | 血管外科 | 肝胆胰外 | 骨科 |\n| -------- | -------- | -------- | -------- | ---- |\n| 19       | 76       | 92       | 91       | 10   |\n\n| 普通外科 | 胸心外科 | 神经外科 | 泌尿外科 | 烧伤科 |\n| -------- | -------- | -------- | -------- | ------ |\n| 23       | 24       | 25       | 26       | 27     |\n\n| 整形科 | 麻醉疼痛 | 罕见病 | 康复医学 | 药械 |\n| ------ | -------- | ------ | -------- | ---- |\n| 28     | 29       | 304    | 95       | 11   |\n\n| 儿科 | 耳鼻咽喉 | 口腔科 | 眼科 | 政策人文 |\n| ---- | -------- | ------ | ---- | -------- |\n| 18   | 30       | 31     | 32   | 33       |\n\n| 营养全科 | 预防公卫 | 妇产科 | 中医科 | 急重症 |\n| -------- | -------- | ------ | ------ | ------ |\n| 34       | 35       | 36     | 37     | 38     |\n\n| 皮肤性病 | 影像放射 | 转化医学 | 检验病理 | 护理 |\n| -------- | -------- | -------- | -------- | ---- |\n| 39       | 40       | 42       | 69       | 79   |\n\n| 糖尿病 | 冠心病 | 肝病 | 乳腺癌 |\n| ------ | ------ | ---- | ------ |\n| 8      | 43     | 22   | 89     |",
  "example": "/medsci",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 329,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "sid": "科室，见下表，默认为推荐",
    "tid": "亚专业，可在对应科室页 URL 中找到，默认为该科室的全部"
  },
  "path": "/:sid?/:tid?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "推荐 - MedSci.cn - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70825962351576064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.medsci.cn/",
      "title": "推荐 - MedSci.cn",
      "type": "feed",
      "url": "rsshub://medsci"
    },
    {
      "description": "心血管 - MedSci.cn - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66942767614244865",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.medsci.cn/department/details?s_id=2&module=article",
      "title": "心血管 - MedSci.cn",
      "type": "feed",
      "url": "rsshub://medsci/2"
    }
  ]
}
```
