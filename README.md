![Dark Logo](assets/awesome_zephyr_rtos_logo_dark.png#gh-dark-mode-only)
![Ligh Logo](assets/awesome_zephyr_rtos_logo_light.png#gh-light-mode-only)

# 🪁 Awesome Zephyr RTOS with stars

> The Zephyr RTOS is based on a small-footprint kernel designed for use on resource-constrained and embedded systems: from simple embedded environmental sensors and LED wearables to sophisticated embedded controllers, smart watches, and IoT wireless applications.

[What is an awesome list?](https://github.com/sindresorhus/awesome/blob/main/awesome.md) ⭐ 498,470 | 🐛 105 | 📅 2026-08-18

> \[!NOTE]\
> The Zephyr Project has started to maintain an [awesome list](https://github.com/zephyrproject-rtos/awesome-zephyr-rtos) ⭐ 67 | 🐛 4 | 📅 2026-02-24. We encourage you to check it out and contribute.

## Contents

* [Official Resources](#official-resources)
* [Libraries](#libraries)
* [Tools](#tools)
* [Open Source Hardware](#open-source-hardware)
* [Videos](#videos)
* [Learning Material](#learning-material)

## Official Resources

* [zephyrproject.org](https://www.zephyrproject.org/) - Official website.
* [docs.zephyrproject.org](https://docs.zephyrproject.org/) - Project documentation.
* [github](https://github.com/zephyrproject-rtos) - Project GitHub organization.
  * [zephyr](https://github.com/zephyrproject-rtos/zephyr) ⭐ 16,277 | 🐛 3,974 | 🌐 C | 📅 2026-08-21 - Main repo.
  * [west](https://github.com/zephyrproject-rtos/west) ⭐ 360 | 🐛 67 | 🌐 Python | 📅 2026-08-10 - Swiss-army knife command line tool.
  * [sdk-ng](https://github.com/zephyrproject-rtos/sdk-ng) ⭐ 286 | 🐛 81 | 🌐 C | 📅 2026-08-03 - Next generation toolchains & host tools.
  * [example-application](https://github.com/zephyrproject-rtos/example-application) ⭐ 359 | 🐛 2 | 🌐 C | 📅 2026-08-10 - Example out-of-tree application that is also a module.
  * [docker-image](https://github.com/zephyrproject-rtos/docker-image) ⭐ 248 | 🐛 12 | 🌐 Shell | 📅 2026-07-30 - Docker image suitable for development and CI.
* [discord](https://discord.com/invite/Ck7jw53nU2) - Community chat hosted on Discord.
* [mailing list](https://lists.zephyrproject.org/g/main/subgroups) - Mail & web based mailing list powere by Groups.io.
* [youtube](https://www.youtube.com/c/ZephyrProject) - Conferences videos and event highlights.
* [blog](https://www.zephyrproject.org/community/#blog) / [RSS](https://www.zephyrproject.org/category/blog/feed/) - Posts from the project and community.
* [twitter](https://twitter.com/zephyriot) / [linkedin](https://www.linkedin.com/company/the-zephyr-project) / [facebook](https://www.facebook.com/ZephyrIoT/) / [mastodon](https://social.lfx.dev/@zephyr) - Various social feeds.
* [newsletter](https://www.zephyrproject.org/newsletter/) - Quarterly newsletter.
* [ambassadors](https://www.zephyrproject.org/ambassadors/) - List of community experts.
* [vulnerability alert registry](https://www.zephyrproject.org/vulnerability-registry/) - Email notifications of vulnerabilties.
* [store](https://zephyr-project.myspreadshop.com/) - Get merch.
* [job board](https://www.zephyrproject.org/careers/) - Search roles from Zephyr member companies.

## Libraries

### Application frameworks

* [control](https://github.com/swedishembedded/control) ⭐ 178 | 🐛 0 | 🌐 MATLAB | 📅 2023-10-08 - A control systems design library written in pure C that provides you with advanced algorithms for control, state estimation and model identification specifically designed for use on embedded systems.
* [micro\_ros\_zephyr\_module](https://github.com/micro-ROS/micro_ros_zephyr_module) ⭐ 90 | 🐛 19 | 🌐 C | 📅 2025-12-15 - ROS 2 for microcontrollers.
* [Swedish Embedded Platform SDK](https://github.com/swedishembedded/sdk) ⭐ 70 | 🐛 4 | 🌐 JavaScript | 📅 2023-08-13 - Swedish Embedded Platform SDK is a comprehensive platform for firmware development.
* [gsoc-2022-arduino-core](https://github.com/zephyrproject-rtos/gsoc-2022-arduino-core) ⭐ 65 | 🐛 23 | 🌐 C++ | 📅 2026-08-20 - Arduino Core API module with an Arduino-C++ style abtraction layer.
* [zpp](https://github.com/lowlander/zpp) ⭐ 60 | 🐛 2 | 🌐 C++ | 📅 2023-01-13 - C++20 framework.
* [open-amp](https://github.com/zephyrproject-rtos/open-amp) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2026-05-05 - Open Asymmetric Multi Processing (OpenAMP) framework.
* [chre](https://github.com/zephyrproject-rtos/chre) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2026-03-13 - Context Hub Runtime Environment (CHRE) is Android’s platform for developing always-on applications, called nanoapps.
* [Sense-VM](https://github.com/svenssonjoel/Sense-VM) ⭐ 7 | 🐛 19 | 🌐 C | 📅 2022-05-14 - Bytecode virtual machine for microcontrollers.

### Containerization

* [ocre](https://github.com/project-ocre/ocre-runtime) ⭐ 142 | 🐛 17 | 🌐 C | 📅 2026-05-26 - OCI compliant application container runtime.

### Filesystem

* [littlefs](https://github.com/zephyrproject-rtos/littlefs) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2026-08-18 - Little fail-safe filesystem designed for microcontrollers.
* [fats](https://github.com/zephyrproject-rtos/fatfs) ⭐ 18 | 🐛 1 | 🌐 C | 📅 2026-07-22 - Generic FAT/exFAT filesystem module for small embedded systems.
* [nffs](https://github.com/zephyrproject-rtos/nffs) ⚠️ Archived - Flash file system prioritizing minimal ram usage & reliability.

### HAL/PAL

* [libmetal](https://github.com/zephyrproject-rtos/libmetal) ⭐ 17 | 🐛 1 | 🌐 C | 📅 2026-05-05 - Abstraction layer across user-space Linux, baremetal, and RTOS environments.
* [cmsis](https://github.com/zephyrproject-rtos/cmsis) ⭐ 14 | 🐛 2 | 🌐 C | 📅 2025-06-03 - Standardized API for the Cortex-M processor core and peripherals.

### IoT & Cloud

* [Eclipse hawkbit](https://github.com/eclipse/hawkbit) ⭐ 592 | 🐛 65 | 🌐 Java | 📅 2026-08-21 - Firmware Update Server.
* [Memfault](https://github.com/memfault/memfault-firmware-sdk/tree/master/ports/zephyr) ⭐ 235 | 🐛 5 | 🌐 C | 📅 2026-08-05 - Cloud-based debugging & observability.
* [openhaystack-zephyr](https://github.com/koenvervloesem/openhaystack-zephyr) ⭐ 90 | 🐛 1 | 🌐 C | 📅 2022-06-10 - Track personal Bluetooth devices via Apple's massive Find My network.
* [Golioth](https://github.com/golioth/golioth-zephyr-sdk) ⚠️ Archived - Device Management & cloud enablement platform.
* [send-my-sensor](https://github.com/koenvervloesem/send-my-sensor) ⭐ 28 | 🐛 1 | 🌐 C | 📅 2022-06-10 - Upload sensor data from a device without internet connection by (ab)using Apple's Find My network.
* [thingset-zephyr-sdk](https://github.com/ThingSet/thingset-zephyr-sdk) ⭐ 22 | 🐛 7 | 🌐 C | 📅 2026-04-16 - A software development kit (SDK) based on Zephyr RTOS to integrate communication interfaces using the ThingSet protocol into an application with minimum effort. See <https://thingset.io/>.
* [Edge Impulse](https://github.com/edgeimpulse/example-standalone-inferencing-zephyr) ⭐ 19 | 🐛 2 | 🌐 CMake | 📅 2025-07-22 - Machine learning on edge devices.
* [Anjay-zephyr](https://github.com/AVSystem/Anjay-zephyr) ⚠️ Archived - C implementation of the client-side OMA LwM2M protocol.
* [zephyrus](https://github.com/mustafaabdullahk/zephyrus) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-05-12 - A lightweight C library for exposing Prometheus metrics in Zephyr applications.

### Languages & Runtimes

* [micropython](https://github.com/micropython/micropython) ⭐ 22,001 | 🐛 1,537 | 🌐 C | 📅 2026-08-18 - a lean and efficient Python implementation for microcontrollers and constrained systems.
* [wasm-micro-runtime](https://github.com/bytecodealliance/wasm-micro-runtime) ⭐ 6,071 | 🐛 598 | 🌐 C | 📅 2026-08-21 - Lightweight standalone WebAssembly (WASM) runtime.
* [lispBM](https://github.com/svenssonjoel/lispBM) ⭐ 132 | 🐛 3 | 🌐 C | 📅 2026-08-19 - LispBM is a lisp or scheme like programming language for microcontrollers.

### Networking & Protocols

* [pjon](https://github.com/gioblu/PJON) ⭐ 2,815 | 🐛 60 | 🌐 C++ | 📅 2025-11-21 - Multi-master, multi-media network protocol.
* [BACnet Stack](https://github.com/bacnet-stack/bacnet-stack) ⭐ 587 | 🐛 94 | 🌐 C | 📅 2026-08-20 - BACnet open source protocol stack for embedded systems, Linux, and Windows.
* [openthread](https://github.com/zephyrproject-rtos/openthread) ⭐ 31 | 🐛 1 | 🌐 C++ | 📅 2026-07-06 - Thread mesh networking protocol.
* [canopennode](https://github.com/zephyrproject-rtos/canopennode) ⭐ 13 | 🐛 1 | 🌐 C | 📅 2026-04-07 - CANopen Stack.
* [greybus-for-zephyr](https://github.com/cfriedt/greybus-for-zephyr) ⭐ 7 | 🐛 30 | 🌐 C | 📅 2022-07-01 - Protocol for hotpluggable devices.
* [nanopb](https://github.com/zephyrproject-rtos/nanopb) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2026-03-03 - Protocol Buffers for Embedded Systems.
* [civetweb](https://github.com/zephyrproject-rtos/civetweb) ⚠️ Archived - Embeddable web server.
* [CBOR](https://cbor.io/) - Concise Binary Object Representation.
  * [QCBOR](https://github.com/laurencelundblade/QCBOR) ⭐ 239 | 🐛 24 | 🌐 C | 📅 2026-08-20 - Comprehensive CBOR library.
  * [zcbor](https://github.com/NordicSemiconductor/zcbor/) ⭐ 165 | 🐛 32 | 🌐 C | 📅 2026-08-20 - CBOR library that includes support for CDDL.
  * [tinycbor](https://github.com/zephyrproject-rtos/tinycbor) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2022-04-07 - Small CBOR library.
* [cosy](https://github.com/lindemer/cozy) - CBOR Object Signing and Encryption (COSE).
* [S2OPC](https://gitlab.com/systerel/S2OPC) - Open-source OPC-UA Toolkit designed with security and embedded devices in mind.

### Security

* [TF - M](https://github.com/zephyrproject-rtos/trusted-firmware-m) ⭐ 49 | 🐛 8 | 🌐 C | 📅 2026-08-18 - Platform Security Architecture (PSA) for ARMv7-M and Armv8-M.
* [MCUboot](https://github.com/zephyrproject-rtos/mcuboot) ⭐ 41 | 🐛 1 | 🌐 C | 📅 2026-08-21 - A secure bootloader for 32-bits microcontrollers.
* [mbed TLS](https://github.com/zephyrproject-rtos/mbedtls) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2026-08-13 - C library that implements cryptographic primitives, X.509 certificate manipulation and the SSL/TLS and DTLS protocols.
* [aerology](https://github.com/Linaro/aerology) ⭐ 25 | 🐛 2 | 🌐 Rust | 📅 2025-01-24 - Inspect Zephyr and TF-M applications, post mortem.
* [tinycrypt](https://github.com/zephyrproject-rtos/tinycrypt) ⭐ 3 | 🐛 2 | 🌐 C | 📅 2024-03-04 - Cryptographic library with a minimal set of standard cryptography primitives.

### Misc

* [zmk](https://github.com/zmkfirmware/zmk) ⭐ 4,231 | 🐛 417 | 🌐 C | 📅 2026-08-21 - Keyboard firmware with a rich featureset and broad hardware support.
* [zephyr-rust](https://github.com/tylerwhall/zephyr-rust) ⭐ 278 | 🐛 9 | 🌐 Rust | 📅 2024-10-21 - API bindings, libstd, and Cargo integration for Rust.
* [zscilib](https://github.com/zephyrproject-rtos/zscilib) ⭐ 166 | 🐛 24 | 🌐 C | 📅 2026-03-02 - Scientific computing library.
* [pinetime-zephyr](https://github.com/najnesnaj/pinetime-zephyr) ⭐ 122 | 🐛 1 | 🌐 C | 📅 2023-07-22 - Smartwatch operating system.
* [spinner](https://github.com/teslabs/spinner) ⭐ 110 | 🐛 0 | 🌐 C | 📅 2024-03-05 - Motor control firmware based on the Field Oriented Control (FOC) principles.
* [lvgl](https://github.com/zephyrproject-rtos/lvgl) ⭐ 86 | 🐛 7 | 🌐 C | 📅 2026-08-01 - Complete graphics library.
* [ecfw-zephyr](https://github.com/intel/ecfw-zephyr) ⭐ 75 | 🐛 3 | 🌐 C | 📅 2026-08-12 - Embedded Controller for low-level tasks on a motherboard like power sequencing.
* [zephyr-usb-midi](https://github.com/stuffmatic/zephyr-usb-midi) ⭐ 25 | 🐛 2 | 🌐 C | 📅 2026-03-03 - This is a USB MIDI 1.0 device class driver for the Zephyr RTOS, which allows sending and receiving MIDI data (including system exclusive messages) over USB.
* [grbl](https://github.com/iwasz/zephyr-grbl) ⭐ 14 | 🐛 1 | 🌐 C | 📅 2023-07-04 - Motion control for CNC milling.
* [linaro\_sensor\_pipeline](https://github.com/microbuilder/linaro_sensor_pipeline) ⭐ 12 | 🐛 2 | 🌐 C | 📅 2023-09-19 - Secure data pipelines.
* [zbus](https://github.com/zephyr-bus/zbus) ⭐ 11 | 🐛 5 | 🌐 C | 📅 2022-07-29 - Inter thread communication bus.
* [pysvd2dts](https://github.com/thedigitaledge/pysvd2dts) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-04-13 - Creates a Zephyr Devicetree file from an ARM CMSIS-SVD file.
* [tflite-micro](https://github.com/zephyrproject-rtos/tflite-micro) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-03-14 - TensorFlow Lite for Microcontrollers.
* [zcalendar](https://github.com/bpbradley/zcalendar) ⭐ 6 | 🐛 1 | 🌐 C | 📅 2025-12-15 - Calendar API with RTC integration.
* [sof](https://github.com/zephyrproject-rtos/sof) ⭐ 4 | 🐛 1 | 🌐 C | 📅 2025-10-01 - Audio Digital Signal Processing (DSP) firmware infrastructure and SDK.
* [lz4](https://github.com/zephyrproject-rtos/lz4) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2026-04-29 - Extremely Fast Compression algorithm.

## Tools

### Build & Config

* [Zephyr Container Images](https://github.com/embeddedcontainers/zephyr) ⭐ 77 | 🐛 3 | 🌐 Dockerfile | 📅 2026-08-13 - Develop Zephyr applications using OCI-compatible Docker images.
* [action-setup-zephyr](https://github.com/zephyrproject-rtos/action-zephyr-setup) ⭐ 30 | 🐛 6 | 📅 2026-08-21 - This action initializes a Zephyr based project, downloading the Zephyr SDK and the necessary modules for a West based [Zephyr workspace application](https://docs.zephyrproject.org/latest/develop/application/index.html#zephyr-workspace-app).
* [bazel2zephyr](https://github.com/GatCode/bazel2zephyr) ⭐ 9 | 🐛 0 | 🌐 Starlark | 📅 2021-12-22 - Embedded/bare-metal development using bazel.
* CMake
* Device Tree
  * [dtsh](https://github.com/dottspina/dtsh) ⭐ 74 | 🐛 3 | 🌐 Python | 📅 2026-05-04 - Shell-like interface to devicetrees.
* KConfig
* Make
* Ninja
* [Swedish Embedded Platform SDK Docker Image](https://github.com/swedishembedded/develop) - Docker containers for CI & development.

### Compilers

Note: the official SDK includes several compilers.

* GNU Arm Embedded
* Arm Compiler 6
* Intel oneAPI Toolkit
* DesignWare ARC MetaWare Development Toolkit (MWDT)
* Cadence Tensilica Xtensa C/C++ Compiler (XCC)
* Espressif tools

### Editors & IDEs

#### Visual Studio Code

* [zephyr-ide](https://github.com/mylonics/zephyr-ide) ⭐ 96 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-28 - The Zephyr IDE for VS code extension provides tools to aide in your Zephyr Project work flow.
* [Zephyr Tools for VSCode](https://github.com/circuitdojo/zephyr-tools) ⭐ 27 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Circuit Dojo designed Zephyr Tools to make getting started with Zephyr a snap.
* [VS Code importer](https://github.com/smrtos/Zephyr2VSC) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2023-01-31
* [Zephyrus](https://github.com/tuScale/vscode-zephyrus) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2021-09-02
* [Ardesco-VSCode-Extension](https://github.com/Ericsson/Ardesco-VSCode-Extension) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2020-12-02 - Ericsson Ardesco device development extension.
* [Embedded Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-embedded-tools) - A register viewer for CMSIS-SVD files and an RTOS data viewer
* [nRF Connect for VS Code](https://marketplace.visualstudio.com/items?itemName=nordic-semiconductor.nrf-connect)
* [PlatformIO](https://docs.zephyrproject.org/latest/guides/platformio/index.html)

#### Other Editors & IDEs

* [Eclipse](https://github.com/zephyrproject-rtos/eclipse-plugin) ⭐ 18 | 🐛 21 | 🌐 Java | 📅 2022-03-29
* [CMake Zephyr helpers](https://github.com/thirdpin/Zephyr-CMake-Helpers) ⭐ 4 | 🐛 0 | 🌐 CMake | 📅 2022-05-27 - Enhance CMake automation for use with VS Code.

### Flash, Debug & Test

* [OpenOCD](https://github.com/zephyrproject-rtos/openocd) ⭐ 46 | 🐛 10 | 🌐 C | 📅 2026-02-24
* [jlink-zephyr](https://github.com/zephyrproject-rtos/jlink-zephyr) ⭐ 40 | 🐛 6 | 🌐 C | 📅 2026-03-16 - Zephyr RTOS plugin for JlinkGDBserver.
* [mcumgr](https://github.com/zephyrproject-rtos/mcumgr) ⭐ 36 | 🐛 0 | 🌐 C | 📅 2022-11-16
  * [iOS](https://github.com/NordicSemiconductor/IOS-nRF-Connect-Device-Manager) ⭐ 164 | 🐛 2 | 🌐 Swift | 📅 2026-08-05
  * [Android](https://github.com/NordicSemiconductor/Android-nRF-Connect-Device-Manager) ⭐ 140 | 🐛 19 | 🌐 Java | 📅 2026-08-19
  * [Web](https://github.com/boogie/mcumgr-web) ⭐ 63 | 🐛 3 | 🌐 JavaScript | 📅 2026-06-18
* [Aerology](https://github.com/Linaro/aerology) ⭐ 25 | 🐛 2 | 🌐 Rust | 📅 2025-01-24 - Inspect Zephyr and TF-M applications, post mortem.
* [SEGGER](https://github.com/zephyrproject-rtos/segger) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2026-01-27
* [GNU Tools (GDB, Binutils)](https://github.com/zephyrproject-rtos/binutils-gdb) ⭐ 3 | 🐛 5 | 🌐 C | 📅 2026-08-02
* [EDTT (Embedded Device Test Tool)](https://github.com/zephyrproject-rtos/edtt) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-08-13
* [libjaylink](https://github.com/zephyrproject-rtos/libjaylink) ⭐ 1 | 🐛 1 | 🌐 C | 📅 2020-02-01 - libjaylink is a shared library written in C to access SEGGER J-Link and compatible devices.
* Atmel SAM-BA
* esptool
* pyOCD
* Twister

### Simulation

* ACRN
* [QEMU](https://github.com/zephyrproject-rtos/qemu) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2026-07-28
  * [Network Tools](https://github.com/zephyrproject-rtos/net-tools) ⭐ 47 | 🐛 7 | 🌐 C | 📅 2026-08-07
  * [SeaBIOS](https://github.com/zephyrproject-rtos/seabios) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2025-07-22
* [Renode](https://zephyr-dashboard.renode.io/)
* XEN

### Version Control

* [zephyr-pre-commit-hooks](https://github.com/cgnd/zephyr-pre-commit-hooks) ⭐ 4 | 🐛 0 | 📅 2023-09-06 - A collection of [pre-commit](https://pre-commit.com/) hooks for use with Zephyr.

## Open Source Hardware

* [ZMK](https://github.com/zmkfirmware/zmk) ⭐ 4,231 | 🐛 417 | 🌐 C | 📅 2026-08-21 - ZMK Firmware is an open source (MIT) keyboard firmware built on the Zephyr™ Project Real Time Operating System (RTOS).
* [ZSWatch](https://github.com/jakkra/ZSWatch) ⭐ 82 | 🐛 0 | 🌐 C | 📅 2026-04-22 - The Open Source Zephyr™ based Smartwatch, including both HW and FW.

## Videos

* [Introducing a New Zephyr Sensing Subsystem 2023](https://www.youtube.com/watch?v=iHfeAqtPSnA)
* [How I Fell in Love with Zephyr – a System Architect’s Tale (2023)](https://www.youtube.com/watch?v=rG4rC5oLx7Y)
* [Zephyr Developer Summit - June 2021](https://www.youtube.com/playlist?list=PLzRQULb6-ipG39tVb-DEkIoSS5wQlbK6i)
* [Embedded Linux Conference/Open Source Summit (Sept. 2021)](https://www.youtube.com/playlist?list=PLzRQULb6-ipEfltSXvM0xBuU84B8-sum7)
* [Zephyr videos from Golioth](https://www.youtube.com/playlist?list=PLXGira7Qd83DljhI7F3euGgsf4hbvhoNp)
* [#zephyrrtos](https://www.youtube.com/hashtag/zephyrrtos) - Videos tagged with `#zephyrrtos`.

## Learning Material

* [Tutorial for Beginners](https://github.com/maksimdrachov/zephyr-rtos-tutorial) ⭐ 471 | 🐛 10 | 🌐 C | 📅 2024-04-07
* [Nordic Developer Academy](https://www.nordicsemi.com/Support/Nordic-Developer-Academy)
* [Ultimate Embedded Firmware DevOps Infrastructure](https://www.udemy.com/course/ultimate-embedded-firmware-devops-infrastructure/)

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-21._
