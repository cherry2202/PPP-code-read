## PPP 源码阅读 & 分析
### 一、项目计划  

### 第一阶段：理论学习和环境搭建（1-2天）

**第1天：**
- **上午：** 阅读PPP协议的基本概念和工作原理，包括LCP、NCP、PAP、CHAP等。
- **下午：** 下载PPP源码，熟悉源码结构，安装必要的开发工具和环境。

**第2天：**
- **上午：** 搭建PPPoE客户端和服务器的实验环境。
  - 在Windows XP或7上安装PPPoE客户端软件并配置网络连接。
  - 在Ubuntu或CentOS 7上安装PPPoE服务器软件并配置服务。
- **下午：** 测试PPPoE连接，确保客户端和服务器能够成功建立连接。

### 第二阶段：代码静态分析（3-5天）

**第3天：**
- **上午：** 分析PPP模块组成、数据结构和事件处理机制。
- **下午：** 阅读源码，了解PPP的工作状态和状态机。

**第4天：**
- **上午：** 研究PAP和CHAP的底层功能和协议，分析它们的工作流程。
- **下午：** 阅读源码，了解PPP帧的封装过程，特别是LCP和NCP配置协商过程中的PPP帧。

**第5天：**
- **上午：** 分析PPP异步传输时的字节填充代码实现。
- **下午：** 研究PPP与内核驱动代码的关系，了解PPP驱动如何与内核交互。

### 第三阶段：动态调试分析（2-3天）

**第6天：**
- **上午：** 学习如何使用调试工具（如gdb）进行动态调试。
- **下午：** 调试PPP网络接口，了解数据如何通过网络接口发送和接收。

**第7天：**
- **上午：** 分析PPP帧的分片机制，特别是字节填充对PPP帧分片的影响。
- **下午：** 准备加分大作业的研究方向和计划。

### 第四阶段：实验和报告撰写（2-3天）

**第8天：**
- **全天：** 进行实验，记录实验结果，包括PPP帧的封装、拆封、认证过程等。

**第9天：**
- **上午：** 根据实验结果撰写报告，总结PPP协议的实现和优化建议。
- **下午：** 准备报告的演示材料，如PPT或其他视觉辅助工具。

**第10天：**
- **全天：** 复习报告内容，准备答辩或展示。

