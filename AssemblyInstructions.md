# Assembly Instructions

## Future Todos

- Take pictures of every step of the process to add to this guide.
- Replace Screenshots with equivalents from the final PCB layout.

## Soldering High Pin Density ICs

### Solder MCU (EFM8)

Using a zealous amount of flux, tin the centre thermal and ground pad followed by the surrounding pins. Pads must not have to much solder or pins will short.

Align the IC with the footprint on the board. The dot on the IC should match the cutout corner on the silk screen and should be on the top left corner when viewing the board from the front, with the keyboard at the bottom.

![MCU Footprint on board](/images/MCU%20On%20Board.png)

While using, flux and hot air to keep the solder liquid bring the IC over the pad and place onto solder. Remove hot air while still holding the IC, wait to allow the solder to cool then you may stop holding the IC.

### Solder Audio Amp (PAM8302A)

Tin and place a ball of solder on pin five of the footprint on the PCB, while using flux liberally (if your have the soldering iron in your right hand, otherwise pin 4 may be more desirable).

Align the IC with the footprint on the board silk screen. Once again the dot on the IC should be aligned with the top left corner of the footprint on the PCB when viewed from the front wit the keyboard at the bottom.

![Audio Amp](/images/Audio%20Amp.png)

While Heating the solder push the pin of the IC into the molten solder, making sure to align the IC with the footprint. Remove the head from the solder while holding the IC in place. Inspect the alignment of the IC and remelt the solder and adjust the alignment accordingly.

Solder the remaining pads by heating the pad and pin with the iron then adding solder. Remove excess solder using a soldering wick to prevent shorts.

## Resistors and Capacitors

Using capricious amount of flux tin one pad of the SMD footprint, push the SMD passive component into the molten solder, remove heat and allow solder to cool. Inspect alignment and adjust accordingly, solder the other pad.

Soldering in order:
- Resistors
- 0806 Capacitors
- Kemit B Capacitors
- Kemit C Capacitors

List of all SMD Passives, their component value and their SMD package size.

## Soldering VIAs

Poke a strand of fine steel wire through the via, solder the bottom side of the via, solder the top side of the via, trim excess wire and repeat for all other vias.

## Solder Battery Holders

Viewing the board from the bottom the pad on the left is the ground. Batteries are placed in series so the negative terminal of both battery holders should be at the left hand side of the holder.

Tin the left hand pad, push the negative battery terminal into the solder. Only solder one portion of the pad at a time taking use of the thermal relief. Ensure that the pin is well nested in the solder and that the pin is touching the board at the edge, to ensure that the battery holder fits in the case. Making sure the whole pin is buried well in the solder is important to ensuring the battery holder has a strong mechanical connection to the board.

## Solder Buttons

Solder the button starting from one of the pins not attached to the ground plane. Ensuring alignment and following the methodologies from earlier ensuring you use an un godly amount of flux.

## Through Hole

### Solder Slide Switch and Audio Jack

Ensuring the correct orientation of the Switch or audio jack insert it into the through hole from the bottom of the PCB, attach it to the PCB temporarily using electrical tape. Solder the pins by heating pad and pin then adding solder.

### Solder Speaker

**Warning speaker is small and magnetic and likes hot soldering irons**

### Soldering User Peripherals

- GPIO
- Debug
- Power
- Audio Volume Pot

## Fitting into case
