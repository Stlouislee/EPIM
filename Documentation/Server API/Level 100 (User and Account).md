# EPIM SERVER API 设计文档

## LEVEL 100 用户级别

## Creating a user

#### 1) 请求地址

>https://service-q4l9bhk2-1252248915.ap-hongkong.apigateway.myqcloud.com/release/epimUserCreate

#### 2) 调用方式：HTTP post

#### 3) 接口描述：

* 接口描述详情

#### 4) 请求参数:

```
{
    "username": "Stephen",
    "passwd": "1231111",
    "uuid": "5427f184-a965-11e9-9a84-1617b9edde0c"
}
```

#### POST参数:
|字段名称       |字段说明         |类型            |必填            |备注     |
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|username|新建的用户名|string|Y|-|
|passwd|加密后的密码|string|Y|-|
|uuid|由注册的机器产生的UUID|string|Y|-|

#### 5) 请求返回结果:

```
{
    "Code": 110,
    "Msg": "User Stephen created. The UUID is 5427f184-a965-11e9-9a84-1617b9edde0c"
}
```


#### 6) 请求返回结果参数说明:
|字段名称       |字段说明         |类型            |必填            |备注     |
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|Code|返回值|iny|Y|-|
|Msg|提示信息|string|Y|-|





