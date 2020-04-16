# mbed-tamarillo-F767
Drivers for Custom STM32F767 board for MBED5 

**WARNING - UNTESTED**

This is work in progress to allow use of MBED ecosystem with Innovodesigns custom STM32 board

After adding with *mbed add*, it's necessary to move or copy the custom_targets.json to the project root folder
'''
mbed add https://github.com/innovodesign/mbed-tamarillo-F767
cp mbed-tamarillo-F767/custom_targets.json .
mbed target tamarillo-F767
mbed compile
'''
