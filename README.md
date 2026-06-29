# Digital-Logic-Design

## Overview

This repository contains a collection of digital logic circuits designed and simulated as part of a foundational course in logic design, along with supporting conceptual notes summarizing the underlying theory. The work here progresses from basic Boolean logic principles through to the schematic-level construction of combinational and sequential digital systems.

## What's Inside

- **Circuit Files** – Schematic-level digital circuit designs created in a logic circuit simulator (e.g., Logisim), covering both combinational and sequential logic.
- **Conceptual Notes** – A general write-up of the theoretical foundations these designs are built on: Boolean algebra, minimization techniques, and sequential circuit theory.

## Topics Covered

- Number systems and Boolean algebra fundamentals
- Logic minimization techniques (Karnaugh maps / K-maps)
- Combinational circuit design: adders, subtractors, encoders, decoders, multiplexers, shift registers
- Programmable logic devices: PROM, PAL, PLA
- Sequential circuit design: latches, flip-flops, registers, and counters
- State machine design: state diagrams, state tables, and state minimization
- Memory design fundamentals (RAM/ROM concepts)
- Schematic-level simulation and verification of digital circuits

## Why the Circuit Files Matter

The circuit files in this repository aren't just supplementary material — they're the practical proof of the theory.

- **Theory becomes verifiable** – A Boolean expression or K-map simplification means little until it's actually built and tested. Each circuit file shows that the underlying logic genuinely works, not just on paper.
- **Schematic-level thinking** – Reading and building a circuit at the schematic level (gates, wires, components) is a distinct skill from solving equations by hand. These files demonstrate that translation from abstract logic to a working design.
- **Debugging and troubleshooting** – A circuit that simulates correctly has usually been through trial, error, and correction along the way. The final files represent designs that have been tested and validated through simulation, not just assumed to work.
- **A reusable reference** – Anyone reviewing this repository can open the circuit files directly in a simulator, step through the logic, and see the design decisions for themselves, without needing physical lab hardware.
- **A complete design progression** – The sequential circuits in particular (flip-flops, counters, registers, state machines) build directly on the combinational ones, so the circuit files as a set show a full progression rather than isolated exercises.

In short: the notes explain *why* a design should work — the circuit files prove *that* it does.

## Tools Used

- A digital logic circuit simulator (e.g., Logisim) for constructing and simulating circuits at the schematic level.

## How to Use the Circuit Files

1. Open the simulator used to create the files (e.g., Logisim).
2. Load the circuit file you want to inspect.
3. Run the simulation and toggle inputs to observe the circuit's behavior.
4. Cross-reference the conceptual notes for the theory behind each design.
