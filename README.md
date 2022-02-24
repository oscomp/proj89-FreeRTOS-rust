# proj89-FreeRTOS-rust


### 项目描述
FreeRTOS是一个使用非常广泛的迷你实时操作系统内核。作为一个轻量级的操作系统，功能包括：任务管理、时间管理、信号量、消息队列、内存管理、记录功能、软件定时器、协程等，可基本满足较小系统的需要。FreeRTOS操作系统是完全免费的操作系统，具有源码公开、可移植、可裁减、调度策略灵活、各种信息资源丰富的特点，可以方便地移植到各种单片机上运行。

本项目以C-based的官方FreeRTOS为基础，拟采用Rust语言重新设计与实现它。Rust语言与C语言不同，其作为一门现代的系统编程语言，表达能力更强，语义更丰富，所以在用Rust语言参与本项目时，从某种角度上需要我们将一些规则和设计显式地"写"在代码中，这同时也促使了我们去思考。

当前项目实现源码和文档等：[Rewritten Free RTOS in RUST](https://github.com/OSH-2019/x-rust-freertos)

### 所属赛道
2022全国大学生操作系统比赛的“OS功能挑战”赛道

### 参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“20212国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

陈渝 
- github:  https://github.com/chyyuu
- email: yuchen@tsinghua.edu.cn

注：邀请 [Rewritten Free RTOS in RUST](https://github.com/OSH-2019/x-rust-freertos)的作者和其他感兴趣的专家作为导师

### 难度

简单~中等

### 特征
- 符合FreeRTOS对外的接口
- 使用 Rust 语言实现
- 至少支持RISCV平台
- 支持QEMU仿真和Kendryte K210（含MMU和S模式）

### 参考实现
- [Rewritten Free RTOS in RUST](https://github.com/OSH-2019/x-rust-freertos)

### License
- MIT license (LICENSE-MIT or [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)

## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题：从零开始
- 参考本项目也用Rust语言复现FreeRTOS的设计与实现

### 第二题：实现和扩展智能指针
- 比如Arc和Condvar

### 第三题：实现对各种上层应用的支持
- 通过常见的C库
- 支持常见应用程序
- 通过基本的测试用例

### 第四题：移植到各种开发板上
- Kendryte K210开发板
- D1哪吒开发板
- SIFIVE U540, U740开发板
- 其他ARM/x86 based 开发板
