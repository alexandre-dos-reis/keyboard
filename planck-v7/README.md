# How to update the firmware via the cli

- `qmk console`
- Put the keyboard into bootloader mode
- Retrieve the `bootloader name`
- update with `qmk flash -bl stm32-dfu planck.bin`
