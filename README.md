# MineFX
## About
- MineFx is a Minecraft styled 3d isometric renderer for the FxCp400 (Casio ClassPad II)
  
## Installation:
- You can simply download the last release. You can choose to download the ```.bin``` and ```.hkk```, it doesn't really matter — but the ```.bin``` is prefered...

- If you haven't already installed hollyhock-2 on your calculator install it.

- Then you just simply drag the downloaded file into the plugged in calculators folder

- And finished! Now you have MineFx on your fx cp 400!

## Controls?
![controls](assets/minefx_controls.png)
(A little extra secret: press `=` to reset the cursor position)

## Build it!

- Install WSL 2 (recommended is ubuntu)

- Just compile the sh4 compiler and add newlib (if needed look at the guide on the hollyhock-2 github)

- download the hollyhock-2 repository and go into the app_template folder

- now use the ```Makefile``` from this repository and replace the default on with it (the one in the app_template dir)

- and if you set everything right up you'll now be able to run ```make``` and compile MineFx

- What to do now?
- ###  HAVE FUN!

## Things to be implemented:
- [x] Destroy system
- [X] World save & load system
- [x] Place system
- [ ] Better Controls
- [ ] Interation system
- [ ] More Blocks (also special like: chests)
- [ ] Entity system
- [ ] Chunk generation

