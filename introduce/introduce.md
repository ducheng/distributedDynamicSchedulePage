# 1,为什么要基于nacos分布式动态定时任务

## 1.1 在日常的开发过程中，我们有一些应用场景是使用定时任务的。 但是定时任务又是经常改变的。 或者说运行一段时间就要停止。并且就是一个很小的功能，也没必要上xxl-job,elastic-job。增加工作量，然后引入新的中间件，还需要开发任务

## 1.2 官方不支持，自己看了大量的资料基于springboot2.5 版本搞了出来。