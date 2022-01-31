# STM32_Rust_Experiments
Playing around with embedded rust

# Installation - Windows 10

## Setting up Rust Enviroment

https://docs.microsoft.com/en-us/windows/dev-environment/rust/setup

## Setting up debugging

Install gcc-arm-none-eabi (Tested with 10.3-2021.10)
[gcc-arm-none-eabi](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads)

Make sure to select add to PATH at end of installation

Run to check install
```bash
arm-none-eabi-addr2line.exe -v
```

Download and install OpenOCD

Unofficial install hosted here
https://github.com/xpack-dev-tools/openocd-xpack/releases

You need npm installed, then install xpm, then follow instructions to install OpenOCD



