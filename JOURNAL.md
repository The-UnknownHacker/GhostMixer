---
Title: "GhostMixer"
Author: "Aarav J"
Description: "GhostMixer is an all one mixer soundpad designed for schools or hobbiest to produce sounds with ease"
Created At: "2025-05-24"
---
# May 24th: Started the PCB!

Today I started working on the PCB and choosing components to add.  
I decided to choose some requirements before starting such as the key components.

I decided on using:

- **Main Board:** Xiao ESP32-S3 x3 (2 for testing and prototyping, 1 for main board)  
- **Audio DAC:** MAX98357A or PCM5102A  
- **3.5mm Jack:** PJ-320D  
- **MicroSD:** Generic TF card reader  
- **Display:** ST7789  
- **I/O Expander:** MCP23017  
- **Switches:** 16x Cherry MX  
- **Main Potentiometer**  
- **Volume Potentiometer**  
- **Rotary Encoder**  
- **Voltage Regulator:** AMS1117-3.3 or AP2112  
- **Misc Capacitors**  
- **Misc Resistors**  
- **Xiao Socket Headers** to plug Xiao into PCB  
- **Power Switch**  
- **Battery Charging Circuit:** Should be portable OR able to be used plugged in (3.7V LiPo + TP4056 Module)  
- **DC Barrel Jack:** Additional power charging option  



![image](https://github.com/user-attachments/assets/83220eb4-dc40-49c7-9eeb-96cb6ee08e02)


**Total time spent: 4h**




# May 25th: Finished Placing Components onto the Schematic and started wiring!

Today I almost finalised the components that I am going to use and imported and downloaded all the footprints into the schematic.  
I started a rough wiring diagram of  how to connect the components togtether and finished the power charging circuit.
I still need to work on getting the switches and other small components wired up and it was quite challening to find different symbols and footprints for each of the components as they didnt have it available online.
![image](https://github.com/user-attachments/assets/2682cd43-e33b-4f3a-8980-5f28084912ab)

**Total time spent: 3h**


# May 26th: Finished wiring up the switches and power circuit

Today I finsished configuring the GPIO extenders and finished wiring up the switches to the Xiao ESP32-S3
I decided to use a matrix layout and 6x6

<img alt="image" src="https://github.com/user-attachments/assets/d60dc6f6-f78f-4e10-acaf-e83a9f994be1" />


# May 31st: Finished wiring up the audio DAC and the decoupling circuit - Started on the microsd card circuit

Today I finally finished wiring up the audio DAC to handle audio output to the headphone jack. This is one of the most challening things in the project as configuring each pin and wiring it to the correct circuit was very very tough. I started wiring the microsd card to the Xiao using SPI

![image](https://github.com/user-attachments/assets/4a86f23d-18b5-43f7-b395-b38d92c1aad7)
