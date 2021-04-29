#### Object类
- 有哪些方法
- 为什么要有hashCode方法
- 为什么重写equals方法的同时也需要重写hashCode方法
- clone方法 干嘛的？深拷贝还是浅拷贝?

#### 封装类
- integer a=128, integer b=128, int c=128, Integer d = new Integer(128) a 等于b 和 a等于c结果，为什么

#### String类
- 双等于 和 equals的区别
- 我在项目中新建一个类,java.lang.String，那项目中使用的是我定义的String类还是jdk提供的String类呢?
    - 项目中使用的还是jdk的String类，因为双亲委派
- String str = new String("str"); String s = "a" 分别创建了几个对象
- String stringbuilder stringbuffer 的区别

#### 集合类
- 有哪些线程安全的集合类
- concurrentHashMap是怎么实现线程安全的
- hashMap为什么是线程不安全的
- currentHashMap实现线程安全1.7和1.8的区别
- currentHashMap是怎么解决hash冲突的
- 为什么jdk1.8要把hashmap底层 链表超过8 变成红黑树

- List删除某个元素可以有哪些写法？list集合遍历删除的问题？
    - 1 普通for循环遍历删除，根据下标删除
    - 2 迭代器方式删除
    - 3 jdk8的stream流 filter过滤
    - foreach方法会发生 concurrentModificationException
    
#### 流处理
- Bio nio

#### 并发相关
- cas问题

#### JVM
- 类的初始化有哪些，class文件是如何加载到内存的
- 说一说JVM模型

#### 反射
- 动态代理的原理是什么


#### 线程池
- 线程池参数，每个参数详解
- 线程池参数设置策略



