# CYW955513EVK-01 BSP Release Notes
The Infineon AIROC™ Wi-Fi & Bluetooth® combo evaluation kit (CYW955513EVK-01) enables evaluation, prototyping, and development of a wide array of IoT applications using the AIROC™ CYW55513, a low power and high performance combo chip. 

NOTE: BSPs are versioned by family. This means that version 1.2.0 of any BSP in a family (eg: PSoC™ 6) will have the same software maturity level. However, not all updates are necessarily applicable for each BSP in the family so not all version numbers will exist for each board. Additionally, new BSPs may not start at version 1.0.0. In the event of adding a common feature across all BSPs, the libraries are assigned the same version number. For example if BSP_A is at v1.3.0 and BSP_B is at v1.2.0, the event will trigger a version update to v1.4.0 for both BSP_A and BSP_B. This allows the common feature to be tracked in a consistent way.

### What's Included?
The CYW955513EVK-01 library includes the following:
* BSP specific makefile to configure the build process for the board
* cybsp.c/h files to initialize the board and any system peripherals
* cybsp_types.h file describing basic board setup
* Configurator design files (and generated code) to setup board specific peripherals
* API documentation

### What Changed?
#### v1.0.0
* Initial release.

### Supported Software and Tools
This version of the CYW955513EVK-01 BSP was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox™ Software Environment        | 3.1.0   |
| GCC Compiler                              | 11.3.1  |
| ARM Compiler                              | 6.16    |

Minimum required ModusToolbox™ Software Environment: v3.1.0

### More information
* [CYW955513EVK-01 BSP API Reference Manual][api]
* [CYW955513EVK-01 Documentation](http://www.infineon.com/CYW955513EVK-01)
* [Cypress Semiconductor, an Infineon Technologies Company](http://www.cypress.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.cypress.com/products/modustoolbox-software-environment)

[api]: https://infineon.github.io/TARGET_CYW955513EVK-01/html/modules.html

---
© Cypress Semiconductor Corporation (an Infineon company) or an affiliate of Cypress Semiconductor Corporation, 2019-2022.