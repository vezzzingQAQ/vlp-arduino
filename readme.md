## Arduino学习笔记

vlp-arduino

_code is art that does something_

### 项目

起止时间：大四下-:

BLOG形式的笔记

### 技术栈

arduino c++ c

### 参考链接

* https://space.bilibili.com/103589285

* http://www.taichi-maker.com/

* http://www.taichi-maker.com/homepage/reference-index/arduino-code-reference/

### 笔记

#### 基础知识

* [基本硬件](./notes/基础知识/基本硬件.md)

* [程序基础](./notes/基础知识/程序基础.md)

* [常用函数](./notes/基础知识/常用函数.md)

* [LED](./notes/基础知识/LED.md)

* [按键开关](./notes/基础知识/按键开关.md)
    
    * 上拉电阻

* [读取按键开关数据](./notes/基础知识/读取按键开关数据.md)

    * digitalRead()

* [随机数字装置](./notes/基础知识/随机数字装置.md)

    * LED数码管

* [模拟输出1-analogWrite](./notes/基础知识/analogWrite.md)

* [模拟输出2-PWM](./notes/基础知识/PWM.md)

* [analogRead](./notes/基础知识/analogRead.md)

#### MeArm机械臂

* [整体介绍](./notes/机械臂/整体架构.md)

* [舵机](./notes/机械臂/舵机.md)

    * Servo.h

    * servo.attach()

    * serv.write()

* [串口通信](./notes/机械臂/串口通讯.md)

    * Serial.available()

    * Serial.read()

* [用串口控制舵机](./notes/机械臂/用串口控制舵机.md)

    * 电源模块

* [控制四个舵机](./notes/机械臂/控制四个伺服电机.md)

    * switch语句

* [一维数组](./notes/机械臂/一维数组.md)

* [二维数组](./notes/机械臂/二维数组.md)

* [机械臂搭建](./notes/机械臂/机械臂搭建.md)

* [调试机械臂](./notes/机械臂/调试机械臂.md)

* [控制机械臂速度](./notes/机械臂/控制机械臂速度.md)

    * servo.read()

* [机械臂程序-限位&状态输出](./notes/机械臂/程序1.md)

* [机械臂程序-执行一连串动作](./notes/机械臂/程序2.md)

* [HC06蓝牙通信模块1](./notes/机械臂/HC06蓝牙模块1.md)

    * 通过RxTx引脚通信

* [HC06蓝牙通信模块2](./notes/机械臂/HC06蓝牙模块2.md)

    * 通过软件串口通信

#### 智能应用

##### 传感器

* [光敏电阻](./notes/智能应用/光敏电阻.md)

* [红外人体感应模块](./notes/智能应用/红外人体感应模块.md)

##### RGBLED

* [RGBLED](./notes/智能应用/RGBLED.md)

##### arduino内存

* [arduino内存](./notes/智能应用/arduino内存.md)

* [EEPROM](./notes/智能应用/EEPROM.md)

* [内存优化](./notes/智能应用/优化内存使用.md)

* [安装第三方库](./notes/智能应用/安装第三方库.md)

##### 红外遥控

* [红外遥控器-基本原理](./notes/智能应用/红外遥控.md)

* [红外遥控-信号接收](./notes/智能应用/红外遥控信号接收.md)

    * IRremote库

* [红外遥控-信号发射](./notes/智能应用/红外遥控信号发送.md)

* [万能遥控器](./notes/智能应用/万能遥控器.md)

##### WS2812&FastLED

* [WS2812灯带](./notes/智能应用/WS2812.md)

* [arduino控制WS2812](./notes/智能应用/使用arduino控制WS2812.md)

    * arduino供电方法

* [FastLED库](./notes/智能应用/FastLED.md)

#### 电机

* [原理和分类](./notes/电机/电机的基本结构和原理.md)

##### 直流有刷电机

* [控制直流有刷电机](./notes/电机/控制有刷直流电机.md)

    * H桥电路

* [arduino通过控制板控制电机](./notes/电机/arduino驱动直流电机.md)

##### 步进电机

* [步进电机原理](./notes/电机/步进电机原理.md)

* [控制步进电机-基本使用](./notes/电机/arduino控制42步进电机.md)

    * A4988控制模块

    * NEMA42步进电机

* [控制步进电机-综合使用](./notes/电机/arduino控制42步进电机2.md)

* [控制28YBJ-48步进电机](./notes/电机/arduino控制28BYJ-48步进电机.md)

    * Stepper库

* [AccelStepper库](./notes/电机/AccelStepper.md)