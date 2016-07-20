#### 单个计费配置修改接口

#### 接口地址
  * 正式接口：/userreview/fee/config-edit

#### 请求参数说明
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| package_id      | 配置id |必选    |
|user_is_paid	| 用户类型 0:试用用户 1:付费用户 |可选    |
|review_status	| 0:未审核 100:不通过 200:通过|可选    |
|traffic_flow	| 流量(单位G) 计费类型为流量时有效|可选    |
|storage_space	| 存储(单位G) 计费类型为流量时有效|可选    |

#### 返回示例
```javascript
{
    "err": 0,
    "msg": "success",
    "data": []
}
```

#### 返回结果说明
```javascript
..
```