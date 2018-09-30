# 激活

** 用户在完成任务，领取奖励后，调用激活 **


**请求URL：** 

- ` https://ow-api.houputech.com/idfa/activate `
  
**请求方式：**
- POST 

**请求参数：** 

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
|appkey |是  |string |授权key。由蚂蚁提供。   |
|appsecret |是  |string | 授权密钥。由蚂蚁提供。    |
|appid     |是  |string | 任务的appid。对应appstore appid。    |
|idfa     |是  |string | idfa   | 




 **返回示例**

``` 
{
  "code": "1000",
  "errmsg": ""
}
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----  |:-----|-----  |
|code |string   |返回码。1000：激活成功。其他为激活失败，见errmsg |
|errmsg |string   |错误信息  | 
