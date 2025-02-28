# Rainy_UHF_Breakout_Software

<img src="https://github.com/sbcshop/Rainy_UHF_Breakout_Software/blob/main/images/Rainy_UHF_BreakoutBanner.jpg">

The Compact Rainy UHF Module Breakout is a versatile long-range (1–20m) RFID module with Type-C USB and UART support. Can perform multi-tag reading (1–60 tags/sec), supporting ISO 18000-6C (EPC Gen 2) RFID applications! It offers high-speed, precise RFID capabilities, making it ideal for professionals, hobbyists, and electronics enthusiasts.

This GitHub repository provides Rainy UHF module breakout getting started instructions.

### Features:
- **Compact size** UHF module breakout
- **Type C** interface to connect with PC/laptop or compatible system
- **TTL(UART)** pins breakout as standard 2.54” header for interfacing with various **microcontrollers like Arduino, ESP32 or Raspberry,** etc.
- **Jumper option** to choose between Type C and TTL (UART)
- **SMA Antenna port** to connect antenna of choice for increased range 
- Onboard **Buzzer** for alert when card read detected 

### Specifications:
- **Supply Voltage:** 5V
- **Operating Pin:** 3.3V ~ 5V
- **Communication Interface:** TTL (UART), Type C
- **Frequency:** EU 865-868MHz or US 902-928MHz
- **Protocol:** ISO 18000-6C (EPC Gen 2)
- **Read speed:** Multi-tag,1-60tags/second (depend on antenna/tag and application)
- **Read range:**- 1-20m (depend on tag, antenna and application)
- **Read/Write Capability:** Yes
- **RF Power Output:** 15-26 dBm(adjustable)
- **Cooling Method:** Air cooling (no external heat sink required)
- **Antenna port:** 1 port ,SMA
- **Estimated Antenna Range:** 
     - **3dBi Antenna:** 0-2m Range
     - **5.5dBi Antenna:** 0-5m Range

## Getting Started Rainy UHF Breakout
### Pinout 

<img src="https://github.com/sbcshop/Rainy_UHF_Breakout_Software/blob/main/images/Rainy_UHF_Breakout_pinout.jpg">

### Rainy UHF Breakout Standalone 

  - You have two options to use breakout either with Type C or UART interface. For standalone use with software, use Type C interface to connect with PC/laptop. Make sure to put jumper on USB side (2) as shown below,

    <img src="https://github.com/sbcshop/Rainy_UHF_Breakout_Software/blob/main/images/USB_mode.png" width="236" height="252"> 
    
  - Once the Breakout is connected, check your COM Port in the device manager. Device listed with suitable com port,
    
    <img src="https://github.com/sbcshop/NFC_Module/blob/main/images/device_manager_comport_view.png" width="584" height="425">

    If not listed meaning you don't have the CH340 driver installed on your PC/laptop, then follow guide [CH340 Driver Installation Manual Guide](https://github.com/sbcshop/NFC_Module/blob/main/documents/CH340%20Driver%20installation%20steps.pdf).
    
  - Download the software folder provided [here](https://github.com/sbcshop/Rainy_UHF_Breakout_Software/blob/main/Windows%20DEMO%20software.zip), and run the application file, so you will see the below interface of the software.
<!--
    <img src="" width="" height="">
    <img src="" width="" height="">
    <img src="" width="" height="">
    
  - Text here
    <img src="" width="" height="">
    <img src="" width="" height="">
    <img src="" width="" height="">
    
-->

### Rainy UHF Breakout Interface with MCU

  - You have various options ranging from microcontroller to SBC's like Pico, ESP32, Arduino, Raspberry Pi, STM32 boards, etc. Easy integration possible.
  - For interfacing with any MCU select UART mode by setting jumper on uart side (1) as shown below,

    <img src="https://github.com/sbcshop/Rainy_UHF_Breakout_Software/blob/main/images/UART_mode.png" width="207" height="274"> 

  - Follow below reference connection,

     |MCU | Rainy Breakout | Function |
     |---|---|---|
     |5V | 5V | Positive Supply |
     |GND | GND | Supply Ground |
     |TX | RX | Serial UART connection  |
     |RX | TX  | Serial UART connection |
    
  - Checkout more information and sample codes for [Pico](https://github.com/sbcshop/Rainy_UHF_Pico_Expansion_Software), [ESP32](https://github.com/sbcshop/Rainy_UHF_ESP32_Software) and [Raspberry Pi](https://github.com/sbcshop/Rainy_UHF_HAT_Software/).    

 ## Resources
  * [Schematic](https://github.com/sbcshop/Rainy_UHF_Breakout_Hardware/blob/main/Design%20Data/Rainy%20UHF%20Breakout%20SCH.PDF) 
  * [Hardware data](https://github.com/sbcshop/Rainy_UHF_Breakout_Hardware)
  * [Rainy UHF Module Command Manual](https://github.com/sbcshop/Rainy_UHF_Breakout_Software/blob/main/Document/Rainy%20UHF%20Module%20Command%20Manual.pdf)
  * [CH340 Driver Installation Guide](https://github.com/sbcshop/NFC_Module/blob/main/documents/CH340%20Driver%20installation%20steps.pdf)

## Related Products
   * [Rainy UHF HAT](https://shop.sb-components.co.uk/products/rainy-uhf-pi-hat-complete-kit) - UHF module HAT with Standard 40pin to support Raspberry Pi
   * [Rainy UHF Pico Expansion](https://shop.sb-components.co.uk/products/rainypi-uhf-based-on-pico-complete-kit) -  UHF Expansion board easily incorporate Pico/Pico W/Pico 2
   * [Rainy UHF for ESP32](https://shop.sb-components.co.uk/products/rainyfi-uhf-for-esp32-complete-board-kit) - UHF module with embedded ESP32 S3 for IoT prototyping.
   * [Rainy UHF SHIELD](https://shop.sb-components.co.uk/products/rainy-shield-for-arduino-board-complete-kit) - UHF Shield form factor for use with Arduino, Ardi-32, Ardi-Pi, and other compatible boards.  

## Product License

This is ***open source*** product. Kindly check LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>


    
    


