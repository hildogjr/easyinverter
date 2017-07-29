# easyInverter
## An academic modular 4 arms inverter focused to use in researches

Initial development by Power Conditioning Laboratory (*[Laboratório de Condicionamento da Energia Elétrica](http://www.fee.unicamp.br/dse/antenor/lcee)*) at [University of Campinas](http://www.fee.unicamp.br/?language=en) ([**UNICAMP Brazil**](http://www.unicamp.br/unicamp/english)).

The use of this poject is free and conditioned to GNU General Propose License 3.0.

The publication of academics works contend results using this project if conditioned to a ACKNOLEGMENT and citation of this repository in the "acknolegment part" of the article/paper.

## Early bird members
- Hildo Guillardi Júnior (GUILLARDI JR., H.);
- Joel Filipe Guerreiro (GUERREIRO, J. F.);
- Fellipe Saldanha Garcia (GARCIA, F. S.);
- Arthur Crisóstomo Prates (PRATES, A. C.);
- José Antenor Pomilio (POMILIO, J. A.).

## Max values (limitation) / general specifications
The specification values are not necessary concomitant.

- 10kW processing power;
- 600V of DC link;
- 50A in one phase;
- 200kHz switching frequency;
- 3.3V or 5V input logic control;
- Min dead-time & phase transistors interlock onboard;
- TWO extra relays;
- SMD topology with TO-247 transistor to easy replacement.

## Previst powers proposes (look in power limitations)
1. 800V/10A -> To invertes grid conected aplications, motor control;
2. 400V/30A -> To invertes grid conected aplications, motor control;
3. 100V/100A -> DC/DC converters.

## Previst uses, studies of
1. DC/DC convertes, e.g., boost, buck, buck-boost, push-pull;
2. Power switching supplies, isolated topologies based on DC/DC convertes;
3. Resonant converters;
4. Single-phase inverter, using the two fisrt arms. Possibility to use the 3rd arm to synchonous connection to the grid and 4th to DC link boost/pre-load/discharge (discharge, pre-load and connection may be also performade by the two relays);
5. Three-phase inverter three wire connection. With possibility of extra arm to pre-load/discharge of the DC link, DC/DC boost or any extra aplication conected to the same DC link;
6. Three-phase inverter four wire connection (three-phase plus neutral);
7. Single-phase back-to-back inverter (to three-phase is necessary use two boards);
8. DOUBLE isolated single-phase inverters (independent DC links), to use as multilevel inverter aplications.
