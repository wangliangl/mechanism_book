考勤统计
-----------

#### URL

> [http://120.76.218.161:8362/Mall/Worke/getAttendanceCount](http://120.76.218.161:8362/Mall/Worker/getAttendanceCount)

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
|data | array | 考勤统计列表信息 |

#### 接口示例

> 地址：[http://120.76.218.161:8362/Mall/Worker/getAttendanceCount](http://120.76.218.161:8362/Mall/Worker/getAttendanceCount)

```json
{
    "code":1,
    "data":[
        {
            "id":"512",
            "eployee_pic":"",
            "eployee_name":"程永笑",
            "eployee_address":"昌平",
            "eployee_department":"策划部",
            "eployee_phone":"18310687332",
            "thedate":"2018-06-13",
            "punch_in":"17:00:56",
            "punch_in_state":"0",
            "punch_out":null,
            "punch_out_state":null,
            "remarks":null,
            "am_remark":"迟到",
            "pm_remark":null,
            "card_no":"5070694",
            "worker_id":"378",
            "eployee_position":"设计",
            "input":null,
            "check_state":"0",
            "worker_type":"1"
        }
    ],
    "total":"1",
    "page_count":1
}
```
