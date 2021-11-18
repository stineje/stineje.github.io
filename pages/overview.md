---
layout: page
title: Overview of Skywater Technology 130nm Process
description: Overview of construction of the Skywater Technology 130nm Process
---

Skywater Technology creates an open-source Process Design Kit (PDK)
that can be used to fabricate semiconductors for digital and/or analog
designs.  The ultimate goal here is to create a PDK that allows both
fabrication and understanding of the semiconductor process.  Because
it is free, this allows the creation of tools that are free and
open-source to proliferate the understanding of the process.

The Skywater Technology 130nm processor or SKY130 has 5 layers of
metal to allow routing.  It also allows a sixth layer called local
interconnect (li).  However, the li layer despite being close to the
transistors has a high amount of resistance and may be unsuitable for
some applications.

You can get the PDK at the following site.  While the SKY130 process
node and the PDK from which this open source release was derived have
been used to create many designs that have been successfully
manufactured commercially in significant quantities, the open source
PDK is not intended to be used for production settings at this current
time. It should be usable for doing test chips and initial design
verification (but this is not guaranteed).
[SKY130 PDK on GitHub](https://github.com/google/skywater-pdk)
[Google CodeSearch interface](https://cs.opensource.google/skywater-pdk)
[FOSS EDA Tools](https://foss-eda-tools.googlesource.com/skywater-pdk/)

## SKY130 Process Node

The SKY130 is a mature 180nm-130nm hybrid technology originally
developed internally by Cypress Semiconductor before being spun out
into SkyWater Technology and made accessible to general
industry. SkyWater and Google’s collaboration is now making this
technology accessible to everyone!

The SKY130 Process node technology stack consists of;

Support for internal 1.8V with 5.0V I/Os (operable at 2.5V)
- 1 level of local interconnect
- 5 levels of metal
- Is inductor-capable
- Has high sheet rho poly resistor
- Optional MiM capacitors
- Includes SONOS shrunken cell
- Supports 10V regulated supply
- HV extended-drain NMOS and PMOS

The SKY130 Process Node is an extremely flexible offering, including
many normally optional features as standard (features like the local
interconnect, SONOS functionality, MiM capacitors, and more). This
provides the designer with a wide range of flexibility in design
choices.

## About SkyWater Technology Foundry

SkyWater is a solely U.S.-based and U.S.-owned, DoD-accredited,
Trusted Foundry. Through its Technology Foundry model, SkyWater
provides custom design and development services, design IP, and volume
manufacturing for integrated circuits and micro devices. The Company’s
world-class operations and unique processing capabilities enable
mixed-signal CMOS, power, rad-hard and ROIC solutions. SkyWater’s
Innovation Engineering Services empower development of superconducting
and 3D ICs, along with carbon nanotube, photonic and MEMS
devices. SkyWater serves customers in growing markets such as
aerospace & defense, automotive, cloud & computing, consumer,
industrial, IoT and medical. For more information, please visit:
www.skywatertechnology.com/.

SkyWater is building from a long heritage in the microelectronics
industry. The SkyWater facility was originally established by
Minnesota based Control Data Corporation (CDC) in the 1980s. The CDC
fab was acquired by Cypress Semiconductor in 1991. During the Cypress
era, the facility was expanded and upgraded multiple times, keeping
pace with Moore's Law into the late 2000s and was known for being a
US-based production facility that was competitive with Asian-based
fabs. SkyWater spun-off from Cypress in 2017 with private equity
backing from Minnesota based Oxbow Industries.





