# reader-store

🏪 香烟啤酒八宝粥，瓜子饮料矿泉水。

## 贡献方式

### 存储在该仓库里面

fork 后更新代码到该仓库，然后提交 PR。

### 只注册插件

只更新 db.json 不把爬取规则放到这个仓库里面，另外开一个仓库。


## 一定要保证 db.json 格式正确

> 🚑 要不然会导致所有服务不可用。


### 格式参照 

```
  {
    "filename": "www.ybdu.com.js",
    "description": "下载 [www.ybdu.com](https://www.ybdu.com) 的小说的逻辑",
    "url": "https://raw.githubusercontent.com/MiYogurt/ybdy_downloader/master/www.ybdu.com.js",
    "repository": "https://github.com/MiYogurt/ybdy_downloader",
    "author": "MiYogurt"
  }
```

### 爬取规则参考 

https://github.com/MiYogurt/ybdy_downloader
