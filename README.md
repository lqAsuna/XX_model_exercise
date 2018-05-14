# XX 建模练习 
## 要求：
- 练习文档编写
    - 选择一个你喜欢的 移动App 或 其中某业务
    - 参考 Asg_RH 文档格式 编写软件描述
    - 文档要包含一个业务的完整过程
    - 建模要求包括（用例图、XX业务或用例的活动图、XX领域模型、XX对象的状态图、XX场景的系统顺序图与操作协议）
- 建模者答案：
    - 收集建模者答案URL
    - 建模者不能是本团队成员（至少有一个答案）
    - 给建模者给出评价与建议
## 建模题目：[传送门](https://github.com/Owl-Movies-Ticket-System/Dashboard/blob/gh-pages/XX1-Forest%E5%BA%94%E7%94%A8.pdf)

### 用例图：

![image](https://github.com/lqAsuna/XX_model_exercise/blob/master/image/result1.png)

### 活动图：

![image](https://github.com/lqAsuna/XX_model_exercise/blob/master/image/result2.png)

### 状态图：

![image](https://github.com/lqAsuna/XX_model_exercise/blob/master/image/result3.png)

### 领域模型图：

![image](https://github.com/lqAsuna/XX_model_exercise/blob/master/image/result4.png)

### 系统顺序图：

![image](https://github.com/lqAsuna/XX_model_exercise/blob/master/image/result5.png)

### 操作协议

- 操作：请求开始
    - 前置条件：有完整的一个树的实例以及一个可用的计数器实例
    - 后置条件：计时器开始计数，检查是否坚持的系统打开

- 操作：设置树类型
    - 前置条件：该种类已经被解锁
    - 后置条件：创建一个树的实例，类型设置为选择的类型

- 操作：设置时间
    - 前置条件：完成树的类型设置
    - 后置条件：将该时间加入计时器中，设置为计时器的上限
