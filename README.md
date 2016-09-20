# IntoRobot Atom

IntoRobot Atom是一款小尺寸、双CPU设计、软硬件开源、代码完美兼容Arduino和STM32核心控制板.

采取STM32F103RBT6(主频：72MHz)和MT7620N(主频：580MHz)双CPU设计，不仅提供了丰富的接口（46个数字或模拟口，UARTs，SPI，I2C，PWM，CAN，USB，网口），还搭载了强大的OpenWrt系统（开源Linux系统，具备丰富的开源应用）。

Atom、IntoRobot App与IntoRobot云端服务形成一套完整的网络控制系统。

## 管脚描述:

- **D0-D24:** 具有输入输出的功能，其输出电流最大值能达到25mA。在输入模式时用户可以选择是否配置内部上拉或下拉电阻(通常等于40kohm)。
- **A0-A15:** 不但具有输入输出的功能还具有ADC功能，其AD的精度是12bit，测试的电压最大值是3.3V。
- **E0-E4:** 可以做为GPIO口使用同时也是MT7620N的JTAG脚。您可以通过JTAG接口用仿真器调试程序。一般情况下无需使用JTAG，因为您可以通过WEB端的在线编程调试程序。做GPIO使用只有输入输出功能，其操作与D0-D24相同，使用digitalWrite()和digitalRead()操作。
- **3V3:** 3.3v电压输出引脚。当通过VIN或者USB口供电点时候，该引脚输出3.3v电压。
- **5V:** 5v电压输出引脚。当通过VIN或者USB口供电点时候，该引脚输出4.8v电压（保护二极管分压）。
- **AREF:** 模拟输入参考电压。
- **VIN:** 核心板供电引脚。当核心板由USB口供电时，该引脚输出4.8v电压（保护二极管分压）。
- **GND:** 地
- **DP:** MTK7620N USB接口
- **DM:** MTK7620N USB接口
- **RP1:** MTK7620N 网络接口
- **TP1:** MTK7620N 网络接口
- **RN1:** MTK7620N 网络接口
- **TN1:** MTK7620N 网络接口
- **TRN:** MTK7620N JTAG接口
- **RST-S:** STM32复位引脚。
- **RST-N:** MTK7620N复位引脚。

Atom硬件详细功能。请访问：[Atom 硬件详解](http://docs.intorobot.com/hardware/atom/hardware)

更多功能，请访问：[www.intorobot.com](http://www.intorobot.com)

## 技术支持
技术支持邮箱:		support@intorobot.com

微信公众号:		intorobot

QQ交流群:		460095989


