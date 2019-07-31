---
layout: post
title:  "Functions, modes and states"
date:   2019-07-31 10:51:17 +0200
categories: engineering
summary: "Practical framework for defining states and modes for complex systems."
---

Complex systems' specifications and design documents define their states and modes using plain language instead of formal specification methods. So it is necessary to have a practical approach for defining requirements to be incorporated into the functional definition of such systems.

##Definitions
* **State**: the overall condition of a system or a subsystem. May be related hierarchically. Are exclusive.
* **Status**: an indication from a system or subsystem as to its own determination of its state, mode and/or condition(s).
* **Mode**: the way in which functions are performed. Exist within states. May be exclusive or concurrent. Function execution related to modes.
* **Condition**: an attribute of the system at a particular point in time. May contribute to the derivation of a system's state, mode or transitions.
* **Function**: a capability, activity or basic operation of the system.
##Model diagram
![Model diagram](/assets/images/System-State-Function-Mode.png)
A system may be defined to exist in zero or more states. States may consist of zero or more substates. A mode may execute in one or more states. A function may be performed in one or more modes. The system must perform one or more functions. Functions may be decomposed further (not shown).

##References
* [A Practical Approach to State and Mode Definitions for the Specification and Design of Complex Systems, Michael Thomas EDWARDS, September 2003](http://ep.unisa.edu.au/artefact/file/download.php?file=113130&view=23326)

*This post was originally written on a previous blog experiment on 2014/04/04 13:34*
