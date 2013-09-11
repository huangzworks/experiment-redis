实验用 Redis 
===================

此项目用于存放一些对 Redis 的实验性修改。

以下是各个分支的用途，
对分支的修改说明请看\ `文档 <https://github.com/huangz1990/experiment-redis/wiki>`_\ ：

- ``unstable`` ：无修改，仅用于合并上游代码。

- ``2013.9.9-dbnum`` ：添加 ``DBNUM`` 命令，该命令可以返回客户端当前所使用数据库的号码。

- ``2013.9.12-zismember`` ：添加 ``ZISMEMBER`` 命令，用于检查一个给定成员是否存在于有序集合中。
