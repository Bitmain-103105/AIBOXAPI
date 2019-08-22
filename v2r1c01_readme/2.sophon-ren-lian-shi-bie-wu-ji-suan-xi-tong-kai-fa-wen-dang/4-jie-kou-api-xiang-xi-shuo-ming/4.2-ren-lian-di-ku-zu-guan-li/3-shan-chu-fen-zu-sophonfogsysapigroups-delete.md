# 删除分组/SophonFogSys/api/groups（DELETE）

**功能描述**

删除一个分组，组名具有唯一性。删除

**调用URL**

调用方法: DELETE

**请求参数（JSON格式）**

| 参数 | 类型 | 默认值 | 选择 | 描述 | 举例 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| group\_name | string | 无 | 必选 | 分组名称 | ”default\_group“ |
| user\_recursive\_delete | boolean | false | 可选 | 默认为false，删除分组，保留人员。如果为True，删除分组的同时，把人员，人脸一起删除 |  |

请求示例：

```javascript
请求url: http://192.168.1.180:5555/SophonFogSys/api/groups?
请求body:
        {
            "group_name":"default_group"
        }
```

**返回信息：**

请求成功

| 一级参数 | 二级参数 | 描述 |
| :--- | :--- | :--- |
| data | group\_name | 分组名称 |
|  | message | 返回信息 |

请求成功示例：

```javascript
{
    "data": {
        "group_name": "default_group",
        "message": "just delete the group info,the user already exists"
    }
}
```

请求失败

| 一级参数 | 二级参数 | 类型 | 描述 |
| :--- | :--- | :--- | :--- |
| error | code | int | 请求错误码 |
|  | message | string | 错误描述 |
|  | status | string | 错误类型 |

