# E-Stick-V3   
### Now Order Online Best Quality PCB+Assembly from Just $2 for 1-8 Layer PCBs, get JLCPCB $60 new user coupons https://jlcpcb.com/HAR Order Now.
    
## Language Selection:
[English](https://github.com/Knockoi/E-STICK-V2/blob/main/README.md) | [日本語](https://github.com/Knockoi/E-STICK-V2/blob/main/ReadmeJP.md) | [繁體中文](https://github.com/Knockoi/E-STICK-V2/blob/main/ReadmeTC.md)  

  
## Trailer Video  
Act I: https://www.youtube.com/watch?v=njI8RSczQoE  
Beta Bliud: https://youtu.be/r_apQx48-lI  
  ## Acknowledgments  
I would like to express my sincere thanks to JLCPCB for their support and sponsorship of this project, without which I would not have been able to complete this project. Without the help of JLCPCB, I would not have been able to complete this project successfully, not only did JLCPCB provide me with the printed circuit boards for my project, but the quality of their PCBs was very good, which fully met the requirements of my project. Once again, I would like to express my sincere thanks to JLCPCB for their support, which means a lot to me as I continue to work hard on this project and create more valuable works. Thanks to JLCPCB, my path of creation has become smoother.      
JLCPCB is a leading PCB manufacturer known for its superior quality, fast turnaround time and affordability. The company's commitment to precision and adherence to industry standards ensures high quality PCBs. JLCPCB caters to global customers with its user-friendly platform, transparent pricing and comprehensive services including assembly options. Its efficient processes and fast manufacturing make it an ideal choice for projects with tight deadlines. Overall, JLCPCB is a reliable and cost-effective solution for a wide range of engineering and innovation needs.  
    
## Overview  
This birthday gift was specially designed for my elementary school teacher to maximize the utility of the projector. It has a wireless mouse function, so I can control the projector easily without going back to my computer.
It also has a laser function for easy labeling of important content. For added convenience, we added a gyroscope function that allows me to move the mouse via somatosensory movement, and added directional buttons for more precise positioning of the mouse.
For an even better experience, the gyroscope also enables Apple Pencil-like functionality, allowing the E-Stick to draw or write on the projection screen. Currently, the E-Stick has these features and others are being developed.  
  ![image](https://github.com/Knockoi/E-STICK-V2/blob/main/Image/E-Stick.png)
  
## Hardware  
- The MCU uses ESP32-C3-MINI-1 for the small space module version.
- The gyroscope uses the MPU6500 data cable with two SDAs and SCKs.
- Power management using IP5305 highly integrated mobile power charging IC.
- RGB display for current mode and system information.  

## Functions  
- Electronic Pen: Can be connected to a computer to draw on the projection screen without connecting to the projector.
- Laser Pointer: E-Stick has a laser pointer on the top to mark key areas.
- Switching Pages: Use the customizable buttons on the left and right buttons to turn pages.
- Mouse Function: The mouse position of the left and right buttons can be manipulated by using the joystick and the physical sensors.
- Motion Control: Physical shaking is used to move the mouse position.
- Customize Keys: Use Bluetooth to connect to your phone or computer to change the E-Stick's key functions.
  
## Key Functions  
- Left button Same function as left mouse button, can be customized by mode button.
- Right button Same function as right mouse button, can be customized with mode button.
- Joystick You can move freely, default is mouse move (Spotlight move).
- MODE key can change the mode. Press and hold >= 5 seconds to enable Bluetooth connection.
- BOOT button Download button. Press and hold Boot, then press Reset to activate the firmware download mode and download the firmware through the serial port.
- RESET button Press this button to reboot the system.
- On/Off Button Press the button to turn on the system if the duration of the button is longer than 30ms but less than 2s. Pressing the button twice in a row within 1s is recognized as OFF.
    
The basic buttons can be found in the ESP32-C3-DevKitM-1.
