# C-Skills-C-
STM32；cubeide；C；C语言

## /**********************************************Skill 1 Start**********************************************/
    中文：
    /* 代码部分 */
    ```C
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
    
    Engilsh:
    /* Code part */
    uint16_t pData[2];
    pData[0] = 0x1234;
    pData[1] = __REV16(0x1234); // Swap the high and low 8 bits of a 16-bit number.
    
    /* Register result part */
    pData[0] = 0x1234;
    pData[1] = 0x3412;
    
    /* Explanation section */
    __REV16 is a macro defined in CMSIS (Cortex Microcontroller Software Interface Standard) to invert a 16-bit byte order on an ARM Cortex-M processor.
    Library file: cmsis_gc.h
## /**********************************************Skill 1 End**********************************************/
