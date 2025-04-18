# Hackintosh for Lenovo IdeaPad 320-17IKB (Type 80XM)

## Description
EFI build for installing macOS Ventura on the Lenovo IdeaPad 320-17IKB laptop using the OpenCore bootloader version 0.8.6.

## Key Build Features
- **Bootloader**: OpenCore 0.8.6  
- **macOS Support**: Ventura  

### Hardware
- **Processor**: Intel Core i5/i7 7th Generation  
- **Graphics**: Intel HD Graphics 620  
- **Touchpad**: ELAN  
- **Audio**: Realtek ALC  
- **Wi-Fi**: Depends on the model; a module replacement may be required  

## Recommendations

### Before Installation
1. Disable **Secure Boot** and **Fast Boot** in the BIOS.  
2. Ensure that the SATA mode is set to **AHCI**.  

### Installing macOS
1. Create a bootable USB drive with macOS Ventura.  
2. Copy the contents of the `EFI` folder to the EFI partition of the USB drive.  
3. Boot from the USB drive and install macOS.  
