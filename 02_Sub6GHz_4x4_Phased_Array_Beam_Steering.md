# Design and Simulation of a Phased Array Antenna With Beam Steering for Sub-6GHz Applications

**Conference:** Conference paper; the supplied PDF title page does not clearly identify the conference name or publication status. Confirm from the official conference record before describing it as accepted/published.  
**Research area:** RF engineering · Antenna design · Microwave engineering

## 1. Authors and affiliation
Preetham H; Vinay P Bhavi; Pratik Ukey; Divya T M; Venkatesha Muniswamy; Shashikumar D

Affiliation shown in the paper: Department of Electronics and Communication Engineering, Sai Vidya Institute of Technology, Bengaluru, India (some co-authors have separately stated affiliations in the paper).

## 2. Research objective and technical concept
This work extends a slot-loaded Sub-6 GHz patch into a 4×4 phased array and demonstrates phase-controlled beam shaping in simulation. It is relevant as an array-level design study because it addresses gain, directivity, side-lobe behaviour and inter-element coupling rather than only single-element matching.

## 3. Design specifications

- **Operating band/frequency:** 3.5 GHz
- **Substrate:** FR4, εr = 4.4; thickness 2.4 mm
- **Antenna/array architecture:** Meandered Dual T-slot Loaded Microstrip Patch Antenna (MDTS-MPA), extended to a 4×4 phased array with progressive phase excitation.
- **Dimensions:** Single-element patch: 19.4 × 24.8 mm; ground: 33.8 × 39.2 mm; feed width: 3.08 mm; feed length: 25 mm; thickness: 2.4 mm; array spacing: 50 mm.
- **Design/simulation method:** Single element and 4×4 array modelled in ANSYS HFSS. Progressive phase offsets are applied to array elements to steer the beam. The paper provides the phase relation as a function of element indices, spacing, elevation and azimuth steering angles.

## 4. Simulation result sheet

| Parameter | Reported result | Notes |
|---|---:|---|
| Single-element S11 | −22.63 dB | At approximately 3.5 GHz |
| Array gain | 6.82 dB | Reported for 4×4 array |
| Directivity | 21.38 | Paper reports this numeric value; unit/scale is not clearly presented in the text |
| Side-lobe level | −11 dB | Reported for the array radiation pattern |
| Impedance bandwidth | 160 MHz | Reported in the comparison table/conclusion |
| Array spacing | 50 mm | Chosen element spacing |
| S12 / mutual coupling | −54.17 dB in results narrative; −30 dB in comparison table | Internal discrepancy; verify from original simulation plots/data |

## 5. Importance and research contribution
This work extends a slot-loaded Sub-6 GHz patch into a 4×4 phased array and demonstrates phase-controlled beam shaping in simulation. It is relevant as an array-level design study because it addresses gain, directivity, side-lobe behaviour and inter-element coupling rather than only single-element matching.

## 6. Potential applications stated or proposed in the paper
Sub-6 GHz 5G, small-cell base stations, indoor access points and beam-steered wireless systems. Radar is mentioned in the broader application discussion but should be presented as a potential application, not a demonstrated system.

## 7. Comparison against the other papers in this portfolio

| Research paper | Frequency | Architecture | Key reported result | Application area |
|---|---|---|---|---|
| ICMNWC 2025 – Circular Crescent DGS | 3.3/3.5 GHz | Single-element FR4 patch + circular-crescent DGS | S11 reported −32.61 dB at 3.3 GHz; conclusion reports −35.29 dB at 3.28 GHz; gain 4.06 dB | 5G Sub-6, UAV, IoT |
| Sub-6 GHz 4×4 Phased Array | 3.5 GHz | 4×4 MDTS-MPA phased array on FR4 | Gain 6.82 dB; SLL −11 dB; bandwidth 160 MHz; S12 discrepancy | 5G small cells, indoor access, beam-steered links |
| SCPGCON 2026 – Uni-Spine | 5.73 GHz | Single-layer slot-loaded patch on RT5880 | S11 −35.72 dB; gain 6.84 dB; ~90% efficiency; bandwidth inconsistency | 6 GHz WLAN, UAV, IoT, sensing |
| MAPCON 2026 – Serrated Leaf MIMO | 26.853–37.579 GHz | 1×5 Ka-band MIMO; serrated leaf radiators | 10.726 GHz bandwidth; realized gain 10.60 dB; ECC 0.0001–0.016; RCS metrics | Airborne links, UAV, tactical mmWave, 5G/6G |

## 8. Technical limitations, discrepancies and verification notes
The supplied paper is simulation-focused. The PDF itself notes future work involving adaptive phase control/hardware implementation. S12 is inconsistent between the narrative and comparison table. The directivity value 21.38 should be checked against the original HFSS report before presenting it as dBi.

## 9. Original paper PDF
[Open/download the original paper](papers/Phased_Array_Beam_Steering_Sub6GHz.pdf)

## 10. Suggested figures to add to this repository

Add only figures extracted from the original paper or your own HFSS/MATLAB project, with captions and page/figure references. Recommended: antenna geometry, S11/S-parameters, gain/radiation pattern, current distribution, and any design-specific metrics (beam steering, ECC, TARC, DG or RCS). Do not invent or redraw results as if they were measured.

## 11. Source and interpretation note

This page is based on the supplied conference-paper PDF. Numerical values are transcribed from that source and are not independently re-simulated. Any discrepancies in the source are explicitly flagged above. Unless stated otherwise in the paper, results should be described as simulated rather than measured.