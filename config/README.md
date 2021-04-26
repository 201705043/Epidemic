## 详细部署方法

1. 登录 [Github](https://github.com/login), [如果没有账号请先注册](https://github.com/join?return_to=%2Fjoin%3Fref_cta%3DSign%2Bup%26ref_loc%3Dheader%2Blogged%2Bout%26ref_page%3D%252F%26source%3Dheader-home&source=login)

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/1.png)

2. 打开[我的仓库](https://github.com/chiupam/Epidemic), 点击右上角的 `Fork`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/2.png)

3. 点击页面中上部的 `Settings`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/3.png)

4. 点击页面左侧的 `Secret`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/4.png)

5. 点击页面右上部的 `New repository secret`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/5.png)

6. 请查阅右侧提供的文档 -> [Value](https://github.com/chiupam/Epidemic/blob/main/config/json.md)

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

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/6.png)

7. 点击页面中上部的 `Actions`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/7.png)

8. 点击页面中间绿色方块的 `I understand my workflows, go ahead ande enable them`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/8.png)

9. 点击页面左侧的 `EpidemicTask` 后点击右侧的 `Enable workflow`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/9.png)

10. **首次运行**请点击右侧白色方块的 `Run workflow`, 在随后弹出的方框中点击绿色方块的 `Run workflow`

![image](https://raw.githubusercontent.com/chiupam/Epidemic/main/config/png/10.png)
