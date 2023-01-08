﻿# [HT7036](https://www.hitrendtech.com)


## HT7132/HT7136

HT7132系列多功能高精度三相电能专用计量芯片，适用于三相三线和三相四线应用。HT7132集成了多路二阶sigma-delta ADC、参考电压电路以及所有功率、能量、有效值、功率因数及频率测量的数字信号 处理等电路，能够测量各相以及合相的有功功率、无功功率、视在功率、有功能量及无功能量，同时还能 测量各相电流、电压有效值、功率因数、相角、频率等参数，充分满足三相复费率多功能电能表的需求。

HT7132支持全数字域的增益、相位校正，即纯软件校表。有功、无功电能脉冲输出 CF1、CF2提供瞬时有功、无功功率信息，可直接接到标准表，进行误差校正。
HT7132提供两类视在功率、能量计量方式：RMS视在方式和PQS视在方式；HT7132通过CF3输出视在能量脉冲，可接到标准表进行视在能量误差校正。
HT7132/提供基波参数计量：基波有功功率、基波有功电能、基波电流、电压有效值；HT7132通过脉冲输出CF4提供瞬时基波有功功率信息，可直接用于基波的校正。
HT7132通过设置相关寄存器后，可以提供：基波无功功率、基波无功电能，通过脉冲输出CF2提供瞬时基波无功功率信息，可直接用于基波无功的校正。

HT7132提供两个SPI接口，包括一个普通 SPI口和一个高速接口HSDC，方便与外部MCU之间进行计量及校表参数的传递，SPI接口的具体规格参见SPI详细说明部分，所有计量参数及校表参数均可通过SPI接口读出。高速接口HSDC方便把采样数据高速传给外部MCU。

HT7132内置电压监测电路可以保证上电和断电时正常工作。

## HT7036/HT7038

ATT7022E/26E、HT7038/36系列多功能、高性能三相电能专用计量芯片，内部集成了高精度二阶Sigma-delta ADC、参考电压电路以及数字信号处理等电路，能够测量各相以及合相的有功功率、无功功率、视在功率、有功能量及无功能量，同时还能测量各相电流、电压有效值、功率因数、相角、频率等参数，由于所有参数都是内部算法电路直接进行运算的结果，从而充分保证了参数的精度与可靠性。该系列芯片为三相多功能计量提供了功能齐全、设计简单的应用解决方案，可充分满足三相复费率多功能电能表的设计需求。

ATT7022E提供7路计量ADC输入，支持掉零线计量，并可直接输出所有测量参数，支持全数字域的增益、相位校正，即纯软件校表，外围MCU只需要完成多功能电能表要的管理和通讯协议程序即可。它提供有功、无功、视在、基波计量功能，对应提供CF1/CF2/CF3/CF4脉冲输出，并都可直连到标准表，做误差校正。同时ATT7022E还能提供电流和电压的同步ADC数据，方便做谐波分析的应用。另外它还提供电能质量检测SAG/Peak功能，亦可用于闪变分析。

ATT7026E提供6路计量ADC输入，不提供基波功能，即仅提供CF1/CF2/CF3脉冲输出，无ADC同步数据缓存，不支持谐波分析，不支持闪变。

HT7038/36为ATT7022E的小封装型号，采用LQFP32，提供6路计量ADC输入，仅提供CF1/CF2脉冲输出。HT7038不提供视在、基波功能，无ADC同步数据缓存及谐波分析。


## 参考设计

[基于HT7036的三相电能计量模块](https://oshwhub.com/LoveYanElecDIY/ji-yuht7036-di-san-xiang-dian-neng-ji-liang-mu-kuai)

