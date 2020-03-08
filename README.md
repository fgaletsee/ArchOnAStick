## ArchOnAStick

ArchOnAStick is a portable Arch Linux system, runnung on a USB stick or ssd with the following features:

  - Full disk encryption
  - Bootable on EFI and BIOS computers
  - Can duplicate itself with one script
  - Stores multiple configs for different computers, Autodetect of configs
  - Multioboot of ISO systems (not implemented yet)
  - Optional partition for Win/Mac sharing


### How to setup your own ArchOnAStick system


#### Recomended gpart layout

  - 10 M Bios EF02
  - 500 M EFI EF00
  - x GB Linux FS xxxx
  - optional x G exfat Share drive
