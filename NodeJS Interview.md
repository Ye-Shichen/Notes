# NodeJS Interview Note

> 阅读饿厂NodeJS Interview的一些笔记




## 2018/8/2

**NET**

- 抓包工具看[《Wireshark网络分析就这么简单》](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B00PB5QQ84/)

- 粘包？？ 

- TCP延迟传送算法：Nagle算法

  > 多数据同时发送，会缓冲到一起，缓冲大小见socket.bufferSize
  >
  > 粘包解决方案3个

- 可靠传输

  - 关于具体的序号计算, 丢包时的重传机制等可以参见阅读的 [《TCP的那些事儿（上）》](http://coolshell.cn/articles/11564.html) 
  - TCP 头里有一个 Window 字段, 是接收端告诉发送端自己还有多少缓冲区可以接收数据的. 发送端就可以根据接收端的处理能力来发送数据, 从而避免接收端处理不过来. 详细参见陈皓的 [《TCP的那些事儿（下）》](http://coolshell.cn/articles/11609.html) 





## **2018/8/1**

- Buffer?

  > 二进制缓存，用于将文件所有内容一次性读取，然后进行操作（发送等操作）
  >
  > 缺点是占内存

- [《你不知道的JavaScirpt》](https://book.douban.com/subject/26351021/)阅读

- TypeScript: JS的超集，类型注解

  Flow：也是对JS的类型做注释的语言

- 指针和引用的区别

  >普通变量、指针变量、引用变量
  >
  >`int a = 1, //&a==a的地址，引用即取值运算符 ` 
  >
  >`int* p = &a; // 定义一个'指针变量'p，先是个变量，后是个指针进行取值`
  >
  >`int& b = a //表示引用a的地址，可以理解为定义别名的运算符`

- Redis缓存数据库，大概是用于热更新?
