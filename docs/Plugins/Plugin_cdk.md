# cdk.mod
[简体中文](#%e7%ae%80%e4%bd%93%e4%b8%ad%e6%96%87)
## English

| Command | Desc |
| ------- | ---- |
| `/reload_cdk` | reload cdks |
| `/cdk [cdk]` | use cdks |

config: `cdk.json`
```json
{
    "key1": "give %name% dirt 1",
    "example": "say example"
}
```

If you want to add a cdk,you can add these in the configuration file:
```json
"cdk": "command"
```

> You should pay attention to the syntax of json<br>
> You can fill in multiple commands, please see usage: Plugin_base_cmd.md](Plugin_Base_cmd.md)

## 简体中文

| 指令 | 功能 |
| - | - |
| `/reload_cdk` | 重载cdk |
| `/cdk [cdk]` |  玩家兑换cdk |

配置文件: cdk.json
```json
{
    "key1": "give %name% dirt 1",
    "example": "say example"
}

```

如果你想要添加一个cdk，你可以这样做:
```json
"cdk内容": "执行的命令"
```
> 你应该注意json的语法<br>
> 执行的命令为指令序列，具体用法请参见[Plugin_base_cmd.md](Plugin_Base_cmd.md)