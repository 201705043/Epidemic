## 格式说明

```json
[
    {
        "_username": "XXXXXXXXX",
        "_password": "XXXXXX",
        "_notify": false,
        "_token": "XXXXXXXXXXXX"
    }
]
```

|键|值|备注|
|:-:|:-:|:-:|
|`_username`|学号||
|`_password`|密码|即身份证后6位|
|`_notify`|推送|开启推送则填写true 关闭推送则填false 关闭推送时下方的`_token`不需要填写值|
|`_token`|pushplus的token|[申请地址](http://www.pushplus.plus/push1.html) 关闭推送时此处不需要修改 开启推送时此处修改为token的值|

## 正确写法参考

1. 开启推送

```json
[
    {
        "_username": "202010001",
        "_password": "123456",
        "_notify": true,
        "_token": "abcdefghijklmnopqrstuvwxyz"
    }
]
```

2. 关闭推送

```json
[
    {
        "_username": "202010001",
        "_password": "123456",
        "_notify": false,
        "_token": "XXXXXXXXXXXX"
    }
]
```

3. 多账户签到

```json
[
    {
        "_username": "202010001",
        "_password": "123456",
        "_notify": true,
        "_token": "abcdefghijklmnopqrstuvwxyz"
    },
    {
        "_username": "202010002",
        "_password": "123456",
        "_notify": false,
        "_token": "XXXXXXXXXXXX"
    }
]
```
