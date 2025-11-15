--> Notes for making schematic and PCB design 
Schematic idea realtively understood --> juts need to go through the Kicad tutorials

For the writeup its clear on what to do as well as get the overleaf setup ready

Let's allocate the schematic and PCB to one day then the remainder will be the writeup
This should be clear since I have my example ready for my own setup as well as the layers

Notes: will need to change the MCU to support the USB as well as other considerations. That shouldn't necessarily be a major issue, but I can make changes where it is needed

Going to change the MCU to be **STM32WB55** so I can support USB. I think I can then keep most of the other things, maybe include some kind of system to include controlling stuff from the relays to trigger environmental switches 

# Breakdown
--> Need to get schematic, PCB and Write up Done

--> Schematic:
Already have the template for Neoair --> need to change MCU to stm32wb55, add USB, add or change fan/relay usage. Remaining components to be changed upcoming
PCB design --> to be considered -->

Let's focus on one at a time, PCB design secondary

## Schematic
--> First is the layout and setup
--> review schematic design video -- then can recreate the remaining from Neoair/ design changes

Lets give myself 5/6 hours for the schematic, then 6-8 hours for the PCB design. THe remaining can be deidcated to the writeup -- which should be easier since its from BS.

Might need to add a custom display unit -- or rather just have some kind of LCD controller instead lol

Another potentiall consideration is a USB to uart bridge --> this would make things a lot easier and allow me to use one device or another? This would be important for tracking data. I might actually go with this one after all :think: 

Ok will have to gamble and use the UART-USB bridge to get around this. That may make it more difficult, but I think its better in the long run lol

To get aroudn this, I might just have a way to connect USB directly, EFM32GG11 might be the system instead

I don't need to worry about wireless from the MCU -- I can have that connection instead from the ISM RF module

Ok, how about changing it so we can have USB power the system and talk to it over UART -- this will help developers who are debugging or testing the system entirely now
Some kind of CLI system -- I suppose this technically works lol. What else is the point of USB mane

Relays can be door locks or 2 factor door locking or some kind of system shutdown824013
Could use plant to show an example of the system entirely

If I can get this schematic done -- pcb should be easier to completet then the writeup should be as easy as pie

