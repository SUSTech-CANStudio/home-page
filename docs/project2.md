---
id: project2
title: Folding At Home Server
---

# 部署流程

1. 安装 PHP7

2. 打开`src/`, 将`config-sample.php`的内容复制，新建文件`config.php`，将复制的内容粘贴进去并保存。
   1. 所有的配置都在`config.php`
   2. `config.php`已经被添加进`.gitignore`
3. 设置`config.php`
   1. `BASE_URL`为存放index.php的目录，例如http://localhost/folding-at-SUSTech-server/src
   2. `LANGUAGE`为默认语言，其他无需设置
4. 访问 <BASE_URL>/index.php

# 其他配置
1. `php.ini`：将`extension=php_sqlite3.dll`和`extension=pdo_sqlite`取消注释

---

The server for [Folding At SUSTech](/docs/project1).

Document [link]

Github [link]
