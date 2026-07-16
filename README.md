

Charge Pump PLL Design using Cadence Virtuoso
A complete transistor-level Charge Pump Phase Locked Loop (CP-PLL)
designed and verified in Cadence Virtuoso using GPDK090 (90 nm CMOS
## Technology).
##  Project Overview
 The objective of this project was to design and integrate all building
blocks of a Charge Pump PLL at transistor level and verify stable
phase and frequency locking through simulation.

## Blocks:
• PFD
• Charge Pump
- Second-Order Passive Loop Filter
- 5-Stage Current-Starved Ring VCO
• Divide-by-8 Frequency Divider
- Complete PLL Integration

 PLL Architecture
 Reference Clock → PFD → Charge Pump → Loop Filter → 5-Stage
Current-Starved Ring VCO → Divide-by-8 Divider → Feedback

##  Project Specifications
 Technology: GPDK090
Supply Voltage: 1.2 V
Architecture: Charge Pump PLL
Reference Frequency: 301.25 MHz
Nominal PLL Output Frequency: 2.41 GHz
VCO Range: 2.332–2.504 GHz
Average Kvco: 172 MHz/V
Peak Kvco: ≈330 MHz/V

##  Design Blocks
 PFD: Compares reference and feedback clocks.
Charge Pump: Converts UP/DOWN pulses into current.
Loop Filter: Produces stable control voltage.
VCO: 5-stage current-starved ring oscillator.
Divider: Divide-by-8 feedback path.

##  Mathematical Model
 Phase Error: φe = φref − φfb

Ffb = Fvco/N
## Fvco = N × Fref

Kvco = Δf/ΔVc ≈ 172 MHz/V

Iavg = Icp × (tUP − tDOWN)/Tref
At lock: Iavg ≈ 0 μA
##  Simulation Results
 Successful PLL Lock
## Stable Phase & Frequency Synchronization
VCO Characterization
## Kvco Extraction
## Divider Verification
##  Software Used
##  Cadence Virtuoso
## Spectre Simulator
## GPDK090

##  Skills Demonstrated
 Analog CMOS Design
PLL Design
## Charge Pump Design
## Ring Oscillator Design
## Cadence Virtuoso
## Spectre Simulation
##  Results Summary
 The complete transistor-level Charge Pump PLL achieved stable
phase and frequency locking with a nominal output frequency of
approximately 2.41 GHz.
##  Author
##  Anant
B.Tech – VLSI Engineering
NIT Kurukshetra
##  Note
 This repository contains documentation, schematics, and waveforms
only. Proprietary PDK files are not included.