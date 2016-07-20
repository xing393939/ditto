#### 计费添加前计算价格接口

#### 接口地址
  * 正式接口：/userreview/fee/add-price

#### 请求参数说明
|  参数         |说明          |是否必选|
| ------------- |:-------------|:-----:|
| traffic_flow      | 购买流量，单位G |可选    |
| storage_space      | 购买空间，单位G |可选    |

#### 返回示例
```javascript
{
    "err": 0,
    "msg": "success",
    "data": {
        "price": 15.3
    }
}
```

#### 返回结果说明
```javascript
..
```