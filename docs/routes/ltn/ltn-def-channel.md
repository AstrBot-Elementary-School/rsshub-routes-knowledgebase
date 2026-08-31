# 自由時報 - 自由軍武頻道

## Coverage
`index-only`

## Route
- Namespace: `ltn`
- Namespace Name: `自由時報`
- Route Path: `/ltn/def/:channel{.+}?`
- Route Name: `自由軍武頻道`
- Example: `/ltn/def/breakingnewslist`
- URL: `def.ltn.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `def.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: {"default": "breakingnewslist", "description": "Channel, see the table below", "options": [{"label": "軍情動態", "value": "breakingnewslist"}, {"label": "國際軍情", "value": "list/10"}, {"label": "台海軍情", "value": "list/11"}, {"label": "軍情看板", "value": "list/22"}, {"label": "國防MIT", "value": "mitlist"}, {"label": "國機國造", "value": "list/12"}, {"label": "國艦國造", "value": "list/13"}, {"label": "潛艦國造", "value": "list/14"}, {"label": "飛彈", "value": "list/23"}, {"label": "戰甲車國造", "value": "list/24"}, {"label": "國防產業", "value": "list/15"}, {"label": "其他裝備", "value": "list/25"}, {"label": "軍武百科", "value": "pedialist"}, {"label": "圖解軍武", "value": "list/16"}, {"label": "陸用裝備", "value": "list/17"}, {"label": "海軍系統", "value": "list/18"}, {"label": "空軍系統", "value": "list/19"}, {"label": "國防祕辛", "value": "historylist"}, {"label": "軍風尚", "value": "stylelist"}, {"label": "將軍官邸故事", "value": "list/27"}, {"label": "軍事風餐廳", "value": "list/28"}, {"label": "軍風文創", "value": "list/29"}, {"label": "軍風世界", "value": "list/30"}, {"label": "軍武書摘", "value": "filelist"}, {"label": "自由講武堂", "value": "forumlist"}, {"label": "投書", "value": "list/20"}, {"label": "論壇", "value": "list/21"}, {"label": "軍情人物", "value": "peoplelist"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `def.ltn.com.tw/:channel`
- `target`: `/def/:channel`
### Rule 2
- `source`:
  - `def.ltn.com.tw/list/:id`
- `target`: `/def/list/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/ltn/def/breakingnewslist",
  "heat": 2,
  "location": "def.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "自由軍武頻道",
  "parameters": {
    "channel": {
      "default": "breakingnewslist",
      "description": "Channel, see the table below",
      "options": [
        {
          "label": "軍情動態",
          "value": "breakingnewslist"
        },
        {
          "label": "國際軍情",
          "value": "list/10"
        },
        {
          "label": "台海軍情",
          "value": "list/11"
        },
        {
          "label": "軍情看板",
          "value": "list/22"
        },
        {
          "label": "國防MIT",
          "value": "mitlist"
        },
        {
          "label": "國機國造",
          "value": "list/12"
        },
        {
          "label": "國艦國造",
          "value": "list/13"
        },
        {
          "label": "潛艦國造",
          "value": "list/14"
        },
        {
          "label": "飛彈",
          "value": "list/23"
        },
        {
          "label": "戰甲車國造",
          "value": "list/24"
        },
        {
          "label": "國防產業",
          "value": "list/15"
        },
        {
          "label": "其他裝備",
          "value": "list/25"
        },
        {
          "label": "軍武百科",
          "value": "pedialist"
        },
        {
          "label": "圖解軍武",
          "value": "list/16"
        },
        {
          "label": "陸用裝備",
          "value": "list/17"
        },
        {
          "label": "海軍系統",
          "value": "list/18"
        },
        {
          "label": "空軍系統",
          "value": "list/19"
        },
        {
          "label": "國防祕辛",
          "value": "historylist"
        },
        {
          "label": "軍風尚",
          "value": "stylelist"
        },
        {
          "label": "將軍官邸故事",
          "value": "list/27"
        },
        {
          "label": "軍事風餐廳",
          "value": "list/28"
        },
        {
          "label": "軍風文創",
          "value": "list/29"
        },
        {
          "label": "軍風世界",
          "value": "list/30"
        },
        {
          "label": "軍武書摘",
          "value": "filelist"
        },
        {
          "label": "自由講武堂",
          "value": "forumlist"
        },
        {
          "label": "投書",
          "value": "list/20"
        },
        {
          "label": "論壇",
          "value": "list/21"
        },
        {
          "label": "軍情人物",
          "value": "peoplelist"
        }
      ]
    }
  },
  "path": "/def/:channel{.+}?",
  "radar": [
    {
      "source": [
        "def.ltn.com.tw/:channel"
      ],
      "target": "/def/:channel"
    },
    {
      "source": [
        "def.ltn.com.tw/list/:id"
      ],
      "target": "/def/list/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "def.ltn.com.tw"
}
```
