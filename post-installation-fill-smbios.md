# Post installation: fill SMBIOS info

- open `EFI/CLOVER/config.plist` with Clover Configurator
- generate SMBIOS info with 'iMac18,1', if you use eGPU, select 'iMac18,3' please.
  ![SMBIOS-0](./screenshots/smbios-0.png)
  ![SMBIOS-1](./screenshots/smbios-1.png)
- Copy `BoardSerialNumber`, paste in `RtVariables`-`MLB`.
- Select 'UseMacAddr0' for `RtVariables`-`ROM`
  ![SMBIOS-2](./screenshots/smbios-2.jpg)
