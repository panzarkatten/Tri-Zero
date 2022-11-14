# Voron V0.1 to Tri-Zero rebuild

[[/images/Tri-Zero.png| Tri-zero mockup]]

Name: ??? He will get a new name with the rebuild

TODO: Link to projects github  
TODO: Create repo on github for this project  
TODO: Link to my github with this information  


## Parts

Parts list
https://github.com/zruncho3d/tri-zero/blob/main/PARTS.md

Procurment list:
- [x] 3x Nema17 39mm stepper motors
- [x] 3x ~500mm GT2 Belt
- [ ] 3x GT2 16T Pulleys
- [x] 1x MGN7H Linear rail (X rail replaced by MGN9C and old MGN7H rail also used for Z)
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


#¤¤ Cost

