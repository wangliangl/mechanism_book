考勤列表设置
-----------

#### URL

> [http://120.76.218.161:8362/Merchant/Attendence/getAttendenceList?attendance_owner_type=0](http://120.76.218.161:8362/Merchant/Attendence/getAttendenceList?attendance_owner_type=0)

#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数

|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
| page| false|int| 页数|
|pagesize|false|int| 每页几条|
|attendance_owner_type|true|int| 0商场 1 机构|

#### 返回字段

|返回字段|字段类型|说明 |
|:----- |:------|:----------------------------- |
|code | int |返回结果状态。2：不正常；1：正常。 |
|data | array | 考勤统计列表信息 |

#### 接口示例

> 地址：[http://120.76.218.161:8362/Merchant/Attendence/getAttendenceList?attendance_owner_type=0](http://120.76.218.161:8362/Merchant/Attendence/getAttendenceList?attendance_owner_type=0)

```json
{
  "code": 1,
  "data": [
    {
      "id": "12",
      "in_time": "10:00:00",
      "out_time": "17:00:00",
      "mall_id": "1",
      "inst_id": null,
      "status": "0",
      "staff_id_list": "1,2,3",
      "staff_count": 3
    }
  ],
  "total": 1,
  "page_count": 1
}
```
