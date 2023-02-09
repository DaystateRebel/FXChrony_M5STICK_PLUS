# FXChrony_M5STICK_PLUS

## Introduction

This repository contains the FX Chrony display code for the M5 Stick C Plus. The FX Chrony display is a simple and effective way to keep track of your shooting data in real-time. With this project, you can quickly and easily get started with using the M5 Stick C Plus to display important shooting information such as your shot velocity, shot count, and more.

Instructions to start with Arduino IDE 'https://discord.com/channels/1053770249582936104/1073126480164433960/1073126893370482689'

## Required Board Definitions

Before you can use this code, you need to have the M5 Stack board definitions installed in the Arduino IDE. To do this, follow these steps:

1. In the Arduino IDE, go to `File` > `Preferences`
2. Add `https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/arduino/package_m5stack_index.json` to the `Additional board manager URLS` field
3. Go to `Tools` > `Board` > `Boards manager`
4. Search for and install "M5Stack"
5. Go to `Tools` > `Board`
6. Select `M5Stick-C-Plus`

## Required Libraries

This project uses the M5StickCPlus and OpenFontRender libraries. To install these libraries, follow these steps:

### M5StickCPlus

1. Go to `Sketch` > `Include Library` > `Manage Libraries`
2. Search for and install `M5StickCPlus`

### OpenFontRender

1. Download the Open Font Render library from [here](https://github.com/takkaO/OpenFontRender)
2. Click the green `Code` button to download the library
3. Go to `Sketch` > `Include Library` > `Add .Zip Library`
4. Choose the file you downloaded

With these steps completed, you should now have everything you need to start using this project. Happy coding!
