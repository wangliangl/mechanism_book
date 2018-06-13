考勤统计
-----------

#### URL

> [http://120.76.218.161:8362/Mall/Worker/getAttendanceCount?pagesize=2&pagesize=2](http://120.76.218.161:8362/Mall/Worker/getAttendanceCount?pagesize=2&pagesize=2)

#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数

|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
| | || |
||||

#### 返回字段

|返回字段|字段类型|说明 |
|:----- |:------|:----------------------------- |
|code | int |返回结果状态。2：不正常；1：正常。 |
|data | array | 考勤列表信息 |

#### 接口示例

> 地址：[http://120.76.218.161:8362/Mall/Worker/getAttendanceCount?pagesize=2&pagesize=2](http://120.76.218.161:8362/Mall/Worker/getAttendanceCount?pagesize=2&pagesize=2)

```json
{
  "code": 1,
  "data": [
    {
      "id": "452",
      "eployee_pic": "",
      "eployee_name": "孟磊",
      "eployee_address": "桂林市百货大楼",
      "eployee_department": "财务部",
      "eployee_phone": "18510021122",
      "thedate": "2018-03-08",
      "punch_in": "15:04:01",
      "punch_in_state": "0",
      "punch_out": "15:04:52",
      "punch_out_state": "0",
      "remarks": null,
      "am_remark": "迟到",
      "pm_remark": "早退",
      "card_no": "2718374096",
      "worker_id": "",
      "eployee_position": "财务",
      "input": null,
      "check_state": "0",
      "worker_type": "1",
      "am_zc": null,
      "am_cd": "1",
      "pm_zc": null,
      "pm_cd": "1"
    },
    {
      "id": "437",
      "eployee_pic": "",
      "eployee_name": "李玉霞",
      "eployee_address": "桂林市百货大楼",
      "eployee_department": "财务部",
      "eployee_phone": "18310687333",
      "thedate": "2018-03-03",
      "punch_in": "11:49:14",
      "punch_in_state": "0",
      "punch_out": "11:49:18",
      "punch_out_state": "0",
      "remarks": null,
      "am_remark": "迟到",
      "pm_remark": "早退",
      "card_no": "5098070",
      "worker_id": "",
      "eployee_position": "财务",
      "input": null,
      "check_state": "0",
      "worker_type": "1",
      "am_zc": null,
      "am_cd": "1",
      "pm_zc": null,
      "pm_cd": "1"
    }
  ],
  "total": 16,
  "page_count": 8
}
```
