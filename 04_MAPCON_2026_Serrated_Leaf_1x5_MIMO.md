# Low-Observable High-Gain Serrated Leaf 1×5 MIMO Array for Secure Airborne 5G/6G Networks

**Conference:** MAPCON 2026 — acceptance status provided by the author. Attach the official acceptance notification if documentary confirmation is required.  
**Research area:** RF engineering · Antenna design · Microwave engineering

## 1. Authors and affiliation
Vinay P Bhavi; Venkatesha Muniswamy; Divya T M; Ashish C; Shashikumar D; Preetham H

Affiliation shown in the paper: Department of Electronics and Communication Engineering, Sai Vidya Institute of Technology, Bengaluru, India (some co-authors have separately stated affiliations in the paper).

## 2. Research objective and technical concept
The central research proposition is the integration of wideband Ka-band MIMO communication performance with low ECC and reduced radar scattering in a compact 1×5 geometry. This combination of communication and low-observable/RCS analysis is the distinguishing feature relative to the other supplied antenna papers.

## 3. Design specifications

- **Operating band/frequency:** 26.853–37.579 GHz (Ka-band range stated in the paper)
- **Substrate:** The supplied extracted sections do not clearly state the substrate material/relative permittivity; confirm from the full design setup before publishing a substrate specification.
- **Antenna/array architecture:** Serrated leaf-shaped 1×5 linear five-port MIMO array; tapered microstrip feed; lateral serrations; inter-element pitch 0.69λ.
- **Dimensions:** Array footprint: 37.59 × 9.4 mm²; 1×5 elements; inter-element pitch 0.69λ. Table I lists design dimensions in centimetres: LSE 0.31, RTE 0.10, Lp 0.73, Wp 0.63, Se3 0.90, Se1 0.15, Se2 0.12, SL 0.12, CT 0.15, FL 0.17.
- **Design/simulation method:** Computational electromagnetic analysis of S-parameters, gain/realized gain, MIMO diversity parameters (ECC, DG, TARC) and monostatic/bistatic radar cross section (RCS). The paper presents simulated results; it does not establish hardware validation.

## 4. Simulation result sheet

| Parameter | Reported result | Notes |
|---|---:|---|
| Impedance bandwidth | 10.726 GHz | 26.853–37.579 GHz; S11 below −10 dB |
| Fractional bandwidth | 33.3% | As reported in abstract |
| Minimum S11 | −42.70 dB | Near principal resonance |
| VSWR | 1.05 | Minimum/ideal value reported; VSWR below 2 across the stated band |
| Peak total gain | 11.27 dB | Far-field total gain |
| Peak realized gain | 10.60 dB | Reported realized gain |
| ECC | 0.0001–0.0160 | Reported diversity range |
| Diversity gain | Approximately 9.9997 dB | Reported theoretical-near-maximum value |
| Monostatic RCS peak | −33.42 dBsm | Abstract/results |
| Monostatic RCS null | −65.23 dBsm | Abstract/results |
| Bistatic RCS | Peak −46.5 dBsm in abstract; minima −69.82 and −79.20 dBsm in results | Peak and minima are different statistics; preserve distinction |
| Inter-port isolation | Paper states coupling parameters meet a −20 dB target across functional band | Use the plotted S-parameter results for detailed port-pair values |

## 5. Importance and research contribution
The central research proposition is the integration of wideband Ka-band MIMO communication performance with low ECC and reduced radar scattering in a compact 1×5 geometry. This combination of communication and low-observable/RCS analysis is the distinguishing feature relative to the other supplied antenna papers.

## 6. Potential applications stated or proposed in the paper
Secure airborne communication links, UAVs, tactical platforms and prospective 5G/6G millimetre-wave communication systems, as proposed by the paper.

## 7. Comparison against the other papers in this portfolio

| Research paper | Frequency | Architecture | Key reported result | Application area |
|---|---|---|---|---|
| ICMNWC 2025 – Circular Crescent DGS | 3.3/3.5 GHz | Single-element FR4 patch + circular-crescent DGS | S11 reported −32.61 dB at 3.3 GHz; conclusion reports −35.29 dB at 3.28 GHz; gain 4.06 dB | 5G Sub-6, UAV, IoT |
| Sub-6 GHz 4×4 Phased Array | 3.5 GHz | 4×4 MDTS-MPA phased array on FR4 | Gain 6.82 dB; SLL −11 dB; bandwidth 160 MHz; S12 discrepancy | 5G small cells, indoor access, beam-steered links |
| SCPGCON 2026 – Uni-Spine | 5.73 GHz | Single-layer slot-loaded patch on RT5880 | S11 −35.72 dB; gain 6.84 dB; ~90% efficiency; bandwidth inconsistency | 6 GHz WLAN, UAV, IoT, sensing |
| MAPCON 2026 – Serrated Leaf MIMO | 26.853–37.579 GHz | 1×5 Ka-band MIMO; serrated leaf radiators | 10.726 GHz bandwidth; realized gain 10.60 dB; ECC 0.0001–0.016; RCS metrics | Airborne links, UAV, tactical mmWave, 5G/6G |

## 8. Technical limitations, discrepancies and verification notes
Simulation-only evidence in the supplied paper; do not claim fabricated, flight-tested, operationally stealthy or experimentally validated performance. The abstract's bistatic RCS peak (−46.5 dBsm) must not be confused with the deeper minima reported in the results section. Substrate details should be verified from the full HFSS model/setup.

## 9. Original paper PDF
[Open/download the original paper](papers/MAPCON_2026_Serrated_Leaf_1x5_MIMO.pdf)

## 10. Suggested figures to add to this repository

Add only figures extracted from the original paper or your own HFSS/MATLAB project, with captions and page/figure references. Recommended: antenna geometry, S11/S-parameters, gain/radiation pattern, current distribution, and any design-specific metrics (beam steering, ECC, TARC, DG or RCS). Do not invent or redraw results as if they were measured.

## 11. Source and interpretation note

This page is based on the supplied conference-paper PDF. Numerical values are transcribed from that source and are not independently re-simulated. Any discrepancies in the source are explicitly flagged above. Unless stated otherwise in the paper, results should be described as simulated rather than measured.