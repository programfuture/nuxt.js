# 自动发日报

## 环境

> * node v8.11.3

## 配置

修改/src/config.json

```json
{
  "user": {
    "username": "日报系统用户名",
    "password": "密码"
  },
  "dailyList": [
    {
      "date": "2019/06/25",
      "recordList": [
        {
          "recordName": "活动页面",
          "eventName": "bug修复"
        }
      ]
    }
  ]
}
```

## 启动

```
$ npm run start
```
