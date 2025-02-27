# Rainy_UHF_Breakout_Software

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
<img src="">

### Rainy UHF Breakout Standalone 

  - You have two options to use breakout either with Type C or UART interface. For standalone use with software, use Type C interface to connect with PC/laptop. Make sure to put jumper on USB (2) side as shown below,

    <img src="https://github.com/sbcshop/NFC_Module/blob/main/images/device_manager_comport_view.png" width="584" height="425"> 
    
  - Once the Breakout is connected, check your COM Port in the device manager. Device listed with suitable com port,
    
    <img src="https://github.com/sbcshop/NFC_Module/blob/main/images/device_manager_comport_view.png" width="584" height="425">

    If not listed meaning you don't have the CH340 driver installed on your PC/laptop, then follow guide [CH340 Driver Installation Manual Guide](https://github.com/sbcshop/NFC_Module/blob/main/documents/CH340%20Driver%20installation%20steps.pdf).
    
  - Download the software folder provided [here](https://github.com/sbcshop/NFC_Module/tree/main/softwares), and run the .exe file, so you will see the below interface of the software.


### Rainy UHF Breakout Interface with MCU


 ## Resources
  * [Schematic](https://github.com/sbcshop/Rainy_UHF_Breakout_Hardware/blob/main/Design%20Data/Rainy%20UHF%20Breakout%20SCH.PDF) 
  * [Hardware data](https://github.com/sbcshop/Rainy_UHF_Breakout_Hardware)
  * [Rainy UHF Module Command Manual]()
  * [CH340 Driver Installation Guide]()
  * 

## Related Products 


## Product License

This is ***open source*** product. Kindly check the LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>     
     

    
    


