# hello
hello world

## 编译可执行文件:
		gcc hello.c
		gcc -o hello hello.c
## 预编译:
		gcc -E hello.c -o hello.i
## 生成汇编代码:
		gcc -S hello.i -o hello.s	
## 生成目标代码:
		gcc -c hello.s -o hello.o
## 链接为可执行文件:
		gcc hello.o -o hello
