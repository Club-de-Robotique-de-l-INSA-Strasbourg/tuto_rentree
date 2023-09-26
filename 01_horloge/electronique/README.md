# Electronique

Dans cette partie nous retrouvons les pcb et les schémas pour la création d'une horloge

## Ce qu'il faut pour reproduire ce tuto

Logiciel : Proteus 8

Composants :

* Atmega238P-PU [produit](https://www.digikey.fr/fr/products/detail/microchip-technology/ATMEGA328-PU/2271026) [datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-7810-Automotive-Microcontrollers-ATmega328P_Datasheet.pdf)

* Afficheur 7 segments 4 digits [produit](https://www.digikey.fr/fr/products/detail/vishay-semiconductor-opto-division/TDCR1050M/4074708?utm_adgroup=General&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Zombie%20SKUs&utm_term=&productid=4074708) [datasheet](https://www.vishay.com/docs/83180/tdcx10x0m.pdf)

* 8 résistances $220 \Omega$

* 2 connecteurs SIL 8 pins
  Emmanuel
  coucou

## Programmation de l'atmega328P

![](https://camo.githubusercontent.com/c55beef2f138da61fe671a1e4a307ff4ffbc318d/68747470733a2f2f692e696d6775722e636f6d2f715849456368542e6a7067)

[Pin out atmega328P-PU](https://doc.riot-os.org/group__boards__atmega328p.html)



## Oscillateur atmega328P

L'Atmega possède un oscillateur interne de 8MHz, il n'est donc pas obligé d'en mettre un externe. (Dans l'Arduino UNO Rev3 il y a un oscillateur externe 16MHz).

Voici quelques liens qui en parlent :

* [Does an ATmega328P need a crystal oscillator while using ISP? - Quora](https://www.quora.com/Does-an-ATmega328P-need-a-crystal-oscillator-while-using-ISP-1) : Forum

* [Burning bootloader to ATMEGA328P without crystal - Microcontrollers - Arduino Forum](https://forum.arduino.cc/t/burning-bootloader-to-atmega328p-without-crystal/321749) : Forum arduino

* [True Atmega Standalone, Running Without Crystal Oscillator (Arduino) : 4 Steps - Instructables](https://www.instructables.com/Atmega-Standalone-Running-without-crystal-oscillat/) : Article sur la façon de faire tourner un atmega328P sans ocsillateur.

* [Arduino Without External Clock Crystal on ATmega328 - Hackster.io](https://www.hackster.io/techmirtz/arduino-without-external-clock-crystal-on-atmega328-d4fcc4)

* [How To Run Atmega 328,168,88,8 without XTAL, How to Burn bootloader on Atmega without crystal, xtal - YouTube](https://www.youtube.com/watch?v=xxjyhjUDRCY) : Vidéo sur comment rendre un atmega328P autonome 

* [Technoblogy - Using an ATmega328 without a crystal](http://www.technoblogy.com/show?1YO1)

* [GitHub - technoblogy/atmegabreadboard: For programming a stand-alone ATmega328 or ATmega168.](https://github.com/technoblogy/atmegabreadboard/tree/master)

* [Atmega328: Lose the Crystal and Gain Two Pins : 4 Steps - Instructables](https://www.instructables.com/22-Bit-Binary-Counter-for-Atmega328/)

* [arduino - Atmega Standalone, Running without crystal oscillator - Electrical Engineering Stack Exchange](https://electronics.stackexchange.com/questions/217762/atmega-standalone-running-without-crystal-oscillator)





## Modèle 3D

On peut exporter un modèle 3D du PCB pour faire un assemblage, pour ceci, suivre ce tuto : [Proteus PCB - Exporter un circuit imprimé vers une DAO 3D [Multipower - Education &amp; Pros] - YouTube](https://www.youtube.com/watch?v=rmB5Y-brIXQ) .
