# TouchTub tutorial

## Introduction

_Background to usage. Skills required. Brief description about differences between versions_

## Construction guide

### Materials required
![](https://BaDoomUK.github.io/TouchTub/Photos/01.jpg "Materials required")
1. Battery Holder with JST connecter (3 x AAA) or 3.7V LiPo battery.
2. Plastic food container
3. Sticky-backed copper tape or sheet (sheet is best)
4. Bare Conductive Touch Board (you may also need to purchase a way of reading a microSD card)
5. Micro-USB cable (for programming the Touch Board)
6. Crocodile clip cable
7. 3.5mm Audio cable
8. Wowee slim (or similar battery powered speaker)
9. Velcro dots (or a similar adhesive)

### Tools required
![](https://BaDoomUK.github.io/TouchTub/Photos/13.jpg "Tools required")
1. Scissors or a circle cutter (you will also need a compass if using scissors)
2. Ruler

### Stage 1 - Making a touch sensitive surface

1. Orientate your chosen tupperware tub so that it is lid-down. 
2. Measure the diameter of the top surface of the selected tub.
![](https://BaDoomUK.github.io/TouchTub/Photos/14.jpg "2. Measure the diameter of the top surface of the selected tub.")
3. Using a circle cutter (optional) or a compass and scissors, cut a copper circle of diameter 4mm less than the total diameter.
![](https://BaDoomUK.github.io/TouchTub/Photos/15.jpg "3.Cut a copper circle of diameter 4mm less than the total diameter.")
![](https://BaDoomUK.github.io/TouchTub/Photos/16.jpg "3.Cut a copper circle of diameter 4mm less than the total diameter.")
4. Create a second copper circle with an additional rectangular copper tab.  Use the first circle you created to create a template for the second.
![](https://BaDoomUK.github.io/TouchTub/Photos/17.jpg "4. Create a second copper circle with an additional rectangular copper tab.")
5. Apply the copper circle (without the tab) to the tupperware tub. Peel back a small section of the backing (as shown). Position the circle centrally on the top of the tub. Stick the peeled away section to the tub, and smooth out.
![](https://BaDoomUK.github.io/TouchTub/Photos/18.jpg "5. Apply the copper circle (without the tab) to the tupperware tub.")
6. Apply the tabbed circle in a similar manner to the inside surface of the tub.
![](https://BaDoomUK.github.io/TouchTub/Photos/20.jpg "6. Apply the tabbed circle in a similar manner to the inside surface of the tub.")

### Stage 2 - Securing the other components
1. Insert the 3.5mm audio cable into the Wowee speaker (or equivalent) - this is to make sure you position your audio cable fits along with the speaker. Take this opportunity to plan where your speaker, battery and touchboard will go. Make sure you leave enough room to connect a crocodile clip to the electrode side of the Touch Board (on the right side in the picture below), and that you can access any controls on your chosen speaker. 
![](https://BaDoomUK.github.io/TouchTub/Photos/22.jpg "1. Plan your layout.")
2. Add some velcro dots (soft loop side) to the base of your speaker. Attach the (rough hook side) to these dots and secure the speaker to centre of the tub lid, ensuring that there is also enough room for the audio cable to sit inside the lid. 
![](https://BaDoomUK.github.io/TouchTub/Photos/24.jpg "2. Attach your speaker to the lid.")
3. Apply velcro pads to the battery holder and secure to the lid.
![](https://BaDoomUK.github.io/TouchTub/Photos/24.jpg "1. Attach your speaker to the lid.")
4. Apply velcro pads to the Touch Board in the positions shown.
5. Apply velcro pads to the Touch Board in the positions shown. _(This specific positioning is to allow for future soldering)_
6. Connect the battery to the Touch Board.
7. Connect the speaker cable to the speaker.
8. You may wish to stick down the excess cable.
9. Attach the crocodile clip to one of the electrode.
10. Connect the other clip to the copper tab on the inside of the tub. 

Your tub is now physically ready, but we need to upload the code. 

### Stage 3 - Prepare the Touch Board

In order to get the tub to behave in the intended manner, you will need to upload some instructions, or code to the Touch Board. 
To do this, you will need to install some additional sofware.
Follow the steps in the following tutorial 
https://www.bareconductive.com/make/setting-up-arduino-with-your-touch-board/
Once you have successfully followed the steps in the Bare Conductive tutorial, upload the following sketch (XXXXXXX).

If you would like to change the mp3 tracks, follow the instructions lifted here. 
https://www.bareconductive.com/make/changing-the-mp3s-on-the-micro-sd-card/

