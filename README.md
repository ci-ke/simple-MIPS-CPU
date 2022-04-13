# simple-MIPS-CPU

《数字设计和计算机体系结构（原书第2版）》第7章的实现。

使用的逻辑电路仿真软件为[Digital](https://github.com/hneemann/Digital)。

处理器的体系结构为MIPS的一个子集，分别实现了三种不同的微体系结构：单周期、多周期和五级流水线。

支持的指令有：
* R型算术/逻辑指令：add, sub, and, or, slt。
* 存储器指令： lw, sw。
* 分支指令：beq。
* 立即数加法：addi。
* 跳转指令：j。

图片效果：

单周期结构：
![SingleCycleCPU](https://github.com/ci-ke/simple-MIPS-CPU/blob/master/images/SingleCycleProcessor.png)

多周期结构：
![MultiCycleCPU](https://github.com/ci-ke/simple-MIPS-CPU/blob/master/images/MultiCycleProcessor.png)

流水线结构：
![PipelinedCPU](https://github.com/ci-ke/simple-MIPS-CPU/blob/master/images/PipelinedProcessor.png)
