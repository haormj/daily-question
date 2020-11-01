## 每日一问

1. 数据库为什么需要索引？
    - 建立索引的目的是加快对表中记录的查找或排序
    - 参考[数据库索引](https://baike.baidu.com/item/%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B4%A2%E5%BC%95#:~:text=%E7%B4%A2%E5%BC%95%E6%98%AF%E5%AF%B9%E6%95%B0%E6%8D%AE%E5%BA%93%E8%A1%A8,ID%E7%9A%84%E8%BE%85%E5%8A%A9%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E3%80%82)
2. mysql有哪些数据库索引？
    - PRIMARY KEY 主键索引
    - UNIQUE 唯一索引
    - INDEX 普通索引
    - FULLTEXT 文本索引
3. mysql索引是如何实现的？
    - 大多数mysql索引都通过B树来实现（部分数据类型使用R树），内存表支持哈希索引，InnoDB FULLTEXT 索引使用反向列表实现
    - 参考[8.3.1 How MySQL Uses Indexes](https://dev.mysql.com/doc/refman/5.7/en/mysql-indexes.html)
4. mysql支持哪些存储引擎？
    - InnoDB
    - MyISAM
    - Memory
    - CSV
    - Archive
    - Blackhole
    - NDB
    - Merge
    - Federated
    - 参考[MySQL 5.7 Supported Storage Engines](https://dev.mysql.com/doc/refman/5.7/en/storage-engines.html)
5. mysql存储引擎的区别是什么？
    - MyISAM,Memory 表级锁
    - InnoDB，NDB 行级锁
    - 存储数据量 NDB > MyISAM > InnoDB
    - [Table 15.1 Storage Engines Feature Summary](https://dev.mysql.com/doc/refman/5.7/en/storage-engines.html)
6. 为什么mysql索引要使用b树？
    
7. 什么是虚幻引擎？
    - 虚幻引擎（英语：Unreal Engine）是一款由Epic Games开发的游戏引擎
    - 参考[虚幻引擎](https://zh.wikipedia.org/wiki/%E8%99%9A%E5%B9%BB%E5%BC%95%E6%93%8E)
8. B树、R树数据结构有哪些特性？

