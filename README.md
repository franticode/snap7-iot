## Based
source code from [snap7_v1.4.2](http://snap7.sourceforge.net/)

## Build
```
cd build/unix
make -f mips_linux.mk all
```

## Clean
```
cd build/unix
make -f mips_linux.mk clean
```

## Output libs
```
bin/mips-linux/libsnap7.so
```

## Support
nap7 是一个基于以太网与S7系列的西门子PLC通讯的开源库。

支持包括S7系列的S7-200、S7-200 Smart、S7-300、S7-400、S7-1200以及S7-1500的以太网通信。


## Original Summary
Snap7, through three specialized components: Client and the inedited Server and Partner, allows you to definitively integrate your PC based systems into a PLC automation chain.

Designed to transfer large amounts of hi-speed data in industrial facilities, it scales easily, down to small Linux Arm boards such as Raspberry PI.

Hi level object oriented wrappers are provided, currently C/C++, .NET/Mono, Pascal, LabVIEW, Python with many source code examples.

Very easy to use, a full working server example is not bigger than the “Hello world”.

Many projects/makefiles are ready to run to easily rebuild Snap7 in any platform without the need of be a C++ guru.

Very detailed documentation provided.

## Original Features
* Native multi-architecture design (32/64 bit).
* Runtime endian-aware architecture (no compiler switch needed)
* Three different native thread models for performance optimization: Win32/Posix/Solaris
* Two data transfer models: classic synchronous and asynchronous.
* Two data flow models: polling and unsolicited (PLC transfers data when it wants to).
* No dependence on any third-party libraries, no installation needed, zero configuration.
* Supported : S7 300/400/1200/1500/WinAC, LOGO 0BA7/0BA8, S7200, SINAMICS
* Set/Clear password functions to full access to protected PLC

