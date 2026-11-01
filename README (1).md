# Vinay P. Bhavi | RF, Antenna & Microwave Research Portfolio

A curated repository of my conference research papers and simulation work in RF engineering, microstrip antennas, phased arrays, MIMO, beam steering and low-observable antenna systems.

**Profile:** [github.com/vin070104](https://github.com/vin070104)  
**Portfolio:** [vin070104.github.io](https://vin070104.github.io/)

## Research papers

| # | Paper | Venue / status | Operating band | Key reported outcome |
|---|---|---|---|---|
| 1 | [High Performance Sub-6 GHz Patch Antenna with Circular Crescent DGS for 5G Applications](icmnwc-2025-circular-crescent-dgs.md) | ICMNWC 2025 | 3.3 / 3.5 GHz | DGS patch; reported S11 down to −35.29 dB in conclusion; gain 4.06 dB |
| 2 | [Design and Simulation of a Phased Array Antenna With Beam Steering for Sub-6GHz Applications](sub6-phased-array-beam-steering.md) | Conference paper; venue/status needs confirmation from official record | 3.5 GHz | 4×4 FR4 phased array; gain 6.82 dB; bandwidth 160 MHz |
| 3 | [A Compact Uni-Spine Slot-Loaded Patch Antenna for C-Band Wireless and UAV Communication Systems](scpgcon-2026-uni-spine-cband.md) | SCPGCON 2026 | 5.73 GHz | S11 −35.72 dB; gain 6.84 dB; ~90% radiation efficiency |
| 4 | [Low-Observable High-Gain Serrated Leaf 1×5 MIMO Array for Secure Airborne 5G/6G Networks](mapcon-2026-serrated-leaf-mimo.md) | MAPCON 2026 — accepted | 26.853–37.579 GHz | 10.726 GHz bandwidth; realized gain 10.60 dB; low ECC and RCS metrics |

## Cross-paper comparison

See [`comparison.csv`](comparison.csv) for a machine-readable comparison of frequency band, architecture, reported results and application areas.

### What the body of work covers

- **Impedance matching and DGS:** circular-crescent defected-ground structure for a Sub-6 GHz patch.
- **Beamforming:** 4×4 MDTS-MPA phased array with progressive phase excitation.
- **Compact C-band radiator:** single-layer Uni-Spine slot-loaded patch on Rogers RT5880.
- **Wideband mmWave MIMO and low observability:** serrated-leaf 1×5 array with ECC and RCS evaluation.

## Repository structure

```text
.
├── README.md
├── comparison.csv
├── icmnwc-2025-circular-crescent-dgs.md
├── sub6-phased-array-beam-steering.md
├── scpgcon-2026-uni-spine-cband.md
├── mapcon-2026-serrated-leaf-mimo.md
└── papers/
    ├── ICMNWC_2025_Circular_Crescent_DGS_Sub6GHz.pdf
    ├── Phased_Array_Beam_Steering_Sub6GHz.pdf
    ├── SCPGCON_2026_Uni_Spine_CBand_Antenna.pdf
    └── MAPCON_2026_Serrated_Leaf_1x5_MIMO.pdf
```

## Important technical notes

1. All numerical values are transcribed from the supplied PDFs. They are not independently re-simulated or experimentally verified by this repository.
2. The ICMNWC paper reports slightly different S11 values in its abstract and conclusion. Both are disclosed on its paper page.
3. The phased-array paper reports different S12 values in its results narrative and comparison table. Both are disclosed on its paper page.
4. The MAPCON paper includes both peak and minimum RCS values; they are not interchangeable. See its paper page for the distinctions.
5. The phased-array PDF supplied here does not clearly identify the conference on its title page. Confirm the official venue/publication details before adding them.
6. “Accepted at MAPCON 2026” is based on the acceptance information supplied by the author; attach or link the official acceptance notice if you want documentary evidence in this repository.

## Author

**Vinay P Bhavi**  
RF & Antenna Design | Electronics | Ansys HFSS | MATLAB  
[GitHub](https://github.com/vin070104) · [LinkedIn](https://www.linkedin.com/in/vinay-p-bhavi-244909337/) · [Portfolio](https://vin070104.github.io/)
