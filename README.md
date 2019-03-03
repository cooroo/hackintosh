# Minimal Clover Config and Kexts for Gigabyte Z390 I WIFI | 9700K

## Why minimal

There are many tutorial and builds around the hackintosh community, but most of them use a lot of clover config and kexts, and those value/kexts lacks of explaination. I tried to search the meaning of the clover config item, but neither clover wiki nor forum (even golden builds) offer me answers. When someone ask questions in tonymacx or other hackintosh forums, most of time what they get is not an answers, but an EFI.zip. Sometimes an EFI.zip is shortcut to success maybe, but the "blackbox" do not offer any knowleage to solve the problem.

So I want to build my hackintosh with minimal config and kexts, I don't know how they works in detail, but I know what they use for at least.

Correct my if I am wrong, Thanks in advance.

## Parts

- Gigabyte Z390 I WIFI
- Intel i7 9700K
- Corsair LPX DDR4 3000
- Samsung 970Evo 500G for macOS
- Samsung 970Evo 250G for Windows
- Western Digital 2.5' 1TB HDD

## Envirenmens

The installation base on vanilla hackintosh tutorial(with excelent explaination) all software/os use the latest version by now(2, March, 2019), but newer versions may works well.

- macOS version: Mojave 10.14.3
- BIOS version: f5d
- CLOVER version: v2.4k r4884

## Pre-Installation

- BIOS setting
  - "Load Optimized Defaults" then "Save and Exit"
  - That's it, it doesn't matter what the values of those options are:
    - Windows 8/10 Features. It's OK with default value "Windows 8/10"
    - CSM Support. It's OK with default value "Enabled""
    - XHCI Hand-off. It's OK with default value "Disabled"
    - Vt-d. It's OK with default value "Enabled"
- Create Installation Media
  - It doesn't matter what usb versions you use. Both USB 2.0 and 3.0 works well.
  - follow the vanilla tutorial
- Install Clover to USB stick
## Installation
## Post-Installation
