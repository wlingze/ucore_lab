# readme 

ucore实验代码

[ucore实验:master](https://github.com/chyyuu/os_kernel_lab), [在线实验指导书](https://legacy.gitbook.com/book/chyyuu/ucore_os_docs). 

## labcode

* **lab1**

- [x] 练习
- [x] 拓展练习: 实现用户态内核态切换
- [x] 拓展练习: 用键盘实现用户模式内核模式切换

* **lab2**

- [x] 练习: 连续物理内存分配算法
- [x] 练习: 虚拟地址映射关系的建立和取消
- [ ] 拓展练习: buddy system分配算法
- [ ] 拓展练习: 任意大小内存单元slub分配算法

* **lab3**

- [x] 练习: `do_pdfault`函数和fifo页替换算法
- [ ] 拓展练习: 识别dirty bit的extended clock页替换算法
- [ ] 拓展练习: LRU页替换算法

* **lab4**

- [x] 练习: `alloc_proc`和`do_fork`函数
- [x] 理解: `proc_run`函数实现
- [ ] 拓展练习: 任意大小内存分配算法

* **lab5**

- [x] 练习: 加载程序并执行
- [x] 练习: 父子进程内存复制
- [x] 理解: 分析理解系统调用和进程控制相关实现
- [ ] 拓展练习: 实现copy on write

* **lab6**

- [x] 练习: 使用 Round Robin 调度算法
- [x] 练习: 实现 Stride Scheduling 调度算法
- [ ] 扩展练习：实现 Linux 的 CFS 调度算法
- [ ] 扩展练习：在ucore上实现尽可能多的各种基本调度算法
