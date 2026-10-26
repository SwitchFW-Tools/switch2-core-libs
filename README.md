# Switch 2 Core Libraries 📚

[![C++](https://img.shields.io/badge/C%2B%2B-17-blue.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](#)

A collection of core C++ libraries developed by the OpenCore team for the Nintendo Switch 2 architecture. 

These libraries serve as the foundation for our tools, including the [Switch 2 Bootstrapper](https://github.com/OpenCore-Homebrew/switch2-bootstrapper).

## 📦 Modules Included

- **`nx2-mem`**: Advanced memory reading and writing utilities.
- **`nx2-usb`**: Wrapper for USB-C payload communication.
- **`nx2-crypto`**: Implementation of the Switch 2 signature bypass algorithms.

## 🛠️ Building

To compile these libraries, you will need **devkitPro** and CMake installed.

```bash
git clone https://github.com/SwitchFW-Tools/switch2-core-libs.git
cd switch2-core-libs
mkdir build && cd build
cmake ..
make -j$(nproc)
