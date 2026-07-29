# 星洲网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `sinchew`
- Namespace Name: `星洲网`
- Route Path: `/sinchew/category/:category{.+}?`
- Route Name: `分类`
- Example: `/sinchew/category/头条`
- URL: `sinchew.com.my`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 头条 | 国内 | 国际 | 言路 | 财经 | 地方 | 副刊 | 娱乐 | 体育 | 百格 | 星角攝 | 好运来 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ------ |

::: tip
若订阅单级分类 [头条](https://www.sinchew.com.my/category/头条)，其 URL 为 [https://www.sinchew.com.my/category/ 头条](https://www.sinchew.com.my/category/头条)，则路由为 [`/sinchew/category/头条`](https://rsshub.app/sinchew/category/头条)。

若订阅多级分类 [国际 > 天下事](https://www.sinchew.com.my/category/国际/天下事)，其 URL 为 [https://www.sinchew.com.my/category/ 国际 / 天下事](https://www.sinchew.com.my/category/国际/天下事)，则路由为 [`/sinchew/category/国际/天下事`](https://rsshub.app/sinchew/category/国际/天下事)。
:::

## Parameters
- `category`: 分类，见下表，亦可以在对应分类页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `sinchew.com.my/category/:category`
  - `sinchew.com.my/`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 头条 | 国内 | 国际 | 言路 | 财经 | 地方 | 副刊 | 娱乐 | 体育 | 百格 | 星角攝 | 好运来 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ------ |\n\n::: tip\n若订阅单级分类 [头条](https://www.sinchew.com.my/category/头条)，其 URL 为 [https://www.sinchew.com.my/category/ 头条](https://www.sinchew.com.my/category/头条)，则路由为 [`/sinchew/category/头条`](https://rsshub.app/sinchew/category/头条)。\n\n若订阅多级分类 [国际 > 天下事](https://www.sinchew.com.my/category/国际/天下事)，其 URL 为 [https://www.sinchew.com.my/category/ 国际 / 天下事](https://www.sinchew.com.my/category/国际/天下事)，则路由为 [`/sinchew/category/国际/天下事`](https://rsshub.app/sinchew/category/国际/天下事)。\n:::",
  "example": "/sinchew/category/头条",
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，亦可以在对应分类页 URL 中找到"
  },
  "path": "/category/:category{.+}?",
  "radar": [
    {
      "source": [
        "sinchew.com.my/category/:category",
        "sinchew.com.my/"
      ],
      "target": "/category/:category"
    }
  ],
  "topFeeds": []
}
```
