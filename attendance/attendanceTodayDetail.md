今日考勤明细
-----------

#### URL

> [/Mall/Worke/getAttendanceDetail](http://120.76.218.161:8362/Mall/Worker/getAttendance)

#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数

|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
| card_no| true | string | 会员卡号 |
|||||

#### 返回字段

|返回字段|字段类型|说明 |
|:----- |:------|:----------------------------- |
|code | int |返回结果状态。2：不正常；1：正常。 |
|data | array | 考勤明细信息 |

#### 接口示例

> 地址：[http://120.76.218.161:8362/Mall/Worker/getAttendanceDetail](http://120.76.218.161:8362/Mall/Worker/getAttendanceDetail)

```json
{
   "code": 1,
   "data": [
     {
       "id": "512",
       "eployee_pic": "",
       "eployee_name": "程永笑",
       "eployee_address": "昌平",
       "eployee_department": "策划部",
       "eployee_phone": "18310687332",
       "thedate": "2018-04-18",
       "punch_in": "17:00:56",
       "punch_in_state": "0",
       "punch_out": null,
       "punch_out_state": null,
       "remarks": null,
       "am_remark": "迟到",
       "pm_remark": null,
       "card_no": "5070694",
       "worker_id": "378",
       "eployee_position": "设计",
       "input": null,
       "check_state": "0",
       "worker_type": "1"
     },
     {
       "id": "511",
       "eployee_pic": "",
       "eployee_name": "程永笑",
       "eployee_address": "昌平",
       "eployee_department": "策划部",
       "eployee_phone": "18310687332",
       "thedate": "2018-04-17",
       "punch_in": "09:00:51",
       "punch_in_state": "1",
       "punch_out": null,
       "punch_out_state": null,
       "remarks": null,
       "am_remark": "正常",
       "pm_remark": null,
       "card_no": "5070694",
       "worker_id": "378",
       "eployee_position": "设计",
       "input": null,
       "check_state": "0",
       "worker_type": "1"
     }
   ],
   "total": "49",
   "page_count": 25
 }
```
