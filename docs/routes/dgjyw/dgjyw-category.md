# 东莞教研网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `dgjyw`
- Namespace Name: `东莞教研网`
- Route Path: `/dgjyw/:category{.+}?`
- Route Name: `分类`
- Example: `/dgjyw/tz`
- URL: `dgjyw.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 通知 | 动态 | 公示 |
| ---- | ---- | ---- |
| tz   | dt   | gs   |

::: tip
分类字段处填写的是对应东莞教研网网址中介于 `https://www.dgjyw.com/` 和 `.htm` 中间的一段。

如 [通知](https://www.dgjyw.com/tz.htm) 的网址为 `https://www.dgjyw.com/tz.htm`，其中间字段为 `tz`，所以可得路由为 [`/dgjyw/tz`](https://rsshub.app/dgjyw/tz)；

同理，[教育科研 - 科研文件](https://www.dgjyw.com/jyky/kywj.htm) 的网址为 `https://www.dgjyw.com/jyky/kywj.htm`，其中间字段为 `jyky/kywj`，所以可得路由为 [`/dgjyw/jyky/kywj`](https://rsshub.app/dgjyw/jyky/kywj)。
:::

## Parameters
- `category`: 分类，见下表，默认为通知


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dgjyw.com/:category.htm`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| 通知 | 动态 | 公示 |\n| ---- | ---- | ---- |\n| tz   | dt   | gs   |\n\n::: tip\n分类字段处填写的是对应东莞教研网网址中介于 `https://www.dgjyw.com/` 和 `.htm` 中间的一段。\n\n如 [通知](https://www.dgjyw.com/tz.htm) 的网址为 `https://www.dgjyw.com/tz.htm`，其中间字段为 `tz`，所以可得路由为 [`/dgjyw/tz`](https://rsshub.app/dgjyw/tz)；\n\n同理，[教育科研 - 科研文件](https://www.dgjyw.com/jyky/kywj.htm) 的网址为 `https://www.dgjyw.com/jyky/kywj.htm`，其中间字段为 `jyky/kywj`，所以可得路由为 [`/dgjyw/jyky/kywj`](https://rsshub.app/dgjyw/jyky/kywj)。\n:::",
  "example": "/dgjyw/tz",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为通知"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.dgjyw.com/:category.htm"
      ],
      "target": "/:category"
    }
  ],
  "topFeeds": []
}
```
