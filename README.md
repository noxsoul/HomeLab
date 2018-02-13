# HomeLab
Small project to build a homelab server to host VMs and containers for coding development.

## The Hardware
I wanted a budget pc to host just a few virtual machines.  The pc should be able to handle just the basics: a source control system, automated build system and the development server (I.e. LEMP or something similar).  I also wanted to play with containers like Docker too.

### Parts List:
| Part | Description | Notes |
| --- | --- | --- |
| CPU | AMD Ryzen 5 1500X | |
| CPU Heatsink | Noctua NH-L9x65 | Love noctua and like things quiet!!! | |
| Mainboard | Gigabyte GA-B350N-Gaming Wifi | |
| RAM | Ballistix Sport LT 16GB Kit (8GBx2) DDR4 2400 | |
| Power supply | Seasonic FOCUS FM series 550w (SSR-550FM) | Big fan of seasonic too |
| Video Card | MSI Computer Video Card GT 710 2GD3H LP | Needed dedicated card for just setup |
| Hard drive | WD Blue 3D NAND 250GB | Old hard drive but will work for now |
| Case | BitFenix Mini-ITX Tower Case, Arctic White BFC-PRO-300-WWXKW-RP | |
| Fan splitter cable | JBtek All Black Sleeved PWM Fan Splitter Cable | Needed this after seeing case had 2 fans and mainboard had only1 system fan header |

## The Build
The build went pretty smooth since there really isn't too much to this computer.  I had a couple small items that needed to be addressed and will outline below some of the pictures.

![CPU and memory install](https://raw.githubusercontent.com/noxsoul/HomeLab/master/assets/homelab-002.jpg)
Installed the cpu, heatsink with arctic silver and the memory onto the mainboard. Made sure the fins of the heatsink were in-line with the system fan to distribute the heat better.  Noctua came with mounting brackets that would allow the fins to align either way.

![Power supply mounted in case](https://raw.githubusercontent.com/noxsoul/HomeLab/master/assets/homelab-006.jpg)
Mounted the power supply into the case. Had no issues at all with this.

![Mounted mainboard into case](https://raw.githubusercontent.com/noxsoul/HomeLab/master/assets/homelab-009.jpg)
Mounting the mini-ITX mainboard with cpu and heatsink was a little tight, but still was able to get into the case with no issues.

![Mounted video card into case](https://raw.githubusercontent.com/noxsoul/HomeLab/master/assets/homelab-011.jpg)
Mounting the video card was easy, especially since this is a no-frills card to begin with.  Only need this for initial setup and if any issues with remote connection from development machine.

I finally mounted the hard drive last and was ready for test 2.  I did do a test with all the components before installing them in the case just to make sure the parts were working.

**NOTE:** I had to get a fam splitter cable because the mini-ITX mainboard only has one system fan header and the case had 2 system fans.  A simple fix but if I had any more than 2 system fans, would have needed a dedicated fan controller.
