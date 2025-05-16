📦 ELF 是什么？
ELF 全称：Executable and Linkable Format

是 Linux 下的可执行文件格式

常见扩展名：无（如 a.out）、.o、.so、.elf

它是二进制结构，可能包含以下部分：

部分	功能说明
.text	程序的机器码（函数体）
.data	静态变量
.bss	未初始化全局变量
.debug_info	调试信息（函数名、行号、变量名等）
.symtab	符号表（记录函数/变量名和地址）

