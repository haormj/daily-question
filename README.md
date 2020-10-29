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

