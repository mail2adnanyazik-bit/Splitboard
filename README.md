# Splitboard - a custom, built from scratch wireless corne split keyboard. Built for Stardance, to qualify for Outpost.

![](assets/img/2026-06-29-20-37-37.png)

Splitboard is a wireless split keyboard built by ME - Panda (also known as Adnan)

You see, my dad has had a dygma raise split keyboard since like 4 years, and i thought it looked REALLY cool, and wanted to get one -
till i saw the price - the thing was whopping **_200 DOLLARS_** ! So i thought to myself - why not build one myself ?

By the time this event rolled around, i was already getting tired of my very *anti-*ergonomic apple magic keyboard, and thought
that this project would be perfect, expecially cause of the experience with keyboards i got from the Hackpad mission.

That is how the **Splitboard** was born.

## Components :

Since this keyboard was made completely from scratch, i first will tell you whats its made of :

The Split Keyboard has 2 halves, with each having :

- 21 Keys (3x6 matrix with 3 thumb keys) - in the classic Corne layout
- One OLED (blue, since thats myt fav color)
- A supermini nrf52840 microcontroller - this is a cheap nice ! nano v2 clone, a wireless chip made excpecially with keyboards in mind
- A 110 mAh Battery (should last weeks with my setup)

So this is the Schematic with all mentioned components :

## Schematic :

![](assets/img/2026-06-29-20-48-11.png)

As you can see, i dont like wires :D

## PCB :

![](assets/img/2026-06-29-20-49-44.png)

The special thing about this PCB is, it is **_reversible_** - instead of having to design two seperate PCB's, i can simply
design ONE, and order it twice - i would just have to flip it over for the other half, and solder on the other side !

## Case :

For the case, i decided to use just two parts :

- ### A Case Bottom :

  This just holds the PCB and components for my keyboard

  ![](assets/img/2026-06-29-20-53-53.png)

- ### A Top Plate :
  This will be screwed on to the base, and has holes for the components that need to look out to poke out
  ![](assets/img/2026-06-29-20-55-49.png)

## Assembly :

There will be a such Bottom and Top for both halves of the keyboard, and it will then be assembled like this :

![](assets/img/2026-06-29-20-57-40.png)

Then Keycaps will be pressed on to the switches.

This will be done on both sides (I couldnt find a way to flip the PCB 3d model properly D:) :

![](assets/img/2026-06-29-20-59-36.png)

## Costs (BOM) :

I will buy everything except PCB from Aliexpress

2x supermini nrf52840 : 15 $
2x 110 mAh LiPo battery : 5 $
1N4148 SMD Diodes : 2 $
Kailh MX Hotswap sockets : ~ 7 $
42 x Cherry MX Switches : ~ 40 $
42 x Cherry MX Keycaps : 25 $
2 x 0.91" OLED Display : 6$
4.7kΩ SMD resistors : 1 $
100kΩ SMD resistors : 1$
SPST slide switches : 0.50 $
JST PH 2.0 2-pin connector (for battery) : 1 $
M2 standoffs + screws kit : 2 $
8mm self-adhesive bumpons (less glide) : 2 $
PCB from JLCPCB : 20 $
Shipping (Aliexpress and JLCPCB) : 15 $

Total : ~ 142.5

I would add another 15 - 20 dollar buffer since something is bound to go wrong, so in the end it would be around 160 dollars.
