The purpose and required operations of software need to be defined into specifications.

A Software concept can broken down into flow diagrams or software blocks. 

# Diagrams

## Flow Diagrams

**A** Flow diagram can depict, how a particular piece of software or algorithm should behave. Often it contains a same functional software contracts, such as conditional decisions and high level functions calls.

## Block Diagrams

Software **Block Diagrams** do not differ greatly from a hardware block diagram, you often see for circuit boards and micro-controllers. Instead, they depict how different blocks of code communicate and connect to one another. That being said, a Software Block Diagram can also depict a software system in layers.

## OS Based Design

An example of a typical software organisation can be seen with an OS-based design. This includes:
- Low-level device drivers
	- Interface to hardware layers
	- HAL - Hardware Abstraction Layer
- Boot-loader - Helps boot or start the system.
- Operating System
	- Abstracts High from Low Levels
	- Scheduling
	- Resource Management
- Middle-ware - Shared libraries that many software components use
- Applications - Higher level software users interact with.

# Bare-metal firmware
Writing code to direct the interface of the hardware is referred to as **bare-metal firmware**. 

This type of coding has a steep learning curve but allows for low level control.

A firmware engineer requires deep knowledge of the hardware, not only for configuration of the bare-metal but also for **hardware timing** and **limitations** related to their software design.

A software engineer's role will be to try and segment the hardware interface into something referred to as a **HAL or Hardware Abstraction Layer.**

By design this interface works as a module component but with a well defined interface. It allows software above the HAL layers become **platform independent** or agnostic to the specific hardware implementation, a concern layers, portable across platforms. (Like an API working with System Calls in an OS).

In general for each block in a block diagram, **you need to know what responsibilities each block is responsible for and how different blocks interface between one another.** This is especially important, the pieces that need to interact with the underlying hardware specs that affect the software design as we try to engineer the best solution. 

**Remember embedded systems are highly specialised with limited resources.** 

A common software block design method is called a component design. This is where we define small functional software blocks that have certain tasks. We define the interface mechanism and the specs that each modules need to adhere to. By doing this, you can build modulized software that is reusable across different systems, architectures and platforms. This will allow software developers to easily migrate certain software solutions without significant system changes.

**It is very important you understand that with this design paradigm, good interface definitions are a key for successful implementation.** Example components can be seen in the layers where a wireless control embedded system is built. There is a hardware firmware layer that controls peripheral hardware. There's an extracted interface to this layer that is hardware independent. Those are interface with some high level communication libraries, above that is a control library that utilises hardware interfaces.

# On-target testing
Historically, software engineers were dependent on the development of hardware systems. 

On-target testing is a term that refers to installing your code on to your particular embedded system instead of another.

New hardware developments techniques and system emulation provide quality resources for low level development. For example, development kits and SDKs that allow for us to rapidly prototype software. It not only enabled engineers to begin writing low level code or firmware but also provided them with the physical resources to test code on. 

# Development Tools
There are five main development tools that allow software engineers to get started on development and testing of their applications. 
- Simulators - software that imitates hardware behaviour without actual hardware.
- Emulators - The hardboard platform that imitates the operation of your intended system.
- Compilers - software that allows developers to pre-execute code for their intended architecture.
- Installers - a software-hardware combination that allows compiled executable programs to be installed onto a platform.
- Debuggers - a hardware-software solution that allows programmers to test and validate their executable programs. 

These tools are important because developing hardware takes time and it's expensive. The software engineer's role oftentimes will not only include the design of the software product but also software validation of the hardware platform.A complete hardware design and documentation usually finishes first, with software following.

These 5 tools make the job of the embedded software engineer easier. How? simulators and emulators will allow validation of design to occur before the arrival of hardware. 

Compilers, Installers and debuggers will provide a quick development of features for your embedded target, and an easy way to fix bugs.

