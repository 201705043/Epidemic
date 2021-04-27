## 详细部署方法

1. 分为有 Github 账号和无 Github 账号两种情况

- 如果有 Github 账号, [右键此处](https://github.com/login)后点击 `在新的标签页中打开链接`, 在弹出的页面中登录 Github, 最后[回到这个页面](https://gitee.com/chiupam/Epidemic/blob/master/config/README.md)开始操作第2步

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/1.png)

- 如果无 Github 账号, [右键此处](https://github.com/join?return_to=%2Fjoin%3Fref_cta%3DSign%2Bup%26ref_loc%3Dheader%2Blogged%2Bout%26ref_page%3D%252F%26source%3Dheader-home&source=login)后点击 `在新的标签页中打开链接`, 在弹出的页面中注册 Github, 不懂如何注册的请点击[这里](https://gitee.com/chiupam/Epidemic/blob/master/config/create_account.md)查阅文档, 最后[回到这个页面](https://gitee.com/chiupam/Epidemic/blob/master/config/README.md)开始操作第2步

2. [右键此处](https://github.com/chiupam/Epidemic)点击 `在新的标签页中打开链接` 后在弹出的页面中点击右上角的 `Fork`, 如果出现需要验证邮箱的情况请点击[此处](https://gitee.com/chiupam/Epidemic/blob/master/config/verification.md)查看文档, 完成 `Fork` 此步后不需要回到此页面, 后续的操作都是在弹出的页面中进行

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/2.png)

3. 点击页面中上部的 `Settings`

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/3.png)

4. 点击页面左侧的 `Secret`

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/4.png)

5. 点击页面右上部的 `New repository secret`

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/5.png)

6. 先在 `Name` 中填写 `USER`, 其下方 `Value` 的填写请查阅右侧提供的文档 -> [Value](https://gitee.com/chiupam/Epidemic/blob/master/config/json.md)

```txt
发现比较多人在点击 Add sceret 后会出现网络错误，待能访问 Github 后直接重复操作第6步即可
```

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

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/6.png)

7. 点击页面中上部的 `Actions`

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/7.png)

8. 点击页面中间绿色方块的 `I understand my workflows, go ahead ande enable them`

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/8.png)

9. 点击页面左侧的 `EpidemicTask` 后点击右侧的 `Enable workflow`

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/9.png)

10. **首次运行**请点击右侧白色方块的 `Run workflow`, 在随后弹出的方框中点击绿色方块的 `Run workflow`

![image](https://gitee.com/chiupam/Epidemic/raw/master/config/png/10.png)

11. 如何查看执行日志请点击[此处](https://gitee.com/chiupam/Epidemic/blob/master/config/check_log.md)

12. 自动化执行60天后会自动 `Unenable workflow`, 解决方法有两种：

- 第一种方法：只需要操作第7步、第9步即可~ 

- 第二种方法：每60天内编辑一次`REAMDE.md`(内容随便删减)并点击下方的`Commit change`也可，不懂的可以点击[此处](https://gitee.com/chiupam/Epidemic/blob/master/config/edit.md)
