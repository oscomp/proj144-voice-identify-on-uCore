# proj144-voice-identify-on-uCore
uCore操作系统中基于声纹识别的身份认证

### 项目描述

在包括一个C906的RISC-V和两个A7的ARM核的异构SoC开发板D1-Super上移植uCore或rCore教学操作系统，支持ARM核的启动；在ARM核上移植语音处理软件SoX，搭建语音处理引擎，支持基于声纹识别的身份认证。

### 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

向勇

* github [https://github.com/xyongcn](https://github.com/xyongcn)
* email [xyong@tsinghua.edu.cn](mailto:xyong@tsinghua.edu.cn)

### 难度

高

### 特征

* 语音处理
* 声纹识别
* ARM A7启动
* RISC-V

### License

* GPL3

### 预期目标

* 将CMSIS移植到D1-Super的ARM核上；
* 将语音处理软件SoX和声纹识别算法移植到ARM核上；
* 将uCore移植到D1-Super的RISC-V核上；
* 扩展uCore的启动过程，以启动两个ARM A7核；
* 实现ARM与RISC-V间核间中断IPI的MessageBox驱动；
* 在uCore中扩展基于声纹识别的身份认证功能；
