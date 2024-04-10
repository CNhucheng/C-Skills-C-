# C-Skills-C-
STM32；cubeide；C；C语言

## /**********************************************Tips 1 Start**********************************************/
### 中文：
```C
/* 代码部分 */
uint16_t pData[2];
pData[0] = 0x1234;
pData[1] = __REV16(0x1234);//将一个16位的数的高8位和低8位进行交换。
```
    
    /* 寄存器结果部分 */
    pData[0] = 0x1234;
    pData[1] = 0x3412;
    
    /* 解释部分 */
    __REV16 是CMSIS（Cortex Microcontroller Software Interface Standard）中定义的一个宏，用于在ARM Cortex-M处理器上反转一个16位数的字节序。
    库文件：cmsis_gcc.h
    
### Engilsh:
```C
/* Code part */
uint16_t pData[2];
pData[0] = 0x1234;
pData[1] = __REV16(0x1234); // Swap the high and low 8 bits of a 16-bit number.
```
    
    /* Register result part */
    pData[0] = 0x1234;
    pData[1] = 0x3412;
    
    /* Explanation section */
    __REV16 is a macro defined in CMSIS (Cortex Microcontroller Software Interface Standard) to invert a 16-bit byte order on an ARM Cortex-M processor.
    Library file: cmsis_gc.h
### 한국어：
### 日本語：
### Русский язык：
## /**********************************************Tips 1 End**********************************************/
***
## /**********************************************Tips 2 Start**********************************************/
    ASCII (American Standard Code for Information Interchange)：
    美国信息交换标准代码是基于拉丁字母的一套电脑编码系统，主要用于显示现代英语和其他西欧语言。
    可视化面板URL：https://grafana.com/zh-cn/grafana/?pg=graf&plcmt=hero-btn-1
## /**********************************************Tips 2 End**********************************************/
