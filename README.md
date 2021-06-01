# pedalinio-18-footswitches-prototype.  


I created this repository to share my experience of creating my prototype of the open source [pedalino mini project](https://github.com/alf45tar/PedalinoMini). I am also sharing in this repository the files I created along the way.
It was a great experience and journey. I think I spent the same amount I would have spent if I bought it in a store but !! I LEARNT A LOT :
- I discovered and learnt to use GitHub
- I discovered what happened in the last 25 years with microcontrollers. I used to program in assembler.. (incredible)
- I learnt somehow to use arduino and visual studio
- I learnt to design in FUSION 360 !! that software is free !! - PCBs and the entire project.
- I did PCBs again and instead of DIY at home, I learnt how to buy them in China. What a change !
- I did my first 3D print ever. I was wondering what 3D printing is really for. I discovered a new world.
- I discovered how cheap things are in AliExpress :) - no more amazon

Here are 3 pics of the end result:
![Pic1](https://github.com/juani13973/pedalinio-18-footswitches-prototype/blob/main/images/pic%204%20-%20Final.JPG)
![Pic2](https://github.com/juani13973/pedalinio-18-footswitches-prototype/blob/main/images/pic%205%20-%20Final.JPG)
![Pic3](https://github.com/juani13973/pedalinio-18-footswitches-prototype/blob/main/images/pic%206%20-%20Final.JPG)

# My prototype
My prototype has the following features:
- USBMidi interphase that I wanted because my Bluetooth connection used to disconnect on my iPad.
- 18 footswitches leveraging 3 interphases out of the 6 available (6 footswtich ladder configuration)
- 3 external analog interphases leveraging the remaining 3 configuration.
- 18 2812b leds, one for each footswitch.
- LCD display.
- Externalized boot switch to select the profiles A/B/C. For this reason, I am using the 38pin DOIT ESP32 dev board instead of the 30-pins DEV board. (The boot button is in the GPIO-0)
- The mainboard PCB also has pins-out to connect the legacy-midi interphases (circuit to be built in another PCB)


# Fusion 360
Please refer to the [folder Fusion 360](https://github.com/juani13973/pedalinio-18-footswitches-prototype/tree/main/Fusion%20360%20files) to get the files and see how I designed the prototype.
In this section I included some tips on how I thought the construction.

# Creating the prototype
Please refer to the [folder Fusion 360 export files for production](https://github.com/juani13973/pedalinio-18-footswitches-prototype/tree/main/Fusion%20360%20export%20files%20for%20production) to download the files to request the production of the different parts.
In this section I also included some links to some of the components I used.

I hope this information is useful to you and do not hesitate to raise questions for clarification. I will try to answer as soon as I can.
All the best, juani13973
