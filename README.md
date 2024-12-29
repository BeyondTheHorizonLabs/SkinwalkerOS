# SkinwalkerOS

SkinwalkerOS is a custom Linux operating system fork designed for use in paranormal and scientific field testing. It supports ARM and x64 architectures and is optimized for deployment on Raspberry Pi, Orange Pi, and mini ITX systems.

---

## Features

- Built on Ubuntu 24 for general-purpose systems and Raspbian/Raspberry Pi OS for Raspberry Pi devices.
- Includes Alpine Linux-based variants for industrial and micro-form-factor devices.
- Preconfigured for advanced sensor monitoring, drone integration, and SDR tools.
- Lightweight and performance-optimized for field deployment.

---

## Prerequisites

- A compatible device:
  - Raspberry Pi
  - Orange Pi
  - Mini ITX systems
- USB or SD card for installation.

---

## Installation

### Using SkinwalkerPi

The recommended method for installing SkinwalkerOS is through the **SkinwalkerPi** toolkit. SkinwalkerPi automates the installation process and configures the OS for supported devices.

1. Download and set up SkinwalkerPi by following the [SkinwalkerPi README](https://github.com/BeyondTheHorizonLabs/SkinwalkerPi).
2. Run the SkinwalkerPi bootstrap script:

   ```bash
   sudo ./bootstrap.sh
   ```

   This script will install SkinwalkerOS on your device.

### Manual Installation

1. Download the appropriate SkinwalkerOS image from the [releases page](https://github.com/BeyondTheHorizonLabs/SkinwalkerOS/releases).
2. Flash the image onto your USB/SD card using a tool like Balena Etcher.
3. Insert the USB/SD card into your device and power it on.
4. Follow the on-screen prompts to complete the installation.

---

## Usage

### Supported Applications

SkinwalkerOS comes preloaded with software and libraries tailored for:

- Environmental sensors
- GPS and SDR monitoring
- Drone-based data collection
- Scientific and physics experiments

### System Updates

Keep your system up to date with:

```bash
sudo apt update && sudo apt upgrade
```

---

## Credits

SkinwalkerOS is built upon the foundation of open-source Linux distributions. Special thanks to:

- **Ubuntu 24**: The base system for general-purpose ARM and x64 devices.
- **Raspbian/Raspberry Pi OS**: The forked base system for Raspberry Pi devices.
- **Alpine Linux**: Adapted for lightweight, industrial-grade, and micro-form-factor use cases.

We acknowledge the contributions of the open-source community for providing these robust platforms.

---

## Relation to SkinwalkerPi

SkinwalkerOS is designed to be installed and configured using **SkinwalkerPi**. While SkinwalkerOS serves as the core operating system, SkinwalkerPi provides the tools necessary to set up and optimize it for field use. Together, they form a cohesive ecosystem for paranormal and scientific research.

For more information about **SkinwalkerPi**, visit the [SkinwalkerPi repository](https://github.com/BeyondTheHorizonLabs/SkinwalkerPi).

---

## Contribution

We welcome contributions! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

---

## License

This project is licensed under the [MIT License](LICENSE).
