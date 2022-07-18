# General  
**Task: Algorithm of operating ESP32**
>ESP32 is a microcontroller that has built-in Wi-Fi and dual-mode Bluetooth support. It can be programmed through various programming platforms. In this task, the algorithm for programming it on Arduino IDE will be mentioned.

***To operate ESP32 after linking the physical parts (sensors, LEDs, etc.), one can control them by programming***

## Programming ESP32 
For programming ESP32 board with Arduino IDE first step is to add ESP32 board support on Arduino IDE. For this follow the steps below:

1.	Before going to Arduino IDE make sure you have internet access in your computer.
2.	Open Arduino IDE go to “File” in menu bar and open “Preferences”.
3.	As “Preferences” dialog box opens, copy the URL in “Additional Board Manager URLs” box highlighted in image below. After this select “OK”.URL-   https://dl.espressif.com/dl/package_esp32_index.json
4.	Go to “Tools>Board>Board Manager”.
5.	In the Board Manager you can see certain download process going at the bottom of screen. Wait till this process gets completed. Once this process is completed search for “esp32” in search box.
6.	You can see the esp32 package in Board Manager select it and then select “Install”.
7.	Once installation starts wait for a while till installation process gets completed. As the process is completed you can see “INSTALLED” written beside esp32 board name.
8.	Close the Board Manager and go to “Tools > Board” and scroll down, there you can see a complete category of different esp32 boards under the name “ESP32 Arduino” written in grey colored fonts. In that select “ESP32 Dev Module” if you are using standard ESP32 board made by Espressif Systems or select   any other depending on which board you are using.
9.	After selecting esp32 board you can see the board name at the bottom right corner of your Arduino screen changes to board name selected by you. Beside board name you can see certain other parameters, this are mainly parameters related to the code upload process on esp32. You can change them from “Tools” in menu bar. 
10.	Go to “Tools>Port” and select the port available in the list and then upload the code.

