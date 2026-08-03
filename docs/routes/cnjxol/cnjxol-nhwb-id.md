# 南湖清风 - 南湖晚报

## Coverage
`index-only`

## Route
- Namespace: `cnjxol`
- Namespace Name: `南湖清风`
- Route Path: `/cnjxol/nhwb/:id?`
- Route Name: `南湖晚报`
- Example: `/cnjxol/nhwb`
- URL: `cnjxol.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `nhwb.ts`
- Source Module: `_None_`

## Description
| 版                                   | 编号 |
| ------------------------------------ | ---- |
| 全部                                 |      |
| 第 01 版：要闻                       | 01   |
| 第 02 版：品质嘉兴・红船旁的美丽城镇 | 02   |
| 第 03 版：嘉兴新闻                   | 03   |
| 第 04 版：嘉兴新闻                   | 04   |
| 第 05 版：今日聚焦                   | 05   |
| 第 06 版：嘉兴新闻                   | 06   |
| 第 07 版：热线新闻                   | 07   |
| 第 08 版：财经新闻                   | 08   |
| 第 09 版：热线新闻                   | 09   |
| 第 10 版：公益广告                   | 10   |
| 第 11 版：消费周刊                   | 11   |
| 第 12 版：悦读坊                     | 12   |

## Parameters
- `id`: 编号，见下表，默认为全部


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `cnjxol.com/`
- `target`: `/nhwb/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 版                                   | 编号 |\n| ------------------------------------ | ---- |\n| 全部                                 |      |\n| 第 01 版：要闻                       | 01   |\n| 第 02 版：品质嘉兴・红船旁的美丽城镇 | 02   |\n| 第 03 版：嘉兴新闻                   | 03   |\n| 第 04 版：嘉兴新闻                   | 04   |\n| 第 05 版：今日聚焦                   | 05   |\n| 第 06 版：嘉兴新闻                   | 06   |\n| 第 07 版：热线新闻                   | 07   |\n| 第 08 版：财经新闻                   | 08   |\n| 第 09 版：热线新闻                   | 09   |\n| 第 10 版：公益广告                   | 10   |\n| 第 11 版：消费周刊                   | 11   |\n| 第 12 版：悦读坊                     | 12   |",
  "example": "/cnjxol/nhwb",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "nhwb.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "南湖晚报",
  "parameters": {
    "id": "编号，见下表，默认为全部"
  },
  "path": "/nhwb/:id?",
  "radar": [
    {
      "source": [
        "cnjxol.com/"
      ],
      "target": "/nhwb/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
