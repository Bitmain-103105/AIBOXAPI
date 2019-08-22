# 从分组删除人员/SophonFogSys/api/GroupUsers（DELETE）

**功能描述**

一个分组中删除人员。

**调用URL**

调用方法: DELETE

**请求参数（JSON格式）**

| 参数 | 类型 | 默认值 | 选择 | 描述 | 举例 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| group\_name | string | 无 | 必选 | 分组名称 |  |
| identity\_id | list | 无 | 必选 | 用户id列表\[\["123345","23455"\]\([https://info.bitmain.vip:8443/pages/createpage.action?spaceKey=AIBOX&title="123345"%2C"23455"&linkCreation=true&fromPageId=59841178](https://info.bitmain.vip:8443/pages/createpage.action?spaceKey=AIBOX&title="123345"%2C"23455"&linkCreation=true&fromPageId=59841178)\)\] |  |
| with\_identity\_id | boolean | false | 可选 | 默认为false，不返回该组的identity\_id如果为true，返回该组的identity\_id |  |

请求示例：

```javascript
请求url: http://192.168.1.180:5555/SophonFogSys/api/GroupUsers?
请求body:
        {
            "group_name":"测试组",
            "identity_id":["001","002"],
            "with_identity_id":true

        }
```

**返回信息：**

请求成功

| 一级参数 | 二级参数 | 类型 | 描述 |
| :--- | :--- | :--- | :--- |
| data | group\_name | string | 分组名称 |
|  | message | string | 返回信息 |
|  | identity\_id | list | 默认为false，不返回该组的identity\_id如果为true，返回该组的identity\_id |

请求成功示例：

```javascript
{
    "data": {
        "group_name": "测试组",
        "identity_id": ["003"]
    }
}
```

请求失败

| 一级参数 | 二级参数 | 类型 | 描述 |
| :--- | :--- | :--- | :--- |
| error | code | int | 请求错误码 |
|  | message | string | 错误描述 |
|  | status | string | 错误类型 |

