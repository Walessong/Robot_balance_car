# :star:Robot_balance_car

## :loudspeaker:简介

这是我们**参加北航2025电子创新大赛**制作的项目，我们采用STM32作为主控，实现了一款可以在狭小空间内进行空气检测和火灾隐患巡查的平衡车。

*This is a project **participating in the 2025 Electronic Innovation Competition of Beihang University**. We used STM32 as the main control to realize a balancing car that can perform air detection and fire hazard inspection in a small space.*

:pushpin: <font color='gree'>我们制作了面向纯小白的复刻教程!</font>

## :sparkles: 功能特性

* STM32F10C8T6核心板
  
* 两轮平衡小车，手机蓝牙遥控
  
* ESP32CAM+WIFI图传
  
* OLED实时显示温湿度传感、烟雾浓度传感、遇火焰蜂鸣器报警
  
* 按键调节报警阈值
  

## 安装说明

### 1. 环境准备

软件

![613ca92817f64ae995a91c85f9a46a07](file:///C:/Users/wangsong/Pictures/Typedown/613ca928-17f6-4ae9-95a9-1c85f9a46a07.png?msec=1745896215722)![4b41f1f094e04b14bf8813c41abba92c](file:///C:/Users/wangsong/Pictures/Typedown/4b41f1f0-94e0-4b14-bf88-13c41abba92c.png?msec=1745896622322)![61630c06e5ea44938e18acda7b499073](file:///C:/Users/wangsong/Pictures/Typedown/61630c06-e5ea-4493-8e18-acda7b499073.png?msec=1745896700973)

##

开源这个项目要完成的任务

1. readme文件包含：
  

* 面向小白的复刻教程（这个我来搞）；
  
* 材料清单
  

* 找一些咱做的这个东西用到的技术的详细教学、讲解的视频或者文章的连接放在这里面，并给出自己（或AI）的理解和学习建议（比如pid算法简介、陀螺仪模块mpu6050的原理、超声波模块的原理、蓝牙模块的原理、温湿度传感器、编码器电机的介绍）
  
* <font color='red'> 涉及代码介绍的工作</font>
  
  * esp32cam wifi图传的代码解释（用arduino实现的，不用配置keil5环境就能打开和运行，可以你们来搞下）
    
  * 舵机控制代码解释（mht）
    
  * stm32工程文件里的(需要配置keil5)(参考B站教程和AI)
    
    ![66831b81c211433baf19a654dec18ef5](file:///C:/Users/wangsong/Pictures/Typedown/66831b81-c211-433b-af19-a654dec18ef5.png?msec=1745894601828)
    
    * 电机代码原理——motor.c
      
    * 调pid的代码原理——control.c
      

2. 代码 原理图 pcb等材料
  

直接放上去就行，无工作量。
