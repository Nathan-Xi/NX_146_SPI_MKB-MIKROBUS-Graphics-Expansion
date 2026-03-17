# NX_146_SPI_MKB MIKROBUS™ Graphics Expansion Board
![image](https://github.com/Nathan-Xi/NX_146_SPI_MKB-MIKROBUS-Graphics-Expansion/blob/main/i3c_display_demo_cg.png)
**Thank you for noticing this project.**:blush:

This is an graphics expansion board designed for all MIKROBUS™ supported development boards! (but you can still use it for other general-purpose applications as it's just a 4-spi screen adapter board)

In **this** example SDK, I used an NXP FRDM-MCXA156 for demonstration.

## Parameters

**Display product name:** 鱼鹰光电DP146BT001-V12  
**Resolution:** 70×160  
**Display area size:** 1.46 inch  
**Touch:** capacitive  
**Screen IC:** NV3022  
**Touch panel IC:** CST08C  
**Interface:** 4-SPI (for display) & I2C (for touch panel)  
**ESD protection:** no  
**On-board external flash:** no  
**On-board cache:** no  

## Demos

### Demo 1: whiteboard

This demo turns the display into a whiteboard on which you can test the touch panel.✏️

The demo project (for MCUXpresso) was fully packed into a .zip called "whiteboard_demo.zip" (but of course you have to build and debug it by yourself)

### Demo 2: I3C temperature sensor data visualization

This demo is specific to the FRDM-MCXA156 development board.🔒

It uses the on-board MEMS temperature sensor (p3t1755) and reads it using the I3C bus.

## How to use the demos

The two demos are essential as they include the driver which the contributer had written (as this display acquires no existing driver).

If you want to port the driver to a new platform, please refer to Demo 1 as it included all you need for your custom project.
