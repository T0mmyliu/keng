### 坑1:gmock学习
#### 原理
> This means EXPECT_CALL() should be read as expecting that a call will occur in the future, not that a call has occurred. Why does Google Mock work like that? Well, specifying the expectation beforehand allows Google Mock to report a violation as soon as it arises, when the context (stack trace, etc) is still available. This makes debugging much easier.

#### 实践

### 坑2:futex/各种锁学习
> ywl大佬说futex值得学一学
