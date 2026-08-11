# Thailand Parliament - Thailand Parliament Draft of Law's public hearing system

## Coverage
`index-only`

## Route
- Namespace: `parliament`
- Namespace Name: `Thailand Parliament`
- Route Path: `/parliament/section77/:type?`
- Route Name: `Thailand Parliament Draft of Law's public hearing system`
- Example: `/parliament/section77`
- URL: `parliament.go.th`
- Language: `_None_`
- Categories: `government`
- Maintainers: `itpcc`
- Source Location: `section77.ts`
- Source Module: `_None_`

## Description
| Presented by MP \*       | Presented by People \* | Hearing Ongoing      | Hearing ended   | Hearing result reported  | Waiting for PM approval | Assigned into the session | Processed  | PM Rejected   |
| ------------------------ | ---------------------- | -------------------- | --------------- | ------------------------ | ----------------------- | ------------------------- | ---------- | ------------- |
| presentbymp              | presentbyperson        | openwsu              | closewsu        | reportwsu                | substatus1              | substatus2                | substatus3 | closewsubypm  |
| เสนอโดยสมาชิกสภาผู้แทนราษฏร | เสนอโดยประชาชน         | กำลังเปิดรับฟังความคิดเห็น | ปิดรับฟังความคิดเห็น | รายงานผลการรับฟังความคิดเห็น | รอคำรับรองจากนายกรัฐมนตรี  | บรรจุเข้าระเบียบวาระ         | พิจารณาแล้ว  | นายกฯ ไม่รับรอง |

*Note:* For `presentbymp` and `presentbyperson`, it can also add:

- `-m` for the draft which Speaker of Parliament considered as a monetary draft (ประธานสภาผู้แทนราษฎรวินิจฉัยว่า เป็นร่างการเงิน), or
- `-nm` for non-monetary one (ประธานสภาผู้แทนราษฎรวินิจฉัยว่า ไม่เป็นร่างการเงิน).

## Parameters
- `type`: Type of hearing status, see below


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
    "government"
  ],
  "description": "| Presented by MP \\*       | Presented by People \\* | Hearing Ongoing      | Hearing ended   | Hearing result reported  | Waiting for PM approval | Assigned into the session | Processed  | PM Rejected   |\n| ------------------------ | ---------------------- | -------------------- | --------------- | ------------------------ | ----------------------- | ------------------------- | ---------- | ------------- |\n| presentbymp              | presentbyperson        | openwsu              | closewsu        | reportwsu                | substatus1              | substatus2                | substatus3 | closewsubypm  |\n| เสนอโดยสมาชิกสภาผู้แทนราษฏร | เสนอโดยประชาชน         | กำลังเปิดรับฟังความคิดเห็น | ปิดรับฟังความคิดเห็น | รายงานผลการรับฟังความคิดเห็น | รอคำรับรองจากนายกรัฐมนตรี  | บรรจุเข้าระเบียบวาระ         | พิจารณาแล้ว  | นายกฯ ไม่รับรอง |\n\n*Note:* For `presentbymp` and `presentbyperson`, it can also add:\n\n- `-m` for the draft which Speaker of Parliament considered as a monetary draft (ประธานสภาผู้แทนราษฎรวินิจฉัยว่า เป็นร่างการเงิน), or\n- `-nm` for non-monetary one (ประธานสภาผู้แทนราษฎรวินิจฉัยว่า ไม่เป็นร่างการเงิน).",
  "example": "/parliament/section77",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "section77.ts",
  "maintainers": [
    "itpcc"
  ],
  "name": "Thailand Parliament Draft of Law's public hearing system",
  "parameters": {
    "type": "Type of hearing status, see below"
  },
  "path": "/section77/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
