# 雷峰网 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `leiphone`
- Namespace Name: `雷峰网`
- Route Path: `/leiphone/category/:catname`
- Route Name: `栏目`
- Example: `/leiphone/category/industrynews`
- URL: `leiphone.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `vlcheng`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
- 主栏目

| 业界         | 人工智能 | 智能驾驶       | 数智化          | 金融科技 | 医疗科技 | 芯片  | 政企安全   | 智慧城市  | 行业云        | 工业互联网         | AIoT |
| ------------ | -------- | -------------- | --------------- | -------- | -------- | ----- | ---------- | --------- | ------------- | ------------------ | ---- |
| industrynews | ai       | transportation | digitalindustry | fintech  | aihealth | chips | gbsecurity | smartcity | industrycloud | IndustrialInternet | iot  |

- 子栏目

- 人工智能

| 学术     | 开发者   |
| -------- | -------- |
| academic | yanxishe |

- 数智化

| 零售数智化 | 金融数智化 | 工业数智化 | 医疗数智化 | 城市数智化  |
| ---------- | ---------- | ---------- | ---------- | ----------- |
| redigital  | findigital | mandigital | medigital  | citydigital |

- 金融科技

| 科技巨头 | 银行 AI | 金融云       | 风控与安全   |
| -------- | ------- | ------------ | ------------ |
| BigTech  | bank    | FinanceCloud | DataSecurity |

- 医疗科技

| 医疗 AI  | 投融资 | 医疗器械 | 互联网医疗       | 生物医药     | 健康险       |
| -------- | ------ | -------- | ---------------- | ------------ | ------------ |
| healthai | touzi  | qixie    | hulianwangyiliao | shengwuyiyao | jiankangxian |

- 芯片

| 材料设备  | 芯片设计   | 晶圆代工      | 封装测试  |
| --------- | ---------- | ------------- | --------- |
| materials | chipdesign | manufacturing | packaging |

- 智慧城市

| 智慧安防      | 智慧教育       | 智慧交通            | 智慧社区       | 智慧零售       | 智慧政务        | 智慧地产 |
| ------------- | -------------- | ------------------- | -------------- | -------------- | --------------- | -------- |
| smartsecurity | smarteducation | smarttransportation | smartcommunity | smartretailing | smartgovernment | proptech |

- 工业互联网

| 工业软件   | 工业安全 | 5G 工业互联网 | 工业转型实践 |
| ---------- | -------- | ------------- | ------------ |
| gysoftware | gysafety | 5ggy          | gypratice    |

- AIoT

| 物联网 | 智能硬件 | 机器人 | 智能家居  |
| ------ | -------- | ------ | --------- |
| 5G     | arvr     | robot  | smarthome |

## Parameters
- `catname`: 网站顶部分类栏目


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `leiphone.com/category/:catname`
- `target`: `/category/:catname`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "- 主栏目\n\n| 业界         | 人工智能 | 智能驾驶       | 数智化          | 金融科技 | 医疗科技 | 芯片  | 政企安全   | 智慧城市  | 行业云        | 工业互联网         | AIoT |\n| ------------ | -------- | -------------- | --------------- | -------- | -------- | ----- | ---------- | --------- | ------------- | ------------------ | ---- |\n| industrynews | ai       | transportation | digitalindustry | fintech  | aihealth | chips | gbsecurity | smartcity | industrycloud | IndustrialInternet | iot  |\n\n- 子栏目\n\n- 人工智能\n\n| 学术     | 开发者   |\n| -------- | -------- |\n| academic | yanxishe |\n\n- 数智化\n\n| 零售数智化 | 金融数智化 | 工业数智化 | 医疗数智化 | 城市数智化  |\n| ---------- | ---------- | ---------- | ---------- | ----------- |\n| redigital  | findigital | mandigital | medigital  | citydigital |\n\n- 金融科技\n\n| 科技巨头 | 银行 AI | 金融云       | 风控与安全   |\n| -------- | ------- | ------------ | ------------ |\n| BigTech  | bank    | FinanceCloud | DataSecurity |\n\n- 医疗科技\n\n| 医疗 AI  | 投融资 | 医疗器械 | 互联网医疗       | 生物医药     | 健康险       |\n| -------- | ------ | -------- | ---------------- | ------------ | ------------ |\n| healthai | touzi  | qixie    | hulianwangyiliao | shengwuyiyao | jiankangxian |\n\n- 芯片\n\n| 材料设备  | 芯片设计   | 晶圆代工      | 封装测试  |\n| --------- | ---------- | ------------- | --------- |\n| materials | chipdesign | manufacturing | packaging |\n\n- 智慧城市\n\n| 智慧安防      | 智慧教育       | 智慧交通            | 智慧社区       | 智慧零售       | 智慧政务        | 智慧地产 |\n| ------------- | -------------- | ------------------- | -------------- | -------------- | --------------- | -------- |\n| smartsecurity | smarteducation | smarttransportation | smartcommunity | smartretailing | smartgovernment | proptech |\n\n- 工业互联网\n\n| 工业软件   | 工业安全 | 5G 工业互联网 | 工业转型实践 |\n| ---------- | -------- | ------------- | ------------ |\n| gysoftware | gysafety | 5ggy          | gypratice    |\n\n- AIoT\n\n| 物联网 | 智能硬件 | 机器人 | 智能家居  |\n| ------ | -------- | ------ | --------- |\n| 5G     | arvr     | robot  | smarthome |",
  "example": "/leiphone/category/industrynews",
  "heat": 7,
  "location": "category.ts",
  "maintainers": [
    "vlcheng"
  ],
  "name": "栏目",
  "parameters": {
    "catname": "网站顶部分类栏目"
  },
  "path": "/category/:catname",
  "radar": [
    {
      "source": [
        "leiphone.com/category/:catname"
      ],
      "target": "/category/:catname"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "雷峰网 - 读懂智能&未来 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142763127907131396",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.leiphone.com/category/ai",
      "title": "雷峰网 ai",
      "type": "feed",
      "url": "rsshub://leiphone/category/ai"
    },
    {
      "description": "雷峰网 - 读懂智能&未来 - Powered by RSSHub",
      "errorAt": "2026-09-02T06:19:22.079Z",
      "errorMessage": "Failed to fetch\n",
      "id": "149642094386478114",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.leiphone.com/category/industrynews",
      "title": "雷峰网 industrynews",
      "type": "feed",
      "url": "rsshub://leiphone/category/industrynews"
    }
  ],
  "url": "leiphone.com/"
}
```
