1、RabbitMQ 中的 broker 是指什么？cluster 又是指什么？ 

---

2、什么是元数据？元数据分为哪些类型？包括哪些内容？与 cluster 相关的元数据有哪些？元数据是如何保存的？元数据在 cluster 中是如何分布的？ 

---

3、RAM node 和 disk node 的区别？ 

---

4、RabbitMQ 上的一个 queue 中存放的 message 是否有数量限制？ 

---

5、RabbitMQ 概念里的 channel、exchange 和 queue 这些东东是逻辑概念，还是对应着进程实体？这些东东分别起什么作用？ 

---

6、vhost 是什么？起什么作用？  

---

7、在单 node 系统和多 node 构成的 cluster 系统中声明 queue、exchange ，以及进行 binding 会有什么不同？  

---

8、客户端连接到 cluster 中的任意 node 上是否都能正常工作？ 

---

9、若 cluster 中拥有某个 queue 的 owner node 失效了，且该 queue 被声明具有 durable 属性，是否能够成功从其他 node 上重新声明该 queue ？ 

---

10、cluster 中 node 的失效会对 consumer 产生什么影响？若是在 cluster 中创建了 mirrored queue ，这时 node 失效会对 consumer 产生什么影响？ 

---

11、能够在地理上分开的不同数据中心使用 RabbitMQ cluster 么？ 

---

12、为什么 heavy RPC 的使用场景下不建议采用 disk node ？ 

---

13、向不存在的 exchange 发 publish 消息会发生什么？向不存在的 queue 执行 consume 动作会发生什么？ 

---

14、routing_key 和 binding_key 的最大长度是多少？ 

---

15、RabbitMQ 允许发送的 message 最大可达多大？ 

---

16、什么情况下 producer 不主动创建 queue 是安全的？ 

---

17、“dead letter”queue 的用途？ 

---

18、为什么说保证 message 被可靠持久化的条件是 queue 和 exchange 具有 durable 属性，同时 message 具有 persistent 属性才行？ 

---

19、什么情况下会出现 blackholed 问题？ 

---

20、如何防止出现 blackholed 问题？ 

---

21、Consumer Cancellation Notification 机制用于什么场景？ 

---

22、Basic.Reject 的用法是什么？ 

---

23、为什么不应该对所有的 message 都使用持久化机制？ 

---

24、RabbitMQ 中的 cluster、mirrored queue，以及 warrens 机制分别用于解决什么问题？存在哪些问题？ 

---

25、为什么要使用mq队列，有什么用？

---

26、mq队列有哪些？它们的区别是什么？

---

27、mq如何保证数据不丢失？

---

28、mq如何保证幂等性？

---

29、mq如何实现高可用？

---

30、Kafka、ActiveMQ、RabbitMQ、RocketMQ 都有什么区别，以及适合哪些场景？