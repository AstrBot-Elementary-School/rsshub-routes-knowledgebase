# 中华人民共和国学位证书查询 - 各学位授予单位学位证书上网进度

## Coverage
`index-only`

## Route
- Namespace: `chinadegrees`
- Namespace Name: `中华人民共和国学位证书查询`
- Route Path: `/chinadegrees/:province?`
- Route Name: `各学位授予单位学位证书上网进度`
- Example: `/chinadegrees/11`
- URL: `chinadegrees.com.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `TonyRL`
- Source Location: `province.tsx`
- Source Module: `_None_`

## Description
| 省市             | 代号 |
| ---------------- | ---- |
| 北京市           | 11   |
| 天津市           | 12   |
| 河北省           | 13   |
| 山西省           | 14   |
| 内蒙古自治区     | 15   |
| 辽宁省           | 21   |
| 吉林省           | 22   |
| 黑龙江省         | 23   |
| 上海市           | 31   |
| 江苏省           | 32   |
| 浙江省           | 33   |
| 安徽省           | 34   |
| 福建省           | 35   |
| 江西省           | 36   |
| 山东省           | 37   |
| 河南省           | 41   |
| 湖北省           | 42   |
| 湖南省           | 43   |
| 广东省           | 44   |
| 广西壮族自治区   | 45   |
| 海南省           | 46   |
| 重庆市           | 50   |
| 四川省           | 51   |
| 贵州省           | 52   |
| 云南省           | 53   |
| 西藏自治区       | 54   |
| 陕西省           | 61   |
| 甘肃省           | 62   |
| 青海省           | 63   |
| 宁夏回族自治区   | 64   |
| 新疆维吾尔自治区 | 65   |
| 台湾             | 71   |

## Parameters
- `province`: 省市代号，见下表，亦可在 [这里](http://www.chinadegrees.com.cn/help/provinceSwqk.html) 找到，默认为 `11`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "study"
  ],
  "description": "| 省市             | 代号 |\n| ---------------- | ---- |\n| 北京市           | 11   |\n| 天津市           | 12   |\n| 河北省           | 13   |\n| 山西省           | 14   |\n| 内蒙古自治区     | 15   |\n| 辽宁省           | 21   |\n| 吉林省           | 22   |\n| 黑龙江省         | 23   |\n| 上海市           | 31   |\n| 江苏省           | 32   |\n| 浙江省           | 33   |\n| 安徽省           | 34   |\n| 福建省           | 35   |\n| 江西省           | 36   |\n| 山东省           | 37   |\n| 河南省           | 41   |\n| 湖北省           | 42   |\n| 湖南省           | 43   |\n| 广东省           | 44   |\n| 广西壮族自治区   | 45   |\n| 海南省           | 46   |\n| 重庆市           | 50   |\n| 四川省           | 51   |\n| 贵州省           | 52   |\n| 云南省           | 53   |\n| 西藏自治区       | 54   |\n| 陕西省           | 61   |\n| 甘肃省           | 62   |\n| 青海省           | 63   |\n| 宁夏回族自治区   | 64   |\n| 新疆维吾尔自治区 | 65   |\n| 台湾             | 71   |",
  "example": "/chinadegrees/11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "province.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "各学位授予单位学位证书上网进度",
  "parameters": {
    "province": "省市代号，见下表，亦可在 [这里](http://www.chinadegrees.com.cn/help/provinceSwqk.html) 找到，默认为 `11`"
  },
  "path": "/:province?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
