# FXChrony_M5STICK_PLUS

## Introduction

This repository contains the FX Chrony display code for the M5 Stick C Plus. The FX Chrony display is a simple and effective way to keep track of your shooting data in real-time. With this project, you can quickly and easily get started with using the M5 Stick C Plus to display important shooting information such as your shot velocity, shot count, and more.

Instructions to start with Arduino IDE 'https://docs.m5stack.com/en/quick_start/m5stickc/arduino'

# Setting up the Arduino IDE environment for M5StickC

## Step 1: Download and install the Arduino IDE
1. Download the latest version of the Arduino IDE from the official website: https://www.arduino.cc/en/software
2. Install the Arduino IDE on your computer

## Step 2: Add the ESP32 board manager URL
1. Start the Arduino IDE
2. Go to File -> Preferences
3. In the "Additional Boards Manager URLs" field, add the following URL: 'https://dl.espressif.com/dl/package_esp32_index.json'
4. Restart Arduino IDE


## Step 3: Install the ESP32 package
1. Go to Tools -> Board -> Boards Manager
2. Search for "esp32"
3. Install the "esp32 by Espressif Systems" package

## Step 4: Select the ESP32 Wrover Module board
1. Go to Tools -> Board -> M5Stack Arduino
2. Select "M5Stick-C-Plus"

## Step 5: Connect the M5StickC to your computer
1. Connect your M5StickC to your computer using a USB-C cable

## Step 6: Select the correct port
1. Go to Tools -> Port
2. Select the port that your M5StickC is connected to
   - On Windows: "COMx"
   - On Mac and Linux: "/dev/cu.usbserial-xxxxx"
   - On some Linux distributions: "/dev/ttyUSBx"

## Step 7 (optional): Upload the Blink example
1. Go to File -> Examples -> 01.Basics -> Blink
2. Click the Upload button (right arrow) to upload the sketch to your M5StickC

Your M5StickC should now be set up and ready to use with the Arduino IDE!



If you don't know how to clone a repository use this link to download zip 'https://github.com/DaystateRebel/FXChrony_M5STICK_PLUS/archive/refs/heads/main.zip' and open .ino file in Arduino IDE.

## Required Board Definitions

Before you can use this code, you need to have the M5 Stack board definitions installed in the Arduino IDE. To do this, follow these steps:

1. In the Arduino IDE, go to `File` > `Preferences`
2. Add `https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/arduino/package_m5stack_index.json` to the `Additional board manager URLS` field
3. Go to `Tools` > `Board` > `Boards manager`
4. Search for and install "M5Stack"
5. Go to `Tools` > `Board`
6. Select `M5Stick-C-Plus`

## Required Libraries

This project uses the M5StickCPlus and OpenFontRender libraries and M5-ENV 'https://github.com/m5stack/M5Unit-ENV/tree/master/src'. To install these libraries, follow these steps:

### M5StickCPlus

1. Go to `Sketch` > `Include Library` > `Manage Libraries`
2. Search for and install `M5StickCPlus`

### OpenFontRender

1. Download the Open Font Render library from [here](https://github.com/takkaO/OpenFontRender)
2. Click the green `Code` button to download the library
3. Go to `Sketch` > `Include Library` > `Add .Zip Library`
4. Choose the file you downloaded

With these steps completed, you should now have everything you need to start using this project. Happy coding!
