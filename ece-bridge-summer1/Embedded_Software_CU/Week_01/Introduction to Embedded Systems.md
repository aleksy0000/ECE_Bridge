"An Embedded System is a computerised system that is purpose built for its application."

# It's resources are limited:
- Processing
- Memory
- Peripherals
How they are limited depends on the use case of the embedded system.
# Architecture
The hardware is a combination of a processing core, and external circuits for the processor to interact with.

A software installer combines these two pieces by loading software image into the processor's memory. 

The main difference between an embedded system and a Server/General-Purpose PC is that those machines are designed to handle a wide variety of applications which are loaded in and out of memory while the embedded system is designed to do one thing very well with the application rarely being altered after development and installation.

The components of an embedded system are connected by a Printed Circuit Board (PCB). A PCB is a substrate with conductive wires, it interconnects many integrated circuits and passive developments that all have been soldered onto the board. The components include your processor and power converters. An external programmer is connected to the embedded systems processor, in order to install a target application into the internal memory.

Modern designs integrate an onboard debugger to simplify the development process. A host machine is responsible for developing, compiling, and coordinating the install which is equally as important as development of the system PCB itself. The host machine is where your software files live.

An embedded software engineer will focus in becoming an expert on the host development environment, the tools and most importantly, the processor.

# Micro controller vs Microprocessor
A micro-controller is a microprocessor with added functionality such as memory and peripheral hardware, the processor part of the micro-controller is called the CPU or the central processing unit. This is a piece of hardware that runs our software by fetching and executing assembling instructions for memory. These instructions perform maths and logic operations as well as coordinating data movement.

The CPU has many sub-components with many responsibilities. Many registers, general purpose and special purpose, store operations data and systems state.

An Arithmetic Logic Unit (ALU) performs the fundamental low level assembly operations, an interrupt controller coordinates a synchronous event request of the processor.

Lastly a debug interface is used to help troubleshoot installed programs.

The CPU and its subsystems interact with other micro-controller resources through one or more buses. A bus controller aids the processor in this data transmission between memory and peripherals. Memory holds data that we operate on as well as the program that we're executing. This data is stored in a combination of flash and Random Access Memory. A clock system provides synchronisations across all these components. Trip power management hardware is used for regulation and monitoring.

A variety of peripheral hardware maybe included in a micro controller. Some typical peripheral functionality you will see include communication, analog signal processing, input and output, timing and processor support.
