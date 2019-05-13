# Unit PaHUB {docsify-ignore-all}


<img src="assets/img/product_pics/unit/pahub/pahub_p1.jpg" width="30%" height="30%"><img src="assets/img/product_pics/unit/pahub/pahub_p3.jpg" width="30%" height="30%">



:memo:**[Description](#Description)**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:electric_plug:**[Schematic](#Schematic)**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🛒**[Purchase](https://www.aliexpress.com/store/product/New-Arrival-M5Stack-Official-I2C-Hub-1-to-6-Expansion-Grove-I2C-Interface-for-Arduino-Blockly/3226069_32998974179.html?spm=2114.12010615.8148356.1.2bf2a1134Jsams)**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:octocat:**[Code](#Code)**


## 描述

**PaHUB**, 是一款 I2C GROVE PORTA 扩展器.能够将单路 I2C GROBE 接口拓展至六路,并且允许挂载相同I2C地址的从设备.

内部集成**TCA9548A**-I2C多路复用器，配有8个可通过I2C总线控制的双向转换开关.串行时钟/串行数据（SCL /SDA）上行对可扩展为8个下行对或通道.根据可编程控制寄存器的内容，可选择任一单独SCn /SDn通道或者通道组合.

支持多层 Unit 嵌套，这意味着你可以将PaHUB连接到PaHUB上以获得更多的I2C从设备接口.（例：将7个Unit进行连接，将获得36个**I2C**接口，且在主控仅仅占用了一个GROVE端口）当你的项目需要挂载多个I2C设备或存在I2C地址冲突时，PaHUB Unit 是完美解决方案.

该 Unit 的 I2C 地址为0x77（可通过调整电阻进行更改）.

*注意：编程时请注意通道顺序*

<img src="assets/img/product_pics/unit/pahub/pahub_p2.jpg" width="30%" height="30%">



### 产品特性

- I2C GROVE PORTA 拓展
- 2x LEGO 兼容孔
- 允许多个嵌套
- 1-6 拓展

## 原理图

<img src="assets/img/product_pics/unit/pahub/pahub_sch.png">

### 套件清单

- 1x PaHUB Unit
- 1x Grove 线


## 参考文档

- 数据手册 - **[TCA9548A](http://www.ti.com/lit/ds/symlink/tca9548a.pdf)**


## Code

- 通讯类型 - I2C
- 地址 - 0x77