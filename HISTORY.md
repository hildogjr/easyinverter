History of the first develop step of each part of the inverter until get a complet inverter.

# 2017-06-13

**Folder:** 2017-06-13 Logics only prototype [HGJr]

**Images:** "2017-06-29 Logic (bottom).jpg" & "2017-06-29 Logic (top).jpg"

## Improvements did

1. Improved the main power supply layout to reduce the size and improve EMI.

# 2017-06-01

**Folder:** 2017-06-01 One phase  [FSG] (with errors)

**Images:** "2017-06-27 One phase 3.jpg" & "2017-08-06 One phase 3.jpg"

Optimized layout of one arm including the snubber gate circuit. Optimized the current protection logic by Hildo, Joel and Fellipe.

Layout by Fellipe.

## Improvements did

1. Changed the optical isolator Si8421Ad to Si8422;
2. Reduce the size;
3. Top silk and footprints in standards to facture production;
4. Calibrated the gate snubber circuit component values (not in this schematic, updated to next version).
5. Changed the gate drive MIC4420 + AND gate 74HCT1G08 to the ???? gate drive with schmitt trigger input and enable terminal (not in this schematic, updated to next version).

## Diagnosed erros / warnings

1. Replaced the input pair 8-9 and 10-11. Correted in tests by wires;
2. High interference.
Tested up to 100V, 100KHz.

# 2017-05-17
**Images:** "Supplier (bottom).jpg" & "Supplier (top).jpg"
Tested the main power supply to provide energy to all the board in final project. Use the automotive IC LM25011.
Layout recomended by the manufacturer.

# 2017-03-13

**Folder:** "2017-03-13 One phase prototype [HGJr]"

**Images:** "2017-04-28 One phase 2 (bottom).jpg" & "2017-04-28 One phase 2 (top).jpg"

One arm inverter prototype, isolated source + protections + gate drive.
Layout by Hildo.

Testes up to 200V of DC link with 150kHz and 5A. With lest voltage, tested with high frequency, 300kHz.

It was necessary add some extra gate ("snubber") circuit to avoid the voltage overshoot in the transistor turn-on.

## Improvements did

1. Tested the Si8421 IC isolator (LOW default output) at the plae of Si8422 (HIGH default ouput). Diagnosed a problem when this IC burn, may drive on the transistors. This correction was not included in the layout;
2. Better isloated supply layout (the data pins are exchanged).

# 2017-04-03

**Images:** "One phase (bottom).jpg" & "One phase (top).jpg"

First version of one arm of the inverter. Protections does not worked.

Layout by Arthur.

# 2016-10-05

**Images:** "2016-10-05 Isolated supplier 2 (bottom).jpg" & "2016-10-05 Isolated supplier 2 (top).jpg"

Improved layout by Fellipe, Arthur and Hildo.

# 2016-10-01

**Image:** "2016-10-01 Isolated supplier 1.jpg"

Isolated power supplier to the gate drivers tested and working at 400kHz. It will be used as gate driver power source.

Schematic by Fellipe and layout by Arthur.
