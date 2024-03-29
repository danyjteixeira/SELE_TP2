# Asynchronous Communication System

Objective – Development of an asynchronous communication system composed by
several nodes (at least 1 master and 2 slaves). Those nodes have the same hardware
and should be based in the ATmega328P MCU and MAX485 transceivers.

Students must develop the schematic and the corresponding PCB for the nodes that
have in fact the same hardware and only differ in the firmware.
Students must also develop both versions of the firmware (master and slave) in C
language using the approach described in the slides, i.e. using a 9th bit for differentiating
the address and data frames (check chapter 19 - USART0, of the MCU datasheet).

Each node must have a LED connected to the MCU that will be used in the final
demonstration where the Master will switch each LED of the connected Slaves in a
sequential order. For that each node is addressed with a set of 4 DIP switches.
The solution can be tested using Arduino boards instead of the proposed nodes. 
