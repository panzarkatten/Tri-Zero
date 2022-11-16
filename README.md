# Voron V0.1 to Tri-Zero rebuild

## What is a Tri-Zero?
Basically its a Voron v0.1 but with three belted Z instead of a single motor with integrated leadscrew. 
More information about the project can be found here:

https://github.com/zruncho3d/tri-zero/


## Rendered mockup
<img src="/images/Tri-Zero.png"
     alt="Tri-Zero mockup"
     width="300px"
/>

## The victim
### V0.1885
<img src="/images/Voctua.jpg"
     alt="V0.1885"
     width="300px"
/>

## Parts

### Part list
- [x] 3x Nema17 39mm stepper motors
- [x] 3x ~500mm GT2 Belt
- [ ] 3x GT2 16T Pulleys
- [x] 2x MGN7H Linear rail
- [x] 1x MGN9C Linear rail
- [ ] 6x F623 Bearings
- [ ] 3x Spacers for bed
- [x] 1x MCU with minimum 5 drivers
- [x] 1x EBB36 CAN board
- [x] 1x U2C CAN interface
- [ ] 7x Nutbar for 1515 extrusions


### Motors
With regards to space and holding force 39mm Nema17 steppers was choosen. Ended up going with stepperonline motors from amazon.

https://www.amazon.se/gp/product/B07KZQ77VH

### MCU
In total 6 drivers will be needed, A, B, Z1, Z2, Z3 and E. Since I will be using a CAN toolhead board the MCU will only need 5 drivers. After some searching I landed on a used SKR 1.4 Turbo. It included 4xTMC2209 drivers and I have one extra from previous CAN conversion. 

### CAN
Will be using a ebb36 with an u2c from btt salvaged from my Trident.

BTT EBB36
https://lab4450.com/product/ebb36/

BTT U2C
https://lab4450.com/product/u2c/

### Rails
The Tri-Zero needs two extra MGN7H 150mm rails for the two extra Z. As recommended by the designer of the Tri-Zero the X rails will be upgraded to a MGN9C rail and the old one repurposed for Z. One additional MGN7H was bought.

MGHN7H  
https://lecktor.com/en/linear-rails/1146-robotdigg-mgn7h-rail-gcr15-150mm.html

MGN9C  
https://lecktor.com/en/voron-v01/1088-hiwin-mgn9c-150mm-01088.html

### MISC
Belts 
https://lecktor.com/en/v0-motion/779-gates-ll-2gt-timing-belt-6x3000mm-00779.html

### Filament
for this build I will be using ASA filament from 3DO. Base color will be anthracite and the accent ratrig green.

https://3do.eu/asa/581-881-asa-3do-asa-1kg-antracit.html#/33-colour-anthracite
https://3do.eu/asa/599-933-asa-3do-asa-1kg-ratrig-green.html#/123-colour-ratrig_green


### Cost

