# Mutli-Purpose-Keyboard-Controller


## Idea
I thought about what multi purpose Device could be usefull in my day to day life. Then ive got the idea to maybe build a stream deck kinda thing. But i didnt see a world, in which i would actively use that, but it would still be neat to have something like that. Then a wired controller came to my mind. I thought, that that was a great idea too. I also wanted to build like a small handheld console aswell. Then I thought about how cool it would be to have all those things in one. And that was the final outcome. This Device can switch modes from a steam deck, to a simple wired, handheld controller, that you can play games with on your pc and also a standalone console (as long as you give it power). 

## Hardware

I carefully picked Hardware Parts that would be cheap, but also fulfill the projects main idea and make it fun to use. 
#### Buttons
For the Buttons I chose keyboard buttons, because I thought they would give the Device a nice look and would make it feel like it actually was useable as a stream deck unlike if i would have used real controller Buttons. I also decided on a Middle Button for mode switching.
#### Joystick
I could have just kept 4 Buttons for Movement in minigames, that would later be played on the Device but I liked the idea of a seperate Joystick way better. It also balances the controller and makes it more symetrical.
#### LEDs
The LEDs I picked only for stylistic reasons. They could indicte in which mode the Device currently is in Binary (to allow for 4 modes) or maybe just indicate weather the device is active or recieved inputs.
#### OLED Display
I picked a screen last, because it would be the most expensive thing on the list, but i thought about how many new funtionalitys it would bring. It allows for a 128x64px display, which is able to show full on mini games. So i figured it'd be worth it.

## Design Files
### 3D Model
(.STEP file is STILL at "3d Model/Joy_Controller.step")
This is the finsihed Model of the entire Device. Only the key caps are missing but it'd make no real difference to add them in here anyway. See how the Controller still looks retro style while having plenty of functionality? I also lerned from previous designe flaws. that the hole for the usb c port must be big enough.
<img width="1478" height="867" alt="Full Model Picture" src="https://github.com/user-attachments/assets/81716264-8ed9-4065-bf33-c171aa844185" />

This Picture shows the inside of the Device. I wanted to keep everything modular and open. Thats why the display is very easily unpluggable aswell as the Joystick.
<img width="1455" height="934" alt="Model with Opened Case" src="https://github.com/user-attachments/assets/35c38c4d-38b4-4851-8f90-348991c7d814" />

### PCB
For the Schematic I inspired myself by the Hackpad from https://blueprint.hackclub.com/hackpad/index.md and added a horizontal 4 pin header for the joystick and a 5 pin header for the display. I first searched for a fitting Oled display and only then connected the correct pins because I found out, that they were no all pined out the same way.
<img width="1058" height="855" alt="Schematic Picture" src="https://github.com/user-attachments/assets/54d52f96-777d-4640-b29d-1dca75e35748" />

I first settled on the form of the device when I designed the actual PC. It all came together quite nicely. I later added the display and figured, that it could go above the rp2040 so i added the header above it.
<img width="1653" height="997" alt="PCB Picture" src="https://github.com/user-attachments/assets/ccf47cbc-f530-4756-bd87-55f64b92218a" />

## Software
### Modes
I decided on the following 3 modes:
#### Stream Deck
Press Buttons for quick actions such as copy/paste, activate a macro or activate an LED Strip around my desk, that is powered by my PC via USB A.
#### Controller
Control movement in any game on my PC, Laptop, Tablet or really any USB Keyboard-supported Device.
#### Console
Play games such as Tetris, Snake, etc. on the Device, powered by the RP2040 just by powering it using for example a power bank for quick play to go.
### To be continued
Well, for now i cant really show much more here until i actually build this thing. But thats not gonna be a real issue, since ive made some good experience with python, if you look at my profile.
