This file describe the function of any part of the project.

# Main power supplier
Sheet: MainPowerSupplier.SchDoc

Provides the positive voltage to the isolated power supplier, necessary do the gate drive, and the +5V to
the logic circuits.

# Logic
Sheet: LogicCircuits.SchDoc

Provide:
1. The (if) necessary voltage level shift in the PWM / control signal (3.3V to 5V as HIGH LEVEL);
2. Erro memory (of each arm) and board disable. By JUMPER selection, one erro will disable all board, or
even the realys, or only it arm;
3. Manual reset of the error (only if the board is not actived by the control connections);
4. PWM inputs, control of the relays, board enable and external reset connections in an RJ45 standard. Plus
a extra conection HEADER erros identification;
5. Indication (LEDs) of the board status: power-on, actived, no-error or error in an speficic phase;

# Dead-time + interlock
Sheet: DeadTimeDriver_Leg.SchDoc

Provide:
1. The minimum dead-time to any arm of the inveter (configurable). It is used the inerent trigger
level of the gate input and a RC circuit plus DIODE to create a delay in only one transition;
2. The interlock (may be disable) between the HIGH SIDE and LOW SIDE group of transistors;

# Isolated power supplier
Sheet: GateDrivePowerSupply.SchDoc

Provide the isolated voltage to gate the transistores plus the +5V to the logic and protections circuits.

# Gate-drive + protections
Sheet: DriverAndProtection.SchDoc

Provide:
1. The fastest and stable way to drive TWO parallel transistors (MOSFETs) or single IGBTs on the
max frequency and load specification of the project;
2. The isolation of the "drive/PWM" signal and the return of the error signal and a local disable of
the gate circuit;
3. A error signal ACTIVE LOW by the protections and a HIGH SPEED memory, by two transistors;
4. FOUR protections to the transistores and gate circuit.

## Protection operation

Use a 2.5V reference voltage circuit and a comparator IC to provide the bellow protections:

1. **Low voltage gate driver**, included in the reference generator, it decrease the 2.5V refereve voltage NET until any comparation threshold, in the case of low voltage in the isolated power supply;
2. **Over temperature** use a analog output temperature sensor close to one transistor terminal;
3. **Over voltage** compare the scaled voltage of the current conduction terminal of the group of transistors (DRAIN-SOURCE or EMITTER-COLLECTOR;
4. **Over current** use the same measure of the *over voltage* protection in a different instant and scale, only a little time after the transistor turned-on. The time of this comparation is controlled by the PWM signal that disable this when is LOW and allow this protection some nanoseconds after the PWM goes HIGH, changing the scaled voltage. When the PWM is LOW the scaled voltage is ZERO to prevent the wrong protection trigger.

# Gate drive circuit
Sheet: GateDriveCircuit.SchDoc

Provide:
1. Integration of the gate driver with the transistors;
2. Quick removal of the charges of the gate in the MOSFETs transistores;
3. The drive of TWO transistors in parallel without oscilation;
4. Attenuation of the overshoot in the turn-on stage.

# Power
Sheet: MainPower.SchDoc

Provide:
1. The main conections of the DC links and transistores to create the desidered topology of study;
2. The capacitors conections and measurement points.

# Auxiliary
Sheet: Auxiliary.SchDoc

Provide TWO extra relays with them NO and NC connections.
