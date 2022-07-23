# zhenxun_plugin_ddcheck

zhenxun_bot 成分姬插件

移植自[nonebot-plugin-ddcheck](https://github.com/noneplugin/nonebot-plugin-ddcheck)

## 插件安装

1. 将本插件文件放到自定义插件目录下或放到extensive_plugin并安装相关依赖`pip3 install -r requirements.txt`

2. 使用真寻插件商店命令安装

   - 更新插件仓库
   - 查看插件仓库
   - 安装插件x(x为插件序号)

### 使用

```
查成分 + B站用户名/UID
```

若要显示主播牌子，需要在 `configs\config.yaml` 文件中添加任意的B站用户cookie：

```
BILIBILI_COOKIE: xxx
```

`cookie` 获取方式：

`F12` 打开开发工具，查看 `www.bilibili.com` 请求的响应头，找形如 `SESSDATA=xxx;` 的字段，如：

```
bilibili_cookie="SESSDATA=xxx;"
```

[![img](https://camo.githubusercontent.com/2f8d6fcd52dfbec7a4b5c8545cd6166a1ac9b162191d15ffadfb634c58a28efb/68747470733a2f2f73322e6c6f6c692e6e65742f323032322f30372f31392f4149426d64325a39563559776c6b462e706e67)](https://camo.githubusercontent.com/2f8d6fcd52dfbec7a4b5c8545cd6166a1ac9b162191d15ffadfb634c58a28efb/68747470733a2f2f73322e6c6f6c692e6e65742f323032322f30372f31392f4149426d64325a39563559776c6b462e706e67)

### 更新

**2022/7/23**[v0.5]

1. 添加关注列表未公开的提示

**2022/6/01**[v0.3]

1. 添加资源文件

**2022/5/24**[v0.2]

1. 修复bug

**2022/5/24**[v0.1]

1. 对真寻进行了适配

### 注意事项

服务器需要安装中文字体不然会乱码
