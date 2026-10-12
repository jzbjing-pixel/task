# 任务管理 · Rill 插件发布仓库

版本：0.1.0。仅发布编译后的签名安装包，源码在本地统一管理。

需要 2026-10-12 或更新构建的 Rill 安装版，使用统一 Host API 2。

在插件管理中添加仓库 https://github.com/jzbjing-pixel/task ，选择 Git 仓库安装，资源名为 rill-plugin.git.zip。

发布者公钥：

```text
MFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEQFY6RRY7CGDRz7UIEc23akHfRVOKXeHaIjkzSKkrW/OZ4c9MgRak7LsQpRchUPcXEJCKfN7qVmnADRDotBgniQ==
```

也可下载 dist/rill-plugin.git.zip，先添加上述发布者公钥，再从本地安装。

插件数据保存于宿主多维表，卸载不删除业务数据。
