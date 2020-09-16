
## 并发

### 1. select_test
```text
多路选择 和 超时
```

### 2. channel_close_test
```text
channel 的关闭 和 广播
```

### 3. cancel_by_close_test
```text
通过 channel 取消任务
``` 

### 4. cancel_by_context_close_test
```text
通过 context 取消任务
```

### 5. once_test
```
适用 sync包中的 once 实现单例、只运行一次
```

### 6. first_response_test
```text
任意一个任务完成、就结束
```

### 7. all_response_test
```text
所有任务完成、才会结束
```

### 8. obj_pool & obj_pool_test
```text
对象池: 利用channel 和  select  和 time.After 实现
```

### 9. sync_pool_test
```text
使用 sync.pool 来实现对象缓存
```
