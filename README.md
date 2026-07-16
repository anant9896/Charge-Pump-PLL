

<!-- Start of picture text -->
of“ phase h fant<br>frequency wae a vco i<br>detector hl<br>frequency<br>divider<br><!-- End of picture text -->

Nominal PLL Output Frequency: 2.41 GHz VCO Range: 2.332–2.504 GHz Average Kvco: 172 MHz/V Peak Kvco: ≈330 MHz/V 

#  **Design Blocks** 

 **PFD:** Compares reference and feedback clocks. **Charge Pump:** Converts UP/DOWN pulses into current. **Loop Filter:** Produces stable control voltage. **VCO:** 5-stage current-starved ring oscillator. **Divider:** Divide-by-8 feedback path. 

#  **Mathematical Model** 

- Phase Error: φe = φref − φfb 

Ffb = Fvco/N Fvco = N × Fref 

Kvco = Δf/ΔVc ≈ 172 MHz/V 

Iavg = Icp × (tUP − tDOWN)/Tref At lock: Iavg ≈ 0 µA 

#  **Simulation Results** 

- Successful PLL Lock 

Stable Phase & Frequency Synchronization VCO Characterization Kvco Extraction Divider Verification 

#  **Software Used** 

- Cadence Virtuoso Spectre Simulator GPDK090 

- **Skills Demonstrated** 

- Analog CMOS Design 

PLL Design Charge Pump Design Ring Oscillator Design Cadence Virtuoso Spectre Simulation 

- **Results Summary** 

- The complete transistor-level Charge Pump PLL achieved stable phase and frequency locking with a nominal output frequency of approximately 2.41 GHz. 

#  **Author** 

- Anant 

B.Tech – VLSI Engineering 

NIT Kurukshetra 

#  **Note** 

- This repository contains documentation, schematics, and waveforms only. Proprietary PDK files are not included. 

