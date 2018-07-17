## 员工详细信息列表

> 地址：
[http://120.76.218.161:8362/Mall/Worker/index_api?pagesize=10&page=1&keyword=&dept_id=&status=](http://120.76.218.161:8362/Mall/Worker/index_api?pagesize=10&page=1&keyword=&dept_id=&status=)

#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----:|
| page|NO |页数|
|pagesize|N| 每页几条
|keyword|N| 每页几条
|dept_id|N| 部门id
|status|N| 用户状态

#### 返回值
> 返回值

```json
{
    "code":1,
    "data":[
        {
            "id":"333",
            "pic":"/smartmalls/Public/Uploads/Images/Mall/1/thumb_5a221868a3dce.jpg",
            "name":"许睿",
            "number":"100333",
            "address":"北京",
            "dept_name":"管理部",
            "position_name":"股东",
            "sex":"男",
            "birthday":"1984-11-29",
            "phone":"13521724100",
            "emergency_contacts":"许睿",
            "marriage":"已婚",
            "cardnumber_no":"100988",
            "sex_name":"男",
            "age":33
        }
    ],
    "total":"6",
    "page_count":1
}
```

## 员工详情
>地址 [http://120.76.218.161:8362/Mall/Worker/worker_view_api](http://120.76.218.161:8362/Mall/Worker/worker_view_api)
>返回值
#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数
|参数|必选|类型|说明|
|:----- |:-------|:-----:|
|worker_id|Y |员工id|


```json
{
    "code":1,
    "data":{
        "id":"333",
        "number":"100333",
        "mall_id":"1",
        "state":"2",
        "phone":"13521724100",
        "sex":"1",
        "name":"许睿",
        "email":null,
        "pic":"/smartmalls/Public/Uploads/Images/Mall/1/thumb_5a221868a3dce.jpg",
        "birthday":"1984-11-29",
        "id_number":"110104197205201219",
        "birth_province_id":"1",
        "birth_city_id":"1",
        "birth_district_id":"1",
        "birth_address":"北京市-北京市-东城区",
        "address":"北京",
        "marriage":"1",
        "health":"1",
        "education":"4",
        "major":"计算机",
        "school":"清华",
        "dept_id":"70",
        "dept_name":"管理部",
        "position_id":"108",
        "position_name":"股东",
        "remarks":"",
        "join_time":"2017-11-29",
        "contract_time":"2018-11-29",
        "leave_time":null,
        "last_login_time":null,
        "nation":"汉",
        "emergency_contacts":"许睿",
        "emergency_phone":"13521724100",
        "remme":null,
        "token":null,
        "card_number":"0247370438",
        "role_id":"43",
        "cardnumber_no":"100988",
        "balance":"2887.38",
        "app_pwd":"ac54ac4272cf52c69c8c4e1ce60a530a",
        "sex_name":"男",
        "marriage_name":"已婚",
        "health_name":"健康",
        "education_name":"本科"
    }
}
```

## 删除员工
## 添加员工
## 修改员工
