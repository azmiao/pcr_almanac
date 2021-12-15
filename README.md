## pcr_almanac

一个适用hoshinobot的 pcr签到黄历 插件

功能仿造自[BillYang2016](https://github.com/BillYang2016)的酷Q黄历插件

甚至`data.json`的配置文件直接拿来用了，已获原作者授权

插件后续将继续在 github 不定期更新，欢迎提交 isuue 和 request

本插件仅供学习研究使用，插件免费，请勿用于违法商业用途，一切后果自己承担

## 项目地址：

https://github.com/azmiao/pcr_almanac

## 更新日志

21-12-15    v1.1    修复了宜和忌可能是同一件事的bug

## 功能

```
目前就一个命令：
[签到] 签到看黄历
```

## 简单食用教程：

1. 下载或git clone本插件：

    在 HoshinoBot\hoshino\modules 目录下使用以下命令拉取本项目
    ```
    git clone https://github.com/azmiao/pcr_almanac
    ```

2. 在 HoshinoBot\hoshino\config\ `__bot__.py` 文件的 MODULES_ON 加入 'pcr_almanac'

    然后重启 HoshinoBot