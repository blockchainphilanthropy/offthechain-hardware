# offthechain-hardware
Hardware POC for off the chain p2p wallet

Potential BOM:
-----------------------
Target 1.8V VDD:  
* nRF52840 as main processor chip
* USB-C? - CCG2 or CCG3? adds $1-3 to cost mini  
  USB-B micro and CCG2 designs available from Fyber Labs
* ST31 chip not needed with Cryptocell-310?
* SPI flash as big as budget will allow...
* LCD/interface similar but $3-5 in 1k: https://www.crystalfontz.com/product/cfa533tfhkl-uart-lcd-16x2-character  
    Best to use $2 LCD and add buttons on circuit behind panel
* MPPT charging - BQ25504? - BQ25570 likely for buck/boost
* Solar cell - cheaper? - https://www.digikey.com/product-detail/en/ixys/SLMD121H08L/SLMD121H08L-ND/3463125
* Power: replaceable NiMH 2xAAA  

Sub $20 EAU 1k.  Ideally < $10

unlikely($) optional features: sensors/accelerometers - BME680, LSM9DS1, i2s audio
