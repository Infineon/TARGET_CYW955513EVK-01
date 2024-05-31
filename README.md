# CYW955513EVK-01 BSP

## Overview

The Infineon AIROC™ Wi-Fi & Bluetooth® combo evaluation kit (CYW955513EVK-01) enables evaluation, prototyping, and development of a wide array of IoT applications using the AIROC™ CYW55513, a low power and high performance combo chip. 

![](docs/html/board.png)

To use code from the BSP, simply include a reference to `cybsp.h`.

## Features

### Kit Features:

* Arduino compatible headers for hardware expansion.
* On-board sensors - A Digital Ambient Light Sensor (TSL25403) and a Potentiometer.
* Two IFX PDM Microphone (IM69D130) and one Analog Microphone (IM73A135).
* User switches and LEDs
* USB Type-C connector for power, programming, and USB-UART bridge

### Kit Contents:

* CYW55513 Evaluation Board (CYW9CPM2BASE1 + CYW955513SDCM2WILPA)
* Audio shield board(CYW9BTAUDIO5)
* M.2 to FFC adapter board
* 30-pin FFC cable 
* USB Type-C to Type-C cable
* Six jumper wires (5 inches each)
* Laird Triband PCB Antenna (2 Qty)
* Quick Start Guide

## BSP Configuration

The BSP has a few hooks that allow its behavior to be configured. Some of these items are enabled by default while others must be explicitly enabled. Items enabled by default are specified in the CYW955513EVK-01.mk file. The items that are enabled can be changed by creating a custom BSP or by editing the application makefile.

Components:
* Device specific category reference (e.g.: CAT1) - This component, enabled by default, pulls in any device specific code for this board.

Defines:
* CYBSP_WIFI_CAPABLE - This define, disabled by default, causes the BSP to initialize the interface to an onboard wireless chip if it has one.
* CY_USING_HAL - This define, enabled by default, specifies that the HAL is intended to be used by the application. This will cause the BSP to include the applicable header file and to initialize the system level drivers.
* CYBSP_CUSTOM_SYSCLK_PM_CALLBACK - This define, disabled by default, causes the BSP to skip registering its default SysClk Power Management callback, if any, and instead to invoke the application-defined function `cybsp_register_custom_sysclk_pm_callback` to register an application-specific callback.



See the [BSP Setttings][settings] for additional board specific configuration settings.

## API Reference Manual

The CYW955513EVK-01 Board Support Package provides a set of APIs to configure, initialize and use the board resources.

See the [BSP API Reference Manual][api] for the complete list of the provided interfaces.

## More information
* [CYW955513EVK-01 BSP API Reference Manual][api]
* [CYW955513EVK-01 Documentation](http://www.infineon.com/CYW955513EVK-01)
* [Cypress Semiconductor, an Infineon Technologies Company](http://www.cypress.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.cypress.com/products/modustoolbox-software-environment)

[api]: https://infineon.github.io/TARGET_CYW955513EVK-01/html/modules.html
[settings]: https://infineon.github.io/TARGET_CYW955513EVK-01/html/md_bsp_settings.html

---
© Cypress Semiconductor Corporation (an Infineon company) or an affiliate of Cypress Semiconductor Corporation, 2019-2022.