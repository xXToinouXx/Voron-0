Hello !

This tutorial explains how to flash your different cards so that they work together.

I used the Formbot kit I received in May 2025. The cards are :
  - SKR Pico V1
  - BTT Pi V1
  - Voron Display V0

I'm only going to talk about USB communication, as it's the simplest method and UART communication offers few advantages in my opinion.

What's more, the umbilical cable supplied with the kit is very stiff and ended up breaking.

I therefore opted for CAN BUS communication (as per Mepherotus' excellent guide), as the SKR Pico doesn't need a CAN USB adapter. So it's possible to do CANBUS for only $30-35.

Translated with DeepL.com (free version)
