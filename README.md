Abstract
In recent years, the interest for connecting small devices such as sensors or embedded systems into an existing
network infrastructure (such as the global Internet) has steadily increased.
Such devices often have very limited CPU and memory resources and may not be able to run an instance of the
TCP/IP protocol suite.
This document describes how to use the uIP TCP/IP stack, written by Adam Dunkels, on LEGO’s RCX
Mindstorm platform, a very small device / toy powered by a h8300 Hitachi microcontroller with very limited
RAM (32K) and processing power. Still, it is powerful enough to run alternative operating systems such as
LegOS or even a tiny Java VM as a replacement of the original firmware. The advanced user is usually not
satisfied with the original firmware due to its extremely limited capabilities in terms of executing complex code
and the very limited number of variables.
The uIP TCP/IP stack is intended for embedded systems running on low-end 8 or 16-bit microcontrollers. The
code size of uIP is an order of a magnitude smaller than similar generic TCP/IP stacks available today.
The uIP code and an up-to-date version of the uIP documentation can be downloaded from the uIP homepage
maintained by Adam Dunkels. 
