# Edgeverter
**An academic budget cost modular 4 arms inverter focused to use in researches**

Initial development by Power Conditioning Laboratory (*[Laboratório de Condicionamento da Energia Elétrica](http://www.fee.unicamp.br/dse/antenor/lcee)*), [School of Electrical and Computer Engineering](http://www.fee.unicamp.br/?language=en), at University of Campinas ([**UNICAMP Brazil**](http://www.unicamp.br/unicamp/english)).

The use of this project is free and conditioned to GNU General Propose License 3.0. The financial support was provide by São Paulo Research Foundation (FAPESP) under grants 2014/11720-7 and 2015/02325-0.

The publication of academics works contend results using this project if conditioned to a ACKNOWLEDGMENT and citation of this repository in the "acknowledgment part" of the article/paper.

You may use this text:
"The authors are grateful to the edgeverter's work team by the inverter project, which is available at <<https://github.com/hildogjr/easyInverter>>"

The original [schematic and PCB file](https://github.com/hildogjr/easyInverter/tree/master/Altium%20prj) are in [Altium 16](http://www.altium.com/), the GERBERs and schematic PDF are provided in the [Assemblies folder](https://github.com/hildogjr/easyInverter/tree/master/Assemblies).

---

## Max values (limitation) / general specifications
The specification values are not necessary concomitant.

- 10kW processing power;
- 600V of DC link;
- 50A in one phase;
- 200kHz switching frequency;
- 3.3V or 5V input logic control;
- Min dead-time & phase transistors interlock on-board;
- TWO extra relays;
- SMD topology with TO-247 transistor to easy replacement;
- Isolated power supplier to the gate driver (it not depends of PWM to works fine);
- Protection: under voltage of the isolated supplier (gate driver), over current, over voltage on the group of transistors and over temperature.

## Predicted powers proposes (look in power limitations)
1. 800V/10A -> To inverters grid connected applications, motor control;
2. 400V/30A -> To inverters grid connected applications, motor control;
3. 100V/100A -> DC/DC converters.

## Predicted uses, studies of
1. DC/DC converters, e.g., boost, buck, buck-boost, push-pull;
2. Power switching supplies, isolated topologies based on DC/DC converters;
3. Resonant converters;
4. Single-phase inverter, using the two first arms. Possibility to use the 3rd arm to synchronous connection to the grid and 4th to DC link boost/pre-load/discharge (discharge, pre-load and connection may be also performed by the two relays);
5. Three-phase inverter three wire connection. With possibility of extra arm to pre-load/discharge of the DC link, DC/DC boost or any extra application connected to the same DC link;
6. Three-phase inverter four wire connection (three-phase plus neutral);
7. Single-phase back-to-back inverter (to three-phase is necessary use two boards);
8. DOUBLE isolated single-phase inverters (independent DC links), to use as multilevel inverter applications;
9. Three-phase Vienna rectifier.
