# Embedded Systems Developer

I develop software that runs close to hardware, from STM32 firmware and
real-time applications to Embedded Linux systems.

I enjoy understanding how systems work internally, including interrupts,
task scheduling, device communication, and Linux device drivers.
I also like validating software behavior directly on real hardware.

## Tech Stack

### Languages

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Embedded Systems

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00979D?style=flat-square&logo=freertos&logoColor=white)
![Embedded Linux](https://img.shields.io/badge/Embedded_Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)

### GUI Frameworks

![WPF](https://img.shields.io/badge/WPF-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Qt 6](https://img.shields.io/badge/Qt_6-41CD52?style=flat-square&logo=qt&logoColor=white)
![LVGL](https://img.shields.io/badge/LVGL-2C82C9?style=flat-square&logo=lvgl&logoColor=white)
![MFC](https://img.shields.io/badge/MFC-5E5E5E?style=flat-square&logo=microsoft&logoColor=white)
![Win32 API](https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows11&logoColor=white)

### Libraries

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)

### Software Development Tools

![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-A42E2B?style=flat-square)
![STM32CubeMX](https://img.shields.io/badge/STM32CubeMX-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Make](https://img.shields.io/badge/Makefile-6D00CC?style=flat-square&logo=gnu&logoColor=white)
![Yocto](https://img.shields.io/badge/Yocto-000000?style=flat-square&logo=yocto&logoColor=white)
![Buildroot](https://img.shields.io/badge/Buildroot-222222?style=flat-square&logo=linux&logoColor=white)

### CAD & Hardware Design

![SolidWorks](https://img.shields.io/badge/SolidWorks-DA291C?style=flat-square&logo=dassaultsystemes&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![FreeCAD](https://img.shields.io/badge/FreeCAD-729FCF?style=flat-square&logo=freecad&logoColor=white)

### Development Boards

![NUCLEO-C562RE](https://img.shields.io/badge/NUCLEO--C562RE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![STM32F429I-DISC1](https://img.shields.io/badge/STM32F429I--DISC1-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi 3](https://img.shields.io/badge/Raspberry_Pi_3-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Raspberry Pi 4](https://img.shields.io/badge/Raspberry_Pi_4-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Raspberry Pi 5](https://img.shields.io/badge/Raspberry_Pi_5-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![ATmega128](https://img.shields.io/badge/ATmega128-EE1B2D?style=flat-square&logo=microchip&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![ESP32-C6](https://img.shields.io/badge/ESP32--C6-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Zybo Z7-10](https://img.shields.io/badge/Zybo_Z7--10-E01F27?style=flat-square&logo=amd&logoColor=white)
![Kria KV260](https://img.shields.io/badge/Kria_KV260-E01F27?style=flat-square&logo=amd&logoColor=white)
![BeagleBone](https://img.shields.io/badge/BeagleBone-FFCC00?style=flat-square&logo=beagleboard&logoColor=black)

## Projects

<details>
<summary><strong>🤖 Robotics Simulation</strong></summary>

#### • [Yertle Quadruped Robot](https://github.com/MainForm/yertle) · In Development

`Python` · `PyBullet` · `Gait Simulation`

> Currently developing on [`feature/gait-simulation`](https://github.com/MainForm/yertle/tree/feature/gait-simulation)

A fork-based quadruped robotics project currently focused on developing and
testing gait simulation in PyBullet before integration with physical hardware.

</details>

<details>
<summary><strong>🖥️ MPU Projects — ARM Cortex-A</strong></summary>

#### • [BaremetalOS](https://github.com/MainForm/BaremetalOS) · In Development

`ARMv8-A / ARMv7-A` · `C` · `Assembly` · `Make`

An operating system project for studying ARM architecture and low-level system
development. It currently targets the Raspberry Pi 4 in AArch64 mode and the
RealView-PB-A8 platform in AArch32 mode through QEMU, with support for PL011,
GIC-400, and SP804 peripherals.

#### • Linux Debugging with GDB

`Linux` · `GDB` · `JTAG` · `QEMU` · `U-Boot`

- **[Raspberry Pi 4 JTAG Debugging](https://github.com/MainForm/rpi4_debug_linux_with_JTAG_with_UBOOT)** — Debugging Linux on a physical Raspberry Pi 4 through JTAG, GDB, and U-Boot.
- **[Linux Debugging with QEMU](https://github.com/MainForm/Linux_debug_with_qemu)** — Debugging Linux with GDB in a QEMU-based virtual environment.

#### • [PetaLinux Team Project](https://github.com/MainForm/LIG-Nex1_Team-Project_Petalinux)

`Zynq-7000` · `Cortex-A9` · `PetaLinux` · `Yocto` · `Docker`

A PetaLinux build environment for the Zybo Z7-10. The project includes a
board-specific Yocto layer, systemd, Docker support, Wi-Fi support, kernel and
device-tree configuration, and an SD-card image deployment workflow.

</details>

<details>
<summary><strong>⚙️ MCU Projects — ARM Cortex-M</strong></summary>

#### • [STM32 On-Device MNIST Recognition](https://github.com/MainForm/STM32_DISC_MNIST_on_device)

`STM32F429` · `Cortex-M4F` · `FreeRTOS` · `X-CUBE-AI` · `C / C++`

An on-device handwritten-digit recognition system for the STM32F429I-DISC1.
It combines touchscreen input, CNN inference, FreeRTOS tasks and queues,
double-buffered TFT rendering, and output through an I2C LCD and UART.

#### • [STM32F429I-DISC1 SD Card](https://github.com/MainForm/F429I_DISC1_SDCard)

`STM32F429` · `Cortex-M4F` · `SPI` · `SD Card` · `C`

An STM32F429I-DISC1 project that accesses an SD card through SPI and reads
the contents of files stored on the card.

#### • [STM32 I2C Character LCD Driver](https://github.com/MainForm/STM32_LCD_I2C)

`STM32F429` · `Cortex-M4F` · `C++` · `I2C` · `HD44780`

A C++ driver for controlling an HD44780-compatible character LCD through a
PCF8574 I2C backpack using the STM32 HAL.

</details>

<details>
<summary><strong>⚡ MCU Projects — AVR</strong></summary>

#### • [Arduino UNO R3 KiCad Design](https://github.com/MainForm/MyArduinoR3_KiCAD)

`ATmega328P` · `ATmega16U2` · `AVR` · `KiCad` · `PCB Design`

A two-layer Arduino UNO R3-compatible board designed from schematic capture
through PCB layout and manufacturing Gerber output. The design includes power
selection, USB-to-serial communication, protection circuits, and board headers.

</details>

<details>
<summary><strong>🪟 Desktop Applications</strong></summary>

#### • [Chess Game in MFC](https://github.com/MainForm/ChessGameInMFC)

`C++` · `MFC` · `Windows`

A desktop chess game implemented in C++ using Microsoft Foundation Classes.

#### • [Minesweeper](https://github.com/MainForm/Minesweeper)

`C` · `Win32 API` · `Windows`

A desktop Minesweeper game implemented in C using the native Windows API.

</details>

## Templates & Libraries

<details>
<summary><strong>🧱 Embedded Linux Templates</strong></summary>

- **[Raspberry Pi 4 Qt 6 Yocto Template](https://github.com/MainForm/yocto_rpi4_qt6_template)** — A Yocto-based 64-bit Raspberry Pi 4 image template with Qt 6 and a custom application layer.
- **[Raspberry Pi 4 Yocto Template](https://github.com/MainForm/yocto_rpi4_template)** — A reusable Yocto build environment using Poky, OpenEmbedded, and the Raspberry Pi BSP layer.
- **[Raspberry Pi 4 Yocto kas Template](https://github.com/MainForm/yocto_rpi4_with_kas_template)** — A reproducible Raspberry Pi 4 Yocto build configured through `kas`.
- **[Raspberry Pi 4 Qt 5 Buildroot Template](https://github.com/MainForm/Buildroot_RPI4_QT5_Template)** — A Buildroot image template for Raspberry Pi 4 with Qt 5 support.
- **[Raspberry Pi 4 Buildroot Template](https://github.com/MainForm/Buildroot_rpi4_template)** — A 64-bit Raspberry Pi 4 Buildroot project organized as a reusable `BR2_EXTERNAL` tree.
- **[AMD EDF Zybo Z7-10 Workspace](https://github.com/MainForm/AMD-EDF_zybo-z7-10)** — A Yocto build workspace combining AMD EDF with a custom Zybo Z7-10 board-support layer.

</details>

<details>
<summary><strong>🔧 MCU Build Templates</strong></summary>

- **[AVR Makefile Template](https://github.com/MainForm/AVR-makefile-template)** — A Makefile-based build, upload, and JTAG debugging template for 8-bit AVR microcontrollers.

</details>

<details>
<summary><strong>🐧 Linux Device Drivers</strong></summary>

- **[LCD1602 I2C Linux Kernel Module](https://github.com/MainForm/linux_module_lcd1602_i2c)** — A Raspberry Pi 4 character device driver for controlling an LCD1602 through a PCF8574-compatible I2C backpack. It exposes `/dev/lcd1602` for text output and display control through `write()` and `ioctl()`.

</details>

<details>
<summary><strong>📦 STM32 Device Libraries</strong></summary>

- **[STM32 Character LCD](https://github.com/MainForm/STM32_CharacterLCD)** — A reusable character LCD library for STM32 projects.
- **[STM32 ILI9341 Driver](https://github.com/MainForm/STM32_ILI9341_Driver)** — A C++20 display driver for the STM32F429I-DISC1 onboard ILI9341 TFT LCD.
- **[STM32 STMPE811 Driver](https://github.com/MainForm/STM32_STMPE811_Driver)** — A reusable STMPE811 touchscreen controller driver for STM32 projects.
- **[STM32 MPU9250](https://github.com/MainForm/STM32_MPU9250)** · **In Development** — An STM32 device library for the MPU9250 9-axis motion sensor.

</details>
