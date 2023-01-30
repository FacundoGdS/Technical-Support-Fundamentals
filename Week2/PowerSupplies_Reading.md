# Power Supplies (Supplementary reading)

In this reading, you will learn how to select the correct power supply for a personal computer (PC) to support the main components of the PC.

As you learned in a previous video, computer systems require a direct current (DC) of electricity to operate. However, power companies
deliver electricity in alternating currents (AC). AC power can damage the internal components of a computer. To solve this problem,
computer power supplies are used to convert the AC from the wall socket to DC. Power supplies also reduce the voltage delivered to the
computer’s internal components.

## Computer architecture

Computer architecture refers to the engineering design of computers and the interconnecting hardware components that together create computing devices that meet functional, performance and cost goals. Power supplies are part of the hardware layer of a computer’s architecture. You learned earlier about the other major hardware components of a computer’s architecture, including the motherboard, chipsets, CPUs, RAM, storage, peripherals, expansion slots and cards, etc. These components influence the size and type of power supply a computer needs.

## Selecting power supply

### Local input voltage

A main consideration when selecting a computer power supply is the voltage delivered to common wall sockets in your country. Power standards for input voltages can vary from country to country. The most common voltage inputs are 110-120 VAC and 220-240 VAC. VAC stands for volts of alternating current. 

**■ Voltages in the Americas**

North, Central, and parts of South America use the 110-127 VAC standard for common wall sockets. Computers and power supplies sold in these regions are designed to use this level of power. 

**■ Voltages for most of the world**

Most countries use the 220-240 VAC standard for common wall sockets. Computers and power supplies sold in these areas are designed to use this higher voltage.

Please visit [WorldStandards “Plug, socket & voltage by country”](https://www.worldstandards.eu/electricity/plug-voltage-by-country/) to find your country’s voltage standards.

1. Uruguay: C / F / L,	220 V,	50 Hz.
2. USA: A / B,	120 V,	60 Hz.

It is important to use the correct voltage power supply or power converter for the computer’s voltage specifications. Imagine that you have a customer who imported a PC from a country that uses a different standard for input voltage. You will need to adapt the input power to protect the computer. Some options for doing this might include:

- Replace the power supply with a unit that uses the appropriate voltage for the target country.
- Install a power supply model that includes a dual-voltage switch that can be toggled from 110-120VAC to 220-240VAC. 
- Plug the computer into an external power converter that then plugs into a normal wall socket. Power converters can be purchased from any store that sells international travel merchandise.

Without a power converter, the following problems may be experienced:

║-If a computers needs-║-But the wall socket delivers-║-The result will be-----------------------------------------------------║

║------220-240 V-------║----------110-120 V-----------║-not enough power for the computer to run properly--------------║

║------110-2120 V------║----------220-240 V-----------║too much power, which will damage the computer’s internal parts║

**Motherboard engineering specifications**

The motherboard and form factor specifications document will provide a list of compatible power supply types to help you select the correct part. The ATX form factor is the most common motherboard design for full-sized, personal desktop computers. You may also find a version of the ITX form factor in smaller computers. The form factor size and components embedded in the motherboards will create a starting point for the minimum power supply wattages required.

**Power consumption of components**

The number of internal components and peripherals the computer will need to support will also determine the minimum wattage a power supply must provide. For example, a basic computer that is designed for word processing and surfing the Internet should work with a standard power supply. However, some computers may need higher wattage power supplies to support items like a powerful CPU, multiple CPUs, multiple hard drives, video rendering applications, a top-tier graphics processing unit (GPU) for gaming, and more. 

**Voltages and pin connectors**

The internal hardware components of a computer require varied input voltages to operate. Voltage regulators embedded in the motherboard of the computer control the amount of power that is delivered to the computer’s various internal components. 

**Voltage-│-Examples of components that use each voltage level**

3.3V-│-DIMMs, chipsets, and some PCI/AGP cards

5V---│-SIMMS, disk drive logic, ISA, and some voltage regulators

12V-│-Motors and voltage regulators with high outputs

The computer’s power supply plugs into an adapter on the computer’s motherboard. The wiring for this connection uses color coded wires. Each wire color carries a different voltage of electricity to the motherboard or serves as a grounding wire. A standard ATX motherboard power adaptor has either 20-pins or 24-pins to connect these wires. The 20-pin design is an older technology. The 24-pin connector was developed to provide more power to support additional expansion cards, powerful CPUs, and more. The 24-pin connector has become the standard for today’s personal computer power supplies and motherboards. 

The power supply will have multiple connectors that plug into the motherboard, hard drives, and graphic cards. Each cable has a specific purpose and delivers the appropriate amount of electricity to the following parts:

Connections from a PC power supply (ATX 2)

1. Floppy disk drive (obsolete)
2. "Molex" universal (e.g. IDE hard drives, optical drives)
3. SATA drives
4. Graphics cards 8-pin, separable for 6-pin
5. Graphics cards 6-pin
6. Motherboard 8-pin
7. Motherboard P4 connector, can be combined to 8-pin mainboard connector 12V
8. ATX2 24-pin, divisible 20+4, and can therefore also be used for old 20-pin connections

You will learn how to install a power supply and connect these power cables later in this module.

## Key takeaways

When selecting a power supply for a computer, the following items should be taken into consideration:

1. Wall socket input voltage standard for the country where the computer will be used;
2. The number and power consumption needs of the computer’s internal components;
3. The motherboard model and form factor engineering specifications and requirements.

**Resources for more information**

- [“Plug, socket & voltage by country”](https://www.worldstandards.eu/electricity/plug-voltage-by-country/)List of countries around the world and their voltage standards for common wall sockets and plug types.
- [How to Diagnose and Replace a Failed PC Power Supply](https://www.wikihow.com/Diagnose-and-Replace-a-Failed-PC-Power-Supply)Step-by-step illustrated instructions on how to diagnose a power supply failure and replace it on a desktop PC.
