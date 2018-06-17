# 使用Node.js搭建Web服务器


## 启动
```
node start
```

## 功能

* 能显示以 `.html/.htm` 结尾的 Web 页面

* 能直接打开以 `.js/.css/.json/.text` 结尾的文件内容

* 显示图片资源

* 自动下载以 `.apk/.docx/.zip` 结尾的文件

* 形如 `http://xxx.com/a/b/` , 则查找b目录下是否有 `index.html`,如果有就显示，如果没有就列出该目录下的所有文件及文件夹，并可以进一步访问。

* 形如 `http://xxx.com/a/b`,  则作301重定向到 `http://xxx.com/a/b/` , 这样可以解决内部资源引用错位的问题。
