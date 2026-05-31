# 🐧 Linux Device Drivers Mastery

<p align="center">
  <b>Master Linux Device Driver Development from Kernel APIs → Real-World Hardware Drivers</b><br>
  A complete roadmap for Embedded Linux, BSP, Automotive, Robotics, Camera, Audio, and SoC Driver Development.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Linux_Device_Drivers-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Level-Beginner_to_Advanced-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Kernel_&_Driver_Development-blue?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/Srivathsan98/Linux-Device-Drivers-Mastery?style=for-the-badge" />
</p>

---

## 🧠 About

**Linux Device Drivers Mastery** is a structured learning system designed to help you:

✔ Understand Linux kernel driver architecture

✔ Master Linux device model and driver frameworks

✔ Develop character, platform, I2C, SPI, UART, USB, and PCIe drivers

✔ Understand DMA, interrupts, memory management, and synchronization

✔ Build camera, audio, display, storage, and networking drivers

✔ Learn BSP and production Linux development

✔ Transition into Embedded Linux, Automotive, Robotics, and SoC development

---

## 🗺️ Roadmap Overview

```mermaid
flowchart LR

A[Driver Model]
--> B[Character Drivers]

B --> C[Interrupts]

C --> D[DMA & Memory]

D --> E[Platform Drivers]

E --> F[I2C Drivers]

F --> G[SPI Drivers]

G --> H[GPIO & PWM]

H --> I[Network Drivers]

I --> J[Storage Drivers]

J --> K[USB Drivers]

K --> L[PCIe Drivers]

L --> M[Display Drivers]

M --> N[Audio Drivers]

N --> O[Camera Drivers]

O --> P[UART Drivers]

P --> Q[IIO Sensors]

Q --> R[Power Management]

R --> S[CAN Drivers]

S --> T[Kernel Debugging]

T --> U[BSP Development]

U --> V[Upstreaming]
```

---

## 🌐 GitHub Pages

Link to GitHub Page - https://srivathsan98.github.io/Linux-Device-Drivers-Mastery/Linux-Device-Drivers-Mastery-Tracker.html

---

## 📚 Learning Modules

### 🏗️ Driver Model & Kernel Object Infrastructure

* Device Model
* kobject
* kset
* sysfs
* Device Binding
* Uevents
* Reference Counting

### 📄 Character Devices

* cdev API
* file_operations
* ioctl
* mmap
* poll/select
* Blocking I/O

### ⚡ Interrupts & Bottom Halves

* IRQ Handling
* Threaded IRQs
* Tasklets
* Workqueues
* Soft IRQs
* NAPI

### 💾 Memory & DMA

* DMA API
* Scatter-Gather
* IOMMU
* Coherent DMA
* Memory Mapping
* Cache Coherency

### 🔧 Platform Drivers & Device Tree

* Platform Devices
* Device Tree
* DT Bindings
* Clocks
* Regulators
* Reset Controllers

### 🌡️ I2C Driver Development

* i2c_client
* SMBus
* regmap
* Sensor Drivers
* EEPROM Drivers

### 🔌 SPI Driver Development

* spi_device
* spi_transfer
* DMA SPI
* SPI Flash
* Sensor Drivers

### 📌 GPIO, Pinctrl & PWM

* GPIO Framework
* gpiod API
* pinctrl
* Pin Multiplexing
* PWM Framework
* LED Drivers

### 🌐 Network Device Drivers

* net_device
* sk_buff
* NAPI
* ethtool
* XDP
* Ethernet Drivers

### 📦 Block Device & Storage Drivers

* blk-mq
* BIO
* Request Queues
* NVMe
* eMMC
* NAND
* UFS

### 🔗 USB Driver Development

* USB Core
* URBs
* HID
* USB Audio
* USB Video
* Gadget Framework

### 💻 PCIe Driver Development

* BAR Mapping
* MSI/MSI-X
* DMA
* Config Space
* SR-IOV
* AER

### 📺 Display & GPU Drivers

* DRM
* KMS
* GEM
* TTM
* Atomic Modesetting
* Display Pipelines

### 🔊 Audio Drivers

* ALSA
* ASoC
* PCM
* CODEC Drivers
* DAPM
* HDMI Audio

### 📷 Camera Drivers

* V4L2
* Media Controller
* CSI-2
* ISP
* Camera Sensors
* Streaming Pipelines

### 📟 UART & Serial Drivers

* TTY Layer
* UART Core
* RS232
* RS485
* DMA UART
* Serial Console

### 🔭 Sensor Drivers & IIO

* IIO Framework
* Channels
* Triggers
* Buffers
* IMU Drivers
* Sensor Fusion

### 🔋 Power Management

* Runtime PM
* System Suspend
* Wake Sources
* Clock Gating
* DVFS
* PM Domains

### 🚗 CAN & Automotive Drivers

* SocketCAN
* CAN FD
* CAN XL
* UDS
* Automotive Integration

### 🐞 Kernel Debugging

* printk
* ftrace
* perf
* kgdb
* crash
* Dynamic Debug

### 🏭 BSP Development

* Kernel Configuration
* Board Bring-Up
* Device Trees
* Yocto Integration
* Boot Flow
* Production BSPs

### 🌍 Driver Upstreaming

* Coding Style
* Patch Submission
* Maintainer Workflow
* Kernel Mailing Lists
* Review Process

---

## 🛠️ Projects (Hands-On)

| Project | Level | Description |
|----------|----------|-------------|
| 📄 Character Driver | Beginner | Custom Linux character device |
| ⚡ Interrupt Driven Driver | Beginner | GPIO interrupt handling |
| 🌡️ I2C Sensor Driver | Beginner | Temperature sensor driver |
| 🔌 SPI Sensor Driver | Beginner | SPI communication driver |
| 📌 GPIO Controller Driver | Intermediate | GPIO subsystem integration |
| 📟 UART Driver | Intermediate | Custom UART implementation |
| 🚗 CAN Driver | Intermediate | SocketCAN integration |
| 🌐 Virtual Network Driver | Advanced | Linux network interface |
| 📦 RAM Block Driver | Advanced | Block storage driver |
| 🔗 USB Device Driver | Advanced | USB peripheral driver |
| 💻 PCIe Driver | Advanced | BAR mapping & DMA |
| 📷 V4L2 Camera Driver | Expert | CSI-2 camera integration |
| 🔊 ALSA Audio Driver | Expert | Audio codec driver |
| 📺 DRM Display Driver | Expert | Display controller driver |
| 🏭 Complete BSP Bring-Up | Expert | Board support package project |

---

## 📁 Project Structure

```bash
linux-device-drivers-mastery/
│
├── 01-driver-model/
├── 02-character-devices/
├── 03-interrupts/
├── 04-memory-dma/
├── 05-platform-drivers/
├── 06-i2c/
├── 07-spi/
├── 08-gpio-pinctrl-pwm/
├── 09-network-drivers/
├── 10-storage-drivers/
├── 11-usb/
├── 12-pcie/
├── 13-display-drivers/
├── 14-audio-drivers/
├── 15-camera-drivers/
├── 16-uart-drivers/
├── 17-iio/
├── 18-power-management/
├── 19-can-drivers/
├── 20-kernel-debugging/
├── 21-bsp-development/
├── 22-driver-upstreaming/
├── projects/
└── README.md
```

---

## 🧰 Recommended Tools

| Tool | Purpose |
|--------|---------|
| dmesg | Kernel Logs |
| ftrace | Kernel Tracing |
| perf | Performance Analysis |
| kgdb | Kernel Debugging |
| crash | Kernel Crash Analysis |
| Wireshark | CAN & Network Analysis |
| v4l2-ctl | Camera Testing |
| media-ctl | Media Pipeline Debugging |
| alsamixer | Audio Testing |
| i2c-tools | I2C Debugging |
| can-utils | CAN Development |
| Yocto | BSP Development |

---

## 🎯 Goals

* 🐧 Understand Linux driver architecture
* ⚡ Master interrupts and DMA
* 🔌 Develop embedded peripheral drivers
* 📷 Build camera and imaging drivers
* 🔊 Develop audio subsystems
* 🌐 Understand networking internals
* 🚗 Learn automotive Linux development
* 🏭 Build production-ready BSPs

---

## 📈 Progress Tracker

* [ ] Driver Model
* [ ] Character Devices
* [ ] Interrupts
* [ ] DMA & Memory
* [ ] Platform Drivers
* [ ] I2C Drivers
* [ ] SPI Drivers
* [ ] GPIO & PWM
* [ ] Network Drivers
* [ ] Storage Drivers
* [ ] USB Drivers
* [ ] PCIe Drivers
* [ ] Display Drivers
* [ ] Audio Drivers
* [ ] Camera Drivers
* [ ] UART Drivers
* [ ] IIO Sensors
* [ ] Power Management
* [ ] CAN Drivers
* [ ] Kernel Debugging
* [ ] BSP Development
* [ ] Driver Upstreaming

---

## 🏆 End Goal

By the end of this roadmap, you should be able to:

✅ Develop Linux kernel drivers

✅ Build BSPs for embedded systems

✅ Debug kernel and hardware issues

✅ Develop camera, audio, display, and networking drivers

✅ Work on Automotive Linux platforms

✅ Contribute drivers to the Linux kernel

✅ Become a professional Embedded Linux Driver Developer

---

## 🤝 Contributing

Want to improve this roadmap?

1. Fork the repo
2. Create a branch
3. Submit a Pull Request

---

## ⭐ Support

If this helped you:

👉 Star the repo

👉 Share with others

👉 Contribute projects & improvements

---

## 📜 License

MIT License

---

<p align="center">
Built with 🐧 + ⚡ + 🔧 + 📷 + curiosity
</p>