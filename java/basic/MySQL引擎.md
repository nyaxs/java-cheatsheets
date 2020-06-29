## MySQL相关
- MySQL执行过程
    - 
### 引擎
   1.  引擎类型
        - MySQL命令查询提供的所有引擎：
            > mysql> show engines;  
            >
           5.7版本所有的存储引擎中只有InnoDB支持事务
        - 查看MySQL当前默认的存储引擎
            > mysql> show variables like '%storage_engine%';
            >
        - 查看表的存储引擎 
           > mysql> show variables like '%storage_engine%';
           >
- 行级锁，表级锁
- 
- 批量插入、更新
    - 单条循环插入
    - 合并插入 ， 要注意数据大小
