# 引言
//在现代操作系统中，都会有消息通讯机制。消息模型可以简化一些场景下的编程。

角色的代码只能控制角色自身。如果需要多个角色协同，就需要使用到“广播消息”。例如，有两个角色：小猫和小马。小猫对小马说“Hello”，小马需要在1秒后回答“Hello”。这就需要在小猫说完“Hello”后，广播一个消息给小马。小马角色收到广播消息后，说“Hello”。


# Scratch 中的消息机制

Scratch 内置了广播消息机制。在“控制”卡组中，有积木“广播消息 xxxx”和触发器积木“当收到消息 xxxx”。通过“广播消息”和“接收消息”，可以实现角色之间的消息通讯。角色也可以给自己发消息，通常这个用法配合多线程使用。

> * 触发器积木

## 程序制作：小猫和小马打招呼
### 程序目标
小猫和小马在路上相遇了，他们互相问好。
### 设计思路
