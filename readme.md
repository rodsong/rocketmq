
1. 附件是一个rocketmq + spring集成的代码片段

2. 一个应用创建一个Producer，由spring负责生成单例对象，并且负责启动。
   Producer对象可以发送多个topic，多个tag的消息。