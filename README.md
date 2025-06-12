ETHERNET-SWITCH-LAYER-2
🧠 STM32-Based Layer 2 Ethernet Switch
This project implements a custom Layer 2 Ethernet switch using an STM32 microcontroller as the main interface between the user and two Ethernet PHY/switch chips: the Microchip KSZ8795 and the Realtek RTL8211F.

🔧 Key Features
STM32 MCU handles configuration, management, and control of the switch.

KSZ8795 (5-port managed Ethernet switch) is used for Layer 2 packet switching.

RTL8211F provides Gigabit Ethernet PHY functionality.

Custom firmware for communication and control via SPI, MDIO, or other interfaces.

Potential for VLAN, QoS, and port monitoring features depending on firmware implementation.

Powered via USB-C or external power supply (up to 28V DC).

🚀 Applications
Embedded networking devices

Industrial automation

Custom router/switch development

Educational tool for learning about Ethernet switching and embedded networking
