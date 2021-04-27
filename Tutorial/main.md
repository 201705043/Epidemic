# 正式开始部署

### 先明确两个名词：1. 这个页面：指你现在看到的网页 2. 新的页面：点击超链接打开的页面

1. [点击此处](https://github.com/chiupam/Epidemic)打开一个新的页面, 随后每一步操作都在那个新的页面中操作, 请不要在这个页面寻找任何标志

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/Epidemic.png)

2. 点击 `Fork` 按钮

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_1.png)

3. 先点击 `Settings`, 再点击 `Secret`, 最后点击 `New repository secret`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_2.png)

4. 先在 Name 中输入 PAT, 再在 Value 中输入 PAT 的值（申请方法点击[这里](xxx)）, 最后点击 `Add secret`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_3.png)

5. 先点击 `Settings`, 再点击 `Secret`, 最后点击 `New repository secret`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_4.png)

6. 先在 Name 中输入 USER, 再在 Value 中输入下方代码块中的模板（自行修改）, 最后点击 `Add secret`

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

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_5.png)

7. 先点击 `Actions`, 再点击 `I understand my workflow, go ahead and enable them`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_6.png)

8. 先点击 `Auto Sync`, 再点击 `Enable workflow`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_7.png)

9. 先点击 `Epidemic Task`, 再点击 `Enable workflow`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_8.png)

10. 先点击 `Epidemic Task`, 再点击 `Run workflow`, 最后点击 `Run workflow`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_9.png)

11. 点击 `Epidemic Task`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_10.png)

12. 点击 `deploy`

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_11.png)

13. 先点击 `deploy`, 再点击 `Bulid and publish`, 可见运行结果

![image](https://gitee.com/chiupam/Epidemic/raw/master/Tutorial/png/main_12.png)
