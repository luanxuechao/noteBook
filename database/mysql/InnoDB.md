## InnoDB记录存储结构
### InnoDB 简介
InnoDb将数据划为若干个页，以页作为次盼盼和内存之间的交互的基本单位，InnoDB中的页的大小一般为16kb。也就是在一般情况下，一次最少从磁盘中读取16KB的内容到内存中，一次最少把内存中的16KB内容刷新到磁盘中。

### InnoDB行格式
#### 分类
   - Compact
   - Redundant
   - Dynamic
   - Compressed


