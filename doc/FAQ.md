1. 数据库遇到 `ER_TRUNCATED_WRONG_VALUE_FOR_FIELD` 问题

字符集问题，进入 MySQL 配置文件: my.ini。在 `[mysql]` 下新增 `default-character-set=gbk`，`[mysqld]` 下新增 `character-set-server=gbk`。然后重启数据库服务。