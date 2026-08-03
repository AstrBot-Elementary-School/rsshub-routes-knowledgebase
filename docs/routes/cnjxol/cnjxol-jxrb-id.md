# 南湖清风 - 嘉兴日报

## Coverage
`index-only`

## Route
- Namespace: `cnjxol`
- Namespace Name: `南湖清风`
- Route Path: `/cnjxol/jxrb/:id?`
- Route Name: `嘉兴日报`
- Example: `/cnjxol/jxrb`
- URL: `cnjxol.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| 版                   | 编号 |
| -------------------- | ---- |
| 全部                 |      |
| 第 01 版：要闻       | 01   |
| 第 02 版：要闻       | 02   |
| 第 03 版：要闻       | 03   |
| 第 04 版：嘉一度     | 04   |
| 第 05 版：聚焦       | 05   |
| 第 06 版：党报热线   | 06   |
| 第 07 版：天下       | 07   |
| 第 08 版：聚焦       | 08   |
| 第 09 版：南湖新闻   | 09   |
| 第 10 版：综合       | 10   |
| 第 11 版：梅花洲     | 11   |
| 第 12 版：南湖纵横   | 12   |
| 第 13 版：秀洲新闻   | 13   |
| 第 14 版：综合       | 14   |
| 第 15 版：秀・观察   | 15   |
| 第 16 版：走进高新区 | 16   |

## Parameters
- `id`: 编号，见下表，默认为全部


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `cnjxol.com/`
- `target`: `/jxrb/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 版                   | 编号 |\n| -------------------- | ---- |\n| 全部                 |      |\n| 第 01 版：要闻       | 01   |\n| 第 02 版：要闻       | 02   |\n| 第 03 版：要闻       | 03   |\n| 第 04 版：嘉一度     | 04   |\n| 第 05 版：聚焦       | 05   |\n| 第 06 版：党报热线   | 06   |\n| 第 07 版：天下       | 07   |\n| 第 08 版：聚焦       | 08   |\n| 第 09 版：南湖新闻   | 09   |\n| 第 10 版：综合       | 10   |\n| 第 11 版：梅花洲     | 11   |\n| 第 12 版：南湖纵横   | 12   |\n| 第 13 版：秀洲新闻   | 13   |\n| 第 14 版：综合       | 14   |\n| 第 15 版：秀・观察   | 15   |\n| 第 16 版：走进高新区 | 16   |",
  "example": "/cnjxol/jxrb",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "嘉兴日报",
  "parameters": {
    "id": "编号，见下表，默认为全部"
  },
  "path": "/jxrb/:id?",
  "radar": [
    {
      "source": [
        "cnjxol.com/"
      ],
      "target": "/jxrb/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
