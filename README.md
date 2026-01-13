# SimSequentialShifter
Sim racing is expensive... too expensive...

So why not make a $100+ item myself! This is my sequential shifter. It doesn't have any extra buttons and only shifts up and down, but that's all you need, no?

<img src=assets/Final.png alt="PLACEHOLDER" width="400"/>


## Features:
- Custom handle grip and build
- dual spring system to simulate resistance and give a nice feel. It can be adjusted by tightening nuts at the end of each stud.
- Ball spring plungers to provide a tactile feeling, as well as keeping shifter in place while not shifting.

## CAD
Held together with m8 and m6 screws, m8 studs, and an m10 stud for the knob. This was my first time doing a pretty CAD-heavy task, so I'm happy with the result

<img src=assets/CAD.png alt="PLACEHOLDER" width="400"/>

### Assembly

1. Solder the wires to arduino and place it in the main body. There should be 2 raised walls at the bottom of the main body to place it.
2. After inserting the heat-set inserts, make sure to screw the knob into the stick using the smaller stud. 
3. Feed wires from the Arduino through the holder and then solder them to the micro switches. Then use the M6 screws + bolts to attach the holders for the micro switches to the main body, and adjust to your preferences after attaching the micro switches.
4. Use the M8 screws + nuts to attach the stick to the main body at the center of the main body, and then attach the M8 female rod ends with the same type of screw + nut.
5. Slide the longer rods through the holes on the tall part of the main body, then screwing that into the rod ends into the holes. 
6. Add a mould spring to each side and put an M8 nut on to secure, tighten to increase resistance.
7. Repeat 4 and 5 for the other side.
8. Just below the M8 hole for the center of rotation of the stick, there are 2 more about m5 holes. Insert the M5 heatsets and screw in the ball spring plungers until they fit into the crevice on either side of the stick.
9. Done! Enjoy racing!


I included all the files in the CAD folder. Make sure to make 2 micro switch holders.


## Wiring
No PCB for this project, as it would just be more work to use. Simple wiring from Arduino to the microcontroller is used instead. Make sure that the red wire is wired to the same wire slot as the button number in simhub.

<img src=Wiring/wire.png alt="PLACEHOLDER" width="400"/>


## Firmware/Coding
I'm using a tool for sim racing parts to do the programming for me, called SimHub. It will do everything for me and is fast and easy. Here is a video showing the process

https://youtu.be/XaHf5xkZWxY?si=bYvEh1Mwqx5HG9Xs&t=215

## BOM
<img width="628" height="385" alt="image" src="https://github.com/user-attachments/assets/039e8cc2-ea5f-452f-831e-e09a09252ddf" />

Links are included in the Excel sheet: https://1drv.ms/x/c/1d7c297793eee067/IQD1Y_XzaX3VSoLkiemuYFM1ARW1dW0mvp2L7T5ecIngENg?e=hQ6rAf
