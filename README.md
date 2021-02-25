# UEFI-Tutorial

基于 UEFI 开发操作系统的相关指引。本教程将会着重叙述在 UEFI 引导的情况下，操作系统开发中的特殊内容，如 GOP 显存、APIC 中断控制以及长模式指令架构。本教程不能够作为完整的操作系统实验教学指引，而是应该作为一种碎片化的知识补充材料。

本指引基于 x86_64 指令集。其中，初等的内容将同时提供 C++ 和 Rust 语言的版本，而较为深入的内容视时间情况，可能只提供 Rust 语言的版本。实验基于 \*nix 环境。

## 计划

以下计划仅供参考，其中的顺序可能发生调整。

- [ ] [利用 UEFI 引导启动计算机](https://github.com/xfoxfu/UEFI-Tutorial/blob/master/1-Basic-Application.md)
- [ ] UEFI 加载 ELF 格式的可执行文件
- [ ] MMIO、APIC 中断控制器和键盘输入
- [ ] FAT16E 分区表结构
- [ ] 长模式分页内存体系和可执行文件加载
- [ ] 系统调用
- [ ] 对称多处理

## License

[![知识共享许可协议](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

本作品采用[知识共享署名-相同方式共享 4.0 国际许可协议](http://creativecommons.org/licenses/by-sa/4.0/)进行许可。
