---
title: "KlipperHub"
author: "Aahil"
description: "A comapct all in one device to make your 3D printer smarter(with klipper)!"
created_at: "2025-07-12"
---

## July 12th: Did research and made the PCB and Schematic

Hi! I'm back with another project, so I recently purchased a printer, the Anycubic Kobra 2 Neo. But I rlly dont like the interface of it's firmware, the firmware was pretty basic asw with n options for PID, Input Shape Modelling, etc. So I thought, why not make a device to replace the 2 Neos screen? Which is why, I'm making this.

I also wanted to add some RGB LED Strips and a camera for monitoring and timelapses, so I decided to make a custom PCB with a Seeed Studio XIAO, a few JST Headers for RGB and the Pi's I2C, and a onboard RGB LED for print status and stuff.

The idea:
My idea is a Pi, on top of that we'll have a custom HAT, and on top of that, a 4.3" DSI touchscreen. Then I'll make a mount to fit the entire project on the same spot where the original LCD goes, I'll have everything vertical to avoid issues with the bed colliding with the screen. I'll also make a camera mount to slide into the printer's rail. I know I'm using a XIAO and not adding a custom ESP32 there but thats because I want to minimize error, I'll think of adding a S3 instead though.

So anyways, I yapped a bit too much but I am done with my schematic and PCB, for the PCB I picked up a template from [here](https://github.com/MisterHW/RPi5-HATplus) for the PCB to have the right cutouts and such. The rest was designed by me but I will add a bit more later.

<img width="714" height="548" alt="image" src="https://github.com/user-attachments/assets/78fdb53d-0bb9-490b-bc98-225cf51f3882" />
<img width="965" height="335" alt="image" src="https://github.com/user-attachments/assets/0ac0b3f4-c112-46a0-8b90-9ba5b4ec1732" />
