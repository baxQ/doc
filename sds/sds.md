## 表格存储

### 阿里云表格存储

```
表格存储会对表中的行按主键进行排序，合理设计主键可以让数据在分区上的分布更加均匀，从而能够充分利用表格存储水平扩展的特点
选取分区键的几个原则：
- 单个分区键值中的数据不宜过大，建议不超过10GB
- 一张表内，不同分区键值中的数据在逻辑上是独立的
- 访问压力不要集中在小范围连续的分区键值中
```