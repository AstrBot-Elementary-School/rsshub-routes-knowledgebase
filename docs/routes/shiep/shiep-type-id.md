# 上海电力大学 - 新闻网与学院通知

## Coverage
`index-only`

## Route
- Namespace: `shiep`
- Namespace Name: `上海电力大学`
- Route Path: `/shiep/:type/:id?`
- Route Name: `新闻网与学院通知`
- Example: `/shiep/news/notice`
- URL: `bwc.shiep.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gumibea, TeamSUEP`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
类型名称与默认 ID：

学院一览：

| 能源与机械工程学院 | 环境与化学工程学院 | 电气工程学院 | 自动化工程学院 | 计算机科学与技术学院 | 电子与信息工程学院 | 经济与管理学院 | 数理学院 | 外国语学院 | 体育学院 | 马克思主义学院 | 人文艺术学院 | 继续教育学院（国际教育学院） | 海上风电研究院 |
| ------------------ | ------------------ | ------------ | -------------- | -------------------- | ------------------ | -------------- | -------- | ---------- | -------- | -------------- | ------------ | ---------------------------- | -------------- |
| energy             | hhxy               | dqxy         | zdhxy          | jsjxy                | dxxy               | jgxy           | slxy     | wgyxy      | tyb      | skb            | rwysxy       | jjxy                         | hsfdyjy        |
| 892                | 5559               | 2462         | 2002           | xygg                 | tzgg               | 3633           | 2063     | tzgg       | 2891     | 1736           | 3089         | 2582                         | 5748           |

党群部门：

| 党委办公室 | 组织部（老干部处、党校） | 党建服务中心 / 党建督查室 | 宣传部（文明办、融媒体中心） | 统战部 | 机关党委 | 纪委（监察专员办公室） | 巡查办    | 武装部 | 学生工作部 | 团委 | 工会（妇工委） | 教师工作部 | 离退休党委 | 研究生工作部 |
| ---------- | ------------------------ | ------------------------- | ---------------------------- | ------ | -------- | ---------------------- | --------- | ------ | ---------- | ---- | -------------- | ---------- | ---------- | ------------ |
| dangban    | zzb                      | djfwzxdcs                 | xcb                          | tzb    | jgdw     | jijian                 | xunchaban | bwc    | xsc        | tw   | gonghui        | rsc        | tgb        | yjsc         |
| 4013       | 1534                     | tzgg                      | 2925                         | 3858   | 3205     | 59                     | 5044      | tzgg   | 3482       | 2092 | 1806           | 1695       | notice     | 1161         |

行政部门：

| 校长办公室（档案馆） | 对外联络处 | 发展规划处 | 审计处 | 保卫处 | 学生处 | 人事处 | 退管办 | 国际交流与合作处（港澳台办公室） | 科研处 / 融合办 | 教务处 | 研究生院 | 后勤管理处（后勤服务中心） | 实验室与资产管理处 | 基建处 | 临港新校区建设综合办公室 | 图书馆  | 现代教育技术中心 / 信息办 | 创新创业工程训练中心 | 资产经营公司 / 产业办 | 能源电力科创中心 | 技术转移中心 |
| -------------------- | ---------- | ---------- | ------ | ------ | ------ | ------ | ------ | -------------------------------- | --------------- | ------ | -------- | -------------------------- | ------------------ | ------ | ------------------------ | ------- | ------------------------- | -------------------- | --------------------- | ---------------- | ------------ |
| office               | dwllc      | fzghc      | sjc    | bwc    | xsc    | rsc    | tgb    | fao                              | kyc             | jwc    | yjsc     | hqglc                      | sysyzcglc          | jjc    | lgxq                     | library | metc                      | ieetc                | cyb                   | kczx             | jszyzx       |
| 389                  | 2649       | 291        | 199    | tzgg   | 3482   | 1695   | notice | tzgg                             | 834             | 227    | 1161     | 1616                       | 312                | 327    | 377                      | 4866    | tzgg                      | cxcy                 | 367                   | 3946             | 4247         |

其它：

| 新闻网 | 信息公开网 | 本科招生网 | 本科就业信息网 | 文明办  | 学习路上 | “学条例 守党纪” 专题网 | 上海新能源人才技术教育交流中心 | 上海绿色能源并网技术研究中心 | 能源电力智库 | 智能发电实验教学中心 |
| ------ | ---------- | ---------- | -------------- | ------- | -------- | ---------------------- | ------------------------------ | ---------------------------- | ------------ | -------------------- |
| news   | xxgk       | zs         | career         | wenming | ztjy     | xxjy                   | gec                            | green-energy                 | nydlzk       | spgc                 |
| notice | zxgkxx     | zxxx       | tzgg           | 2202    | 5575     | 5973                   | 1959                           | 118                          | tzgg         | 4449                 |

参数与来源页面对应规则为：`https://${type}.shiep.edu.cn/${id}/list.htm`

## Parameters
- `type`: 类型名称，见下表
- `id`: 页面 ID，默认为通知公告或学院公告所对应的 ID


## Features
_None_

## Radar
### Rule 1
- `title`: `武装部保卫处`
- `source`:
  - `bwc.shiep.edu.cn/:id/list.htm`
- `target`: `/bwc/:id`
### Rule 2
- `title`: `本科就业信息网`
- `source`:
  - `career.shiep.edu.cn/news/index/tag/:id`
- `target`: `/career/:id`
### Rule 3
- `title`: `资产经营公司/产业办`
- `source`:
  - `cyb.shiep.edu.cn/:id/list.htm`
- `target`: `/cyb/:id`
### Rule 4
- `title`: `党委办公室`
- `source`:
  - `dangban.shiep.edu.cn/:id/list.htm`
- `target`: `/dangban/:id`
### Rule 5
- `title`: `党建服务中心/党建督查室`
- `source`:
  - `djfwzxdcs.shiep.edu.cn/:id/list.htm`
- `target`: `/djfwzxdcs/:id`
### Rule 6
- `title`: `电气工程学院`
- `source`:
  - `dqxy.shiep.edu.cn/:id/list.htm`
- `target`: `/dqxy/:id`
### Rule 7
- `title`: `对外联络处`
- `source`:
  - `dwllc.shiep.edu.cn/:id/list.htm`
- `target`: `/dwllc/:id`
### Rule 8
- `title`: `电子与信息工程学院`
- `source`:
  - `dxxy.shiep.edu.cn/:id/list.htm`
- `target`: `/dxxy/:id`
### Rule 9
- `title`: `能源与机械工程学院`
- `source`:
  - `energy.shiep.edu.cn/:id/list.htm`
- `target`: `/energy/:id`
### Rule 10
- `title`: `上海热交换系统节能工程技术研究中心`
- `source`:
  - `energy-saving.shiep.edu.cn/:id/list.htm`
- `target`: `/energy-saving/:id`
### Rule 11
- `title`: `Shanghai University of Electric Power`
- `source`:
  - `english.shiep.edu.cn/:id/list.htm`
- `target`: `/english/:id`
### Rule 12
- `title`: `国际交流与合作处（港澳台办公室）`
- `source`:
  - `fao.shiep.edu.cn/:id/list.htm`
- `target`: `/fao/:id`
### Rule 13
- `title`: `妇工委`
- `source`:
  - `fgw.shiep.edu.cn/:id/list.htm`
- `target`: `/fgw/:id`
### Rule 14
- `title`: `发展规划处`
- `source`:
  - `fzghc.shiep.edu.cn/:id/list.htm`
- `target`: `/fzghc/:id`
### Rule 15
- `title`: `上海新能源人才技术教育交流中心`
- `source`:
  - `gec.shiep.edu.cn/:id/list.htm`
- `target`: `/gec/:id`
### Rule 16
- `title`: `工会`
- `source`:
  - `gonghui.shiep.edu.cn/:id/list.htm`
- `target`: `/gonghui/:id`
### Rule 17
- `title`: `上海绿色能源并网技术研究中心`
- `source`:
  - `green-energy.shiep.edu.cn/:id/list.htm`
- `target`: `/green-energy/:id`
### Rule 18
- `title`: `能源化学实验教学中心`
- `source`:
  - `hhsyzx.shiep.edu.cn/:id/list.htm`
- `target`: `/hhsyzx/:id`
### Rule 19
- `title`: `环境与化学工程学院`
- `source`:
  - `hhxy.shiep.edu.cn/:id/list.htm`
- `target`: `/hhxy/:id`
### Rule 20
- `title`: `后勤管理处（后勤服务中心）`
- `source`:
  - `hqglc.shiep.edu.cn/:id/list.htm`
- `target`: `/hqglc/:id`
### Rule 21
- `title`: `创新创业工程训练中心`
- `source`:
  - `ieetc.shiep.edu.cn/:id/list.htm`
- `target`: `/ieetc/:id`
### Rule 22
- `title`: `机关党委`
- `source`:
  - `jgdw.shiep.edu.cn/:id/list.htm`
- `target`: `/jgdw/:id`
### Rule 23
- `title`: `经济与管理学院`
- `source`:
  - `jgxy.shiep.edu.cn/:id/list.htm`
- `target`: `/jgxy/:id`
### Rule 24
- `title`: `纪委（监察专员办公室）`
- `source`:
  - `jijian.shiep.edu.cn/:id/list.htm`
- `target`: `/jijian/:id`
### Rule 25
- `title`: `基建处`
- `source`:
  - `jjc.shiep.edu.cn/:id/list.htm`
- `target`: `/jjc/:id`
### Rule 26
- `title`: `继续教育学院（国际教育学院）`
- `source`:
  - `jjxy.shiep.edu.cn/:id/list.htm`
- `target`: `/jjxy/:id`
### Rule 27
- `title`: `教师教学发展中心`
- `source`:
  - `jsjxfzzx.shiep.edu.cn/:id/list.htm`
- `target`: `/jsjxfzzx/:id`
### Rule 28
- `title`: `计算机科学与技术学院`
- `source`:
  - `jsjxy.shiep.edu.cn/:id/list.htm`
- `target`: `/jsjxy/:id`
### Rule 29
- `title`: `技术转移中心`
- `source`:
  - `jszyzx.shiep.edu.cn/:id/list.htm`
- `target`: `/jszyzx/:id`
### Rule 30
- `title`: `教务处`
- `source`:
  - `jwc.shiep.edu.cn/:id/list.htm`
- `target`: `/jwc/:id`
### Rule 31
- `title`: `电力装备设计与制造虚拟仿真中心`
- `source`:
  - `jxfz.shiep.edu.cn/:id/list.htm`
- `target`: `/jxfz/:id`
### Rule 32
- `title`: `能源电力科创中心`
- `source`:
  - `kczx.shiep.edu.cn/:id/list.htm`
- `target`: `/kczx/:id`
### Rule 33
- `title`: `科研处/融合办`
- `source`:
  - `kyc.shiep.edu.cn/:id/list.htm`
- `target`: `/kyc/:id`
### Rule 34
- `title`: `临港新校区建设综合办公室`
- `source`:
  - `lgxq.shiep.edu.cn/:id/list.htm`
- `target`: `/lgxq/:id`
### Rule 35
- `title`: `图书馆`
- `source`:
  - `library.shiep.edu.cn/:id/list.htm`
- `target`: `/library/:id`
### Rule 36
- `title`: `现代教育技术中心/信息办`
- `source`:
  - `metc.shiep.edu.cn/:id/list.htm`
- `target`: `/metc/:id`
### Rule 37
- `title`: `上海市电力材料防护与新材料重点实验室`
- `source`:
  - `mpep.shiep.edu.cn/:id/list.htm`
- `target`: `/mpep/:id`
### Rule 38
- `title`: `新闻网`
- `source`:
  - `news.shiep.edu.cn/:id/list.htm`
- `target`: `/news/:id`
### Rule 39
- `title`: `能源电力智库`
- `source`:
  - `nydlzk.shiep.edu.cn/:id/list.htm`
- `target`: `/nydlzk/:id`
### Rule 40
- `title`: `校长办公室（档案馆）`
- `source`:
  - `office.shiep.edu.cn/:id/list.htm`
- `target`: `/office/:id`
### Rule 41
- `title`: `国家新能源电力系统实验教学示范中心`
- `source`:
  - `rpstec.shiep.edu.cn/:id/list.htm`
- `target`: `/rpstec/:id`
### Rule 42
- `title`: `党委教师工作部/人事处`
- `source`:
  - `rsc.shiep.edu.cn/:id/list.htm`
- `target`: `/rsc/:id`
### Rule 43
- `title`: `人文艺术学院`
- `source`:
  - `rwysxy.shiep.edu.cn/:id/list.htm`
- `target`: `/rwysxy/:id`
### Rule 44
- `title`: `审计处`
- `source`:
  - `sjc.shiep.edu.cn/:id/list.htm`
- `target`: `/sjc/:id`
### Rule 45
- `title`: `马克思主义学院`
- `source`:
  - `skb.shiep.edu.cn/:id/list.htm`
- `target`: `/skb/:id`
### Rule 46
- `title`: `数理学院`
- `source`:
  - `slxy.shiep.edu.cn/:id/list.htm`
- `target`: `/slxy/:id`
### Rule 47
- `title`: `智能发电实验教学中心`
- `source`:
  - `spgc.shiep.edu.cn/:id/list.htm`
- `target`: `/spgc/:id`
### Rule 48
- `title`: `实验室与资产管理处`
- `source`:
  - `sysyzcglc.shiep.edu.cn/:id/list.htm`
- `target`: `/sysyzcglc/:id`
### Rule 49
- `title`: `离退休党委/退管办`
- `source`:
  - `tgb.shiep.edu.cn/:id/list.htm`
- `target`: `/tgb/:id`
### Rule 50
- `title`: `团委`
- `source`:
  - `tw.shiep.edu.cn/:id/list.htm`
- `target`: `/tw/:id`
### Rule 51
- `title`: `体育学院`
- `source`:
  - `tyb.shiep.edu.cn/:id/list.htm`
- `target`: `/tyb/:id`
### Rule 52
- `title`: `统战部`
- `source`:
  - `tzb.shiep.edu.cn/:id/list.htm`
- `target`: `/tzb/:id`
### Rule 53
- `title`: `文明办`
- `source`:
  - `wenming.shiep.edu.cn/:id/list.htm`
- `target`: `/wenming/:id`
### Rule 54
- `title`: `外国语学院`
- `source`:
  - `wgyxy.shiep.edu.cn/:id/list.htm`
- `target`: `/wgyxy/:id`
### Rule 55
- `title`: `宣传部（文明办、融媒体中心）`
- `source`:
  - `xcb.shiep.edu.cn/:id/list.htm`
- `target`: `/xcb/:id`
### Rule 56
- `title`: `学生处`
- `source`:
  - `xsc.shiep.edu.cn/:id/list.htm`
- `target`: `/xsc/:id`
### Rule 57
- `title`: `巡查办`
- `source`:
  - `xunchaban.shiep.edu.cn/:id/list.htm`
- `target`: `/xunchaban/:id`
### Rule 58
- `title`: `信息公开网`
- `source`:
  - `xxgk.shiep.edu.cn/:id/list.htm`
- `target`: `/xxgk/:id`
### Rule 59
- `title`: `研究生院/研工部`
- `source`:
  - `yjsc.shiep.edu.cn/:id/list.htm`
- `target`: `/yjsc/:id`
### Rule 60
- `title`: `自动化工程学院`
- `source`:
  - `zdhxy.shiep.edu.cn/:id/list.htm`
- `target`: `/zdhxy/:id`
### Rule 61
- `title`: `本科招生网`
- `source`:
  - `zs.shiep.edu.cn/:id/list.htm`
- `target`: `/zs/:id`
### Rule 62
- `title`: `学习路上`
- `source`:
  - `ztjy.shiep.edu.cn/:id/list.htm`
- `target`: `/ztjy/:id`
### Rule 63
- `title`: `组织部（老干部处、党校）`
- `source`:
  - `zzb.shiep.edu.cn/:id/list.htm`
- `target`: `/zzb/:id`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "类型名称与默认 ID：\n\n学院一览：\n\n| 能源与机械工程学院 | 环境与化学工程学院 | 电气工程学院 | 自动化工程学院 | 计算机科学与技术学院 | 电子与信息工程学院 | 经济与管理学院 | 数理学院 | 外国语学院 | 体育学院 | 马克思主义学院 | 人文艺术学院 | 继续教育学院（国际教育学院） | 海上风电研究院 |\n| ------------------ | ------------------ | ------------ | -------------- | -------------------- | ------------------ | -------------- | -------- | ---------- | -------- | -------------- | ------------ | ---------------------------- | -------------- |\n| energy             | hhxy               | dqxy         | zdhxy          | jsjxy                | dxxy               | jgxy           | slxy     | wgyxy      | tyb      | skb            | rwysxy       | jjxy                         | hsfdyjy        |\n| 892                | 5559               | 2462         | 2002           | xygg                 | tzgg               | 3633           | 2063     | tzgg       | 2891     | 1736           | 3089         | 2582                         | 5748           |\n\n党群部门：\n\n| 党委办公室 | 组织部（老干部处、党校） | 党建服务中心 / 党建督查室 | 宣传部（文明办、融媒体中心） | 统战部 | 机关党委 | 纪委（监察专员办公室） | 巡查办    | 武装部 | 学生工作部 | 团委 | 工会（妇工委） | 教师工作部 | 离退休党委 | 研究生工作部 |\n| ---------- | ------------------------ | ------------------------- | ---------------------------- | ------ | -------- | ---------------------- | --------- | ------ | ---------- | ---- | -------------- | ---------- | ---------- | ------------ |\n| dangban    | zzb                      | djfwzxdcs                 | xcb                          | tzb    | jgdw     | jijian                 | xunchaban | bwc    | xsc        | tw   | gonghui        | rsc        | tgb        | yjsc         |\n| 4013       | 1534                     | tzgg                      | 2925                         | 3858   | 3205     | 59                     | 5044      | tzgg   | 3482       | 2092 | 1806           | 1695       | notice     | 1161         |\n\n行政部门：\n\n| 校长办公室（档案馆） | 对外联络处 | 发展规划处 | 审计处 | 保卫处 | 学生处 | 人事处 | 退管办 | 国际交流与合作处（港澳台办公室） | 科研处 / 融合办 | 教务处 | 研究生院 | 后勤管理处（后勤服务中心） | 实验室与资产管理处 | 基建处 | 临港新校区建设综合办公室 | 图书馆  | 现代教育技术中心 / 信息办 | 创新创业工程训练中心 | 资产经营公司 / 产业办 | 能源电力科创中心 | 技术转移中心 |\n| -------------------- | ---------- | ---------- | ------ | ------ | ------ | ------ | ------ | -------------------------------- | --------------- | ------ | -------- | -------------------------- | ------------------ | ------ | ------------------------ | ------- | ------------------------- | -------------------- | --------------------- | ---------------- | ------------ |\n| office               | dwllc      | fzghc      | sjc    | bwc    | xsc    | rsc    | tgb    | fao                              | kyc             | jwc    | yjsc     | hqglc                      | sysyzcglc          | jjc    | lgxq                     | library | metc                      | ieetc                | cyb                   | kczx             | jszyzx       |\n| 389                  | 2649       | 291        | 199    | tzgg   | 3482   | 1695   | notice | tzgg                             | 834             | 227    | 1161     | 1616                       | 312                | 327    | 377                      | 4866    | tzgg                      | cxcy                 | 367                   | 3946             | 4247         |\n\n其它：\n\n| 新闻网 | 信息公开网 | 本科招生网 | 本科就业信息网 | 文明办  | 学习路上 | “学条例 守党纪” 专题网 | 上海新能源人才技术教育交流中心 | 上海绿色能源并网技术研究中心 | 能源电力智库 | 智能发电实验教学中心 |\n| ------ | ---------- | ---------- | -------------- | ------- | -------- | ---------------------- | ------------------------------ | ---------------------------- | ------------ | -------------------- |\n| news   | xxgk       | zs         | career         | wenming | ztjy     | xxjy                   | gec                            | green-energy                 | nydlzk       | spgc                 |\n| notice | zxgkxx     | zxxx       | tzgg           | 2202    | 5575     | 5973                   | 1959                           | 118                          | tzgg         | 4449                 |\n\n参数与来源页面对应规则为：`https://${type}.shiep.edu.cn/${id}/list.htm`",
  "example": "/shiep/news/notice",
  "heat": 1,
  "location": "index.tsx",
  "maintainers": [
    "gumibea",
    "TeamSUEP"
  ],
  "name": "新闻网与学院通知",
  "parameters": {
    "id": "页面 ID，默认为通知公告或学院公告所对应的 ID",
    "type": "类型名称，见下表"
  },
  "path": "/:type/:id?",
  "radar": [
    {
      "source": [
        "bwc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/bwc/:id",
      "title": "武装部保卫处"
    },
    {
      "source": [
        "career.shiep.edu.cn/news/index/tag/:id"
      ],
      "target": "/career/:id",
      "title": "本科就业信息网"
    },
    {
      "source": [
        "cyb.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/cyb/:id",
      "title": "资产经营公司/产业办"
    },
    {
      "source": [
        "dangban.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/dangban/:id",
      "title": "党委办公室"
    },
    {
      "source": [
        "djfwzxdcs.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/djfwzxdcs/:id",
      "title": "党建服务中心/党建督查室"
    },
    {
      "source": [
        "dqxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/dqxy/:id",
      "title": "电气工程学院"
    },
    {
      "source": [
        "dwllc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/dwllc/:id",
      "title": "对外联络处"
    },
    {
      "source": [
        "dxxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/dxxy/:id",
      "title": "电子与信息工程学院"
    },
    {
      "source": [
        "energy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/energy/:id",
      "title": "能源与机械工程学院"
    },
    {
      "source": [
        "energy-saving.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/energy-saving/:id",
      "title": "上海热交换系统节能工程技术研究中心"
    },
    {
      "source": [
        "english.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/english/:id",
      "title": "Shanghai University of Electric Power"
    },
    {
      "source": [
        "fao.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/fao/:id",
      "title": "国际交流与合作处（港澳台办公室）"
    },
    {
      "source": [
        "fgw.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/fgw/:id",
      "title": "妇工委"
    },
    {
      "source": [
        "fzghc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/fzghc/:id",
      "title": "发展规划处"
    },
    {
      "source": [
        "gec.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/gec/:id",
      "title": "上海新能源人才技术教育交流中心"
    },
    {
      "source": [
        "gonghui.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/gonghui/:id",
      "title": "工会"
    },
    {
      "source": [
        "green-energy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/green-energy/:id",
      "title": "上海绿色能源并网技术研究中心"
    },
    {
      "source": [
        "hhsyzx.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/hhsyzx/:id",
      "title": "能源化学实验教学中心"
    },
    {
      "source": [
        "hhxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/hhxy/:id",
      "title": "环境与化学工程学院"
    },
    {
      "source": [
        "hqglc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/hqglc/:id",
      "title": "后勤管理处（后勤服务中心）"
    },
    {
      "source": [
        "ieetc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/ieetc/:id",
      "title": "创新创业工程训练中心"
    },
    {
      "source": [
        "jgdw.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jgdw/:id",
      "title": "机关党委"
    },
    {
      "source": [
        "jgxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jgxy/:id",
      "title": "经济与管理学院"
    },
    {
      "source": [
        "jijian.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jijian/:id",
      "title": "纪委（监察专员办公室）"
    },
    {
      "source": [
        "jjc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jjc/:id",
      "title": "基建处"
    },
    {
      "source": [
        "jjxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jjxy/:id",
      "title": "继续教育学院（国际教育学院）"
    },
    {
      "source": [
        "jsjxfzzx.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jsjxfzzx/:id",
      "title": "教师教学发展中心"
    },
    {
      "source": [
        "jsjxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jsjxy/:id",
      "title": "计算机科学与技术学院"
    },
    {
      "source": [
        "jszyzx.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jszyzx/:id",
      "title": "技术转移中心"
    },
    {
      "source": [
        "jwc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jwc/:id",
      "title": "教务处"
    },
    {
      "source": [
        "jxfz.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/jxfz/:id",
      "title": "电力装备设计与制造虚拟仿真中心"
    },
    {
      "source": [
        "kczx.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/kczx/:id",
      "title": "能源电力科创中心"
    },
    {
      "source": [
        "kyc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/kyc/:id",
      "title": "科研处/融合办"
    },
    {
      "source": [
        "lgxq.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/lgxq/:id",
      "title": "临港新校区建设综合办公室"
    },
    {
      "source": [
        "library.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/library/:id",
      "title": "图书馆"
    },
    {
      "source": [
        "metc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/metc/:id",
      "title": "现代教育技术中心/信息办"
    },
    {
      "source": [
        "mpep.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/mpep/:id",
      "title": "上海市电力材料防护与新材料重点实验室"
    },
    {
      "source": [
        "news.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/news/:id",
      "title": "新闻网"
    },
    {
      "source": [
        "nydlzk.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/nydlzk/:id",
      "title": "能源电力智库"
    },
    {
      "source": [
        "office.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/office/:id",
      "title": "校长办公室（档案馆）"
    },
    {
      "source": [
        "rpstec.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/rpstec/:id",
      "title": "国家新能源电力系统实验教学示范中心"
    },
    {
      "source": [
        "rsc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/rsc/:id",
      "title": "党委教师工作部/人事处"
    },
    {
      "source": [
        "rwysxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/rwysxy/:id",
      "title": "人文艺术学院"
    },
    {
      "source": [
        "sjc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/sjc/:id",
      "title": "审计处"
    },
    {
      "source": [
        "skb.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/skb/:id",
      "title": "马克思主义学院"
    },
    {
      "source": [
        "slxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/slxy/:id",
      "title": "数理学院"
    },
    {
      "source": [
        "spgc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/spgc/:id",
      "title": "智能发电实验教学中心"
    },
    {
      "source": [
        "sysyzcglc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/sysyzcglc/:id",
      "title": "实验室与资产管理处"
    },
    {
      "source": [
        "tgb.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/tgb/:id",
      "title": "离退休党委/退管办"
    },
    {
      "source": [
        "tw.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/tw/:id",
      "title": "团委"
    },
    {
      "source": [
        "tyb.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/tyb/:id",
      "title": "体育学院"
    },
    {
      "source": [
        "tzb.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/tzb/:id",
      "title": "统战部"
    },
    {
      "source": [
        "wenming.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/wenming/:id",
      "title": "文明办"
    },
    {
      "source": [
        "wgyxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/wgyxy/:id",
      "title": "外国语学院"
    },
    {
      "source": [
        "xcb.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/xcb/:id",
      "title": "宣传部（文明办、融媒体中心）"
    },
    {
      "source": [
        "xsc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/xsc/:id",
      "title": "学生处"
    },
    {
      "source": [
        "xunchaban.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/xunchaban/:id",
      "title": "巡查办"
    },
    {
      "source": [
        "xxgk.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/xxgk/:id",
      "title": "信息公开网"
    },
    {
      "source": [
        "yjsc.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/yjsc/:id",
      "title": "研究生院/研工部"
    },
    {
      "source": [
        "zdhxy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/zdhxy/:id",
      "title": "自动化工程学院"
    },
    {
      "source": [
        "zs.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/zs/:id",
      "title": "本科招生网"
    },
    {
      "source": [
        "ztjy.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/ztjy/:id",
      "title": "学习路上"
    },
    {
      "source": [
        "zzb.shiep.edu.cn/:id/list.htm"
      ],
      "target": "/zzb/:id",
      "title": "组织部（老干部处、党校）"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海电力大学-电子与信息工程学院 - Powered by RSSHub",
      "errorAt": "2025-10-29T11:02:15.842Z",
      "errorMessage": "[GET] \"https://dxxy.shiep.edu.cn/5182/list.htm\": <no response> fetch failed\n",
      "id": "150017010215692288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dxxy.shiep.edu.cn/5182/list.htm",
      "title": "上海电力大学-电子与信息工程学院",
      "type": "feed",
      "url": "rsshub://shiep/dxxy/5182"
    }
  ]
}
```
