# spagettimod
# 40% Mechanical Keyboard Firmware

A compact 40% hand-wired mechanical keyboard firmware for Arduino Pro Micro with 47 keys and three functional layers.

##  Features

- **47-key layout** optimized for space efficiency
- **Three fully functional layers** with comprehensive key coverage
- **Arduino Pro Micro** compatibility
- **QMK-inspired layer management**
- **Easy customization** and key mapping

##  Hardware Specifications

- **Controller**: Arduino Pro Micro (ATmega32U4)
- **Switches**: MX Mechanical/Tactile
- **Diodes**: 1N4148 (or similar)
- **Layout**: 40% (47 keys)
- **Connectivity**: USB Type-С

## Bootloader

Enter the bootloader in 3 ways:

* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is configured.
* **Physical reset button**: Briefly press the reset button soldered on the PCB.
* **Bootmagic reset**: Hold down the top left key and plug in the controller.
