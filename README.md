# Intelligent-classification-of-household-waste
项目介绍：

  随着城市化进程的发展和人民生活水平的提高,城市垃圾的产量迅速增长,成分也更加复杂,如何使城市垃圾的收集,运输和处理做到合理化,无害化和资源化,是搞好城市环境卫生,提高人居环境的关键。其次，在我们的身边，垃圾堆放现象屡见不鲜，不仅影响城市形象，也会产生一系列对人体有害的物质。因此分类收集是实现垃圾无害化,资源化,减量化一个十分重要的环节,是解决城市垃圾的有效途径,是今后环卫工作的一个重点。同时也能帮助相关清洁人员有效地分类垃圾，提高工作效率，节省劳动力成本，为充分践行智慧城市的发展理念，合理有效利用环卫资源。

关键词：垃圾分类；自主投放；神经网络

本项目参加 2023年中国大学生工程实践与创新能力大赛 获得奖项：国家级金奖

本代码采用正点原子STM32F407ZGT6核心版，具体思路如下

![image](https://github.com/2435332909/Intelligent-classification-of-household-waste/assets/115623395/d203138e-3402-43c6-a53a-43cfcc7c8692)

主控相关接口说明如下：

![image](https://github.com/2435332909/Intelligent-classification-of-household-waste/assets/115623395/8c88e16d-518a-43b3-8834-7e17e800fe5a)


三路PWM舵机 F8 A3 C8       F8(5V供电)  其余8V供电   线序（地 电 IO）

一路传送带继电器  G6 3.3 GND(三根线)

步进电机传送带 A1 3v3(两根线)

光栅检测 C5  三根线线序(GND 3.3V IO)

NX串口通信 板载USB

推杆压缩电机  C6 C7 5V GND（四根线）

预留舵机 F7  8V供电

预留一路串口  TX：B10  RX：B11
