---
layout: single
title:  "We Have Moved: More Room for Autogyros, Avionics and Everything in Between"
categories: Company
tags: ThunderFly Workshop Manufacturing
excerpt: "From a 40 m² workshop with PCB assembly in another building to 160 m² with everything under one roof, and room for a separate workstation for each stage of development and production."
author: dusan-jansky
toc: true
toc_sticky: true
header:
  teaser: /assets/images/posts/new-premises/TODO-electronics.jpg
---

<!--
DRAFT NOTES (delete before publishing)
Facts to fill in:
  - who did the move / how long it took / any funny moment
  - the real workstation layout (the list below is a guess based on what we make)
Photos to take (interior only, save to /assets/images/posts/new-premises/):
  - old workshop "before" (a crowded desk, the old PCB assembly room)
  - development bench, PCB assembly, test bench, 3D printers, packing corner
  - team photo in the new space
-->

In 2026 ThunderFly moved to larger premises. Development and testing used to share about 40 m², and PCB assembly had a space of its own elsewhere. Now everything is together in 160 m². This post explains what that changes.

## What we make



**REVIEW start**{: .notice--info}


[ThunderFly](https://www.thunderfly.cz/) started as an attempt to build an autogyro drone that keeps flying when the weather grounds multicopters. The [TF-G1](https://www.thunderfly.cz/) and the smaller [TF-G2](https://github.com/ThunderFly-aerospace/TF-G2) came out of that work. While building them we kept designing small parts the autopilot needed. Today most of what we make is not autogyros.

**REVIEW end**{: .notice--info}


Our [documentation site](https://docs.thunderfly.cz/) lists more than twenty avionics modules, and each one has to be built, tested, labelled and shipped. Some examples:

- [TFGPS01](https://github.com/ThunderFly-aerospace/TFGPS01), an RTK-capable GNSS module
- [TFSIK01](https://github.com/ThunderFly-aerospace/TFSIK01) telemetry radios
- [TFRPM01](https://github.com/ThunderFly-aerospace/TFRPM01) RPM sensors for rotors, propellers and wheels
- airspeed sensors, I²C expanders, servo controllers, ESCs and [cable sets](https://github.com/ThunderFly-aerospace/TFCAB01)
- the [TF-ATMON](https://github.com/ThunderFly-aerospace/TFUNIPAYLOAD01) platform for atmospheric measurements

  




  
**REVIEW start**{: .notice--warning}

At the same time we are developing new aircraft: the sub-250 g [TF-G250](https://github.com/ThunderFly-aerospace/TF-G250) autogyro for profiling the lower atmosphere alongside radiosondes, a [UAV conversion of the LA500](https://github.com/ThunderFly-aerospace/LA500) RC autogyro, and the low-cost [TF-A1](https://github.com/ThunderFly-aerospace/TF-A1) fixed-wing aircraft.


**REVIEW end**{: .notice--warning}

We design, assemble and test all of it ourselves. Until now, though, not under one roof.

## PCB assembly in another building

Our main workshop was about 40 m², and development and testing filled it. There was no room left for PCB assembly, so it had a separate space in another building.

As a result, a typical module went through both buildings more than once. Bare boards were assembled in one, carried to the other for programming and testing, and back again whenever a board needed rework. Prototypes were the worst case: a design change in the morning meant a walk to the assembly room, a wait, and a walk back before anyone could find out whether the change worked.

**TODO:** a concrete example, e.g. how long one prototype iteration of a module took, or a board that was forgotten in the other building.
{: .notice--info}
 
In the new 160 m² PCB assembly is a few steps from the test bench. Nobody carries boxes of boards between buildings any more, and a prototype should be possible to assemble, flash and test in one afternoon.

![The old workshop](/assets/images/posts/new-premises/TODO-old-workshop.jpg)
 **pridat fotku stareho stanoviste**
## A workstation for each stage

The extra space also lets us organise the work. In the old workshop the same desk was used to prototype a new board, assemble a production batch and pack an order, depending on what was most urgent that day. Each change meant clearing the desk and setting it up again.

We are still unpacking and finding out which layout works best, but we aim to give development and production separate workstations:

<!-- Adjust to the real layout. One photo per workstation works well. -->

**Development.** Prototyping of new electronics and airframes. A half-built product should be able to stay on the bench for a week without getting in anyone's way.

**PCB assembly.** Assembly and rework of boards, from single prototypes to production batches.

**Module assembly.** Putting finished boards into enclosures, screwing modules together and fitting connectors.

**Programming and testing.** Flashing firmware and running the test procedure for each module.

**3D printing.**

**Packing and shipping.** Labelling, packing and stock of finished modules.

![Electronics workshop](/assets/images/posts/new-premises/TODO-electronics.jpg)
 **pridat fotku random stanoviste**


The most important change is a clear line between development and production. Prototypes, half-finished designs and experiments will stay on the development side. The production workstations will hold only what is ready to build, so a production batch will not get mixed up with a board someone is still debugging, and development work will not have to stop when an order needs to go out.

With its own workstation for each stage, work on one stage will not stop another. The stages will also be able to grow independently. If demand for a module goes up, we will be able to add capacity to assembly and testing without touching development.
## What it means for customers

- **Faster iterations.** With assembly and testing in the same place, fixes and custom variants of our modules should reach customers sooner.
- **Larger batches.** Separate assembly and test workstations will let us build and test more units at once.
 
![The ThunderFly team in the new premises](/assets/images/posts/new-premises/TODO-team.jpg) **Fotka tymu ThunderFly**
