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
[SKY130 PDK](https://github.com/google/skywater-pdk)