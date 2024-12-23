# 基于51单片机的智能鱼缸设计

## 项目简介

本项目基于51单片机设计了一款智能鱼缸控制系统，采用STC12C5A60S2作为核心控制器。该系统集成了温度检测、恒温控制、步进电机控制、继电器控制、矩阵键盘设计等功能，旨在实现对鱼缸环境的智能化管理。

## 项目特点

- **核心控制器**：采用STC12C5A60S2，最新款国产51单片机。
- **功能模块**：
  - **温度检测**：通过DS18B20温度传感器实时监测鱼缸内的温度。
  - **恒温控制**：当温度低于设定阈值时，系统自动启动加热电路，并通过蜂鸣器和指示灯进行报警。
  - **光照控制**：通过DH1750光强传感器监测环境亮度，低于阈值时自动开启照明，也可通过按键手动控制。
  - **自动投喂**：通过按键设置步进电机的工作时间，实现定时自动投喂。
  - **水位控制**：通过继电器控制阀门，实现自动进水和出水。
- **显示模块**：采用OLED液晶显示器实时显示系统状态。
- **供电方式**：系统采用USB 5V供电。

## 资源内容

- **原理图**：详细的设计原理图，帮助理解系统结构。
- **程序代码**：完整的单片机程序代码，可直接下载使用。
- **原文文档**：详细的设计说明文档，包含系统设计思路、硬件选型、软件设计等内容。
- **实物代做**：提供实物制作服务，可根据需求定制。

## 使用说明

1. **硬件连接**：按照原理图连接各模块。
2. **程序烧录**：将程序代码烧录到STC12C5A60S2单片机中。
3. **系统启动**：通过USB 5V供电，系统上电后自动启动。
4. **功能设置**：通过矩阵键盘设置温度阈值、光照阈值、投喂时间等参数。
5. **状态监控**：通过OLED液晶显示器实时监控系统状态。

## 注意事项

- 请确保硬件连接正确，避免短路或接错线。
- 在烧录程序时，请确保单片机型号与程序匹配。
- 使用过程中，请定期检查传感器和执行机构的工作状态，确保系统正常运行。

## 联系我们

如有任何问题或需求，请联系我们进行咨询或定制服务。

## 下载链接

[基于51单片机的智能鱼缸设计](https://pan.quark.cn/s/9a8fd4de36d8)