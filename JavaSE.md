---
date: 2024-03-23
tags:
  - Java基础语法
---
# 1.1 JDK JRE JVM
- JDK：英文全称 Java Development Kit，是Java的开发工具包 JDK是提供给Java开发人员使用的，其中包含了Java的开发工具和JRE。其中的开发工具包括：编译工具（javac.exe）打包工具（jar.exe）等。通俗的说就是开发用的。
- JRE：英文全称 Java Runtime Environment，是Java运行环境 JRE包括Java虚拟机 (JVM Java Virtual Machine)和Java程序所需的核心类库等，如果想要运行一个开发好的Java程序，计算机中只需要安装JRE即可。通俗的说就是运行用的。
- JVM：英文全称 Java Virtual Machine），是java虚拟机。 它只认识.class为后缀的文件，它能将class文件中的字节码指令进行识别并调用操作系统向上的API完成动作。JVM是java能够跨平台的核心机制。通俗的说就是跨平台用的，就是把我们写的代码，转换成class文件用的。
# 1.2 字面量 变量 常量
```Java
	int a; //变量
	const int b = 10; //b为常量，10为字面量
	string str = “hello world！”; // str 为变量，hello world！为字面量
```
- 字面量（literal）：是用于表达源代码中一个固定值的表示法（notation）
- 变量：有些数据在程序运行中可以变化或者被赋值，这称为变量。
- 常量：有些数据可以在程序使用之前预先设定并在整个运行过程中没有变化，这称为常量。
