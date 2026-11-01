# A Compact Uni-Spine Slot-Loaded Patch Antenna for C-Band Wireless and UAV Communication Systems

**Conference:** 2026 Smart RF Communication, Photonics, Geoscience and Remote Sensing Conference (SCPGCON)  
**Research area:** RF engineering · Antenna design · Microwave engineering

## 1. Authors and affiliation
Vinay P Bhavi; Preetham H; Pratik Ukey; Divya T M; Venkatesha Muniswamy; Shashikumar D

Affiliation shown in the paper: Department of Electronics and Communication Engineering, Sai Vidya Institute of Technology, Bengaluru, India (some co-authors have separately stated affiliations in the paper).

## 2. Research objective and technical concept
The contribution is a compact, single-layer, PCB-manufacturable Uni-Spine slot-loaded radiator on RT5880 with deep S11, near-unity VSWR, moderate-high gain and approximately 90% reported radiation efficiency. The simple planar construction is a practical design feature. Its narrow bandwidth must be stated as a limitation.

## 3. Design specifications

- **Operating band/frequency:** Resonance at 5.73 GHz; described as a 6 GHz/C-band application design
- **Substrate:** Rogers RT5880, εr = 2.2; thickness 1.575 mm
- **Antenna/array architecture:** Single-layer planar Uni-Spine slot-loaded microstrip patch with central spine, stepped radiating sections and slots; no vias or multilayer stacking.
- **Dimensions:** Compact size reported as 0.86λ × 0.86λ × 0.031λ. Selected geometry parameters: top parasitic strip length 9 mm; upper/middle radiating section heights 8 mm each; central notch width 2 mm; upper slot lengths 4 mm and 10.2 mm; lower step length 7 mm; lower radiating section height 5.8 mm; side slot width 2 mm; feed length 10 mm; top parasitic strip width 1.07 mm.
- **Design/simulation method:** Model-based design and simulation; parametric optimisation of the planar slot-loaded geometry and feed in the paper.

## 4. Simulation result sheet

| Parameter | Reported result | Notes |
|---|---:|---|
| Resonant frequency | 5.73 GHz | Main resonance |
| S11 | −35.72 dB | At 5.73 GHz |
| VSWR | 1.0512 | At 5.73 GHz |
| Total gain | 6.84 dB | At operating frequency |
| Elevation-plane gain | 5.85 dB | Reported by paper |
| Azimuth-plane gain | 4.02 dB | Reported by paper |
| Directivity | 6.69 dB | Conclusion; body also rounds to approximately 6.7 dB |
| Radiation efficiency | Approximately 90% | Reported near resonance |
| Impedance bandwidth | 88 MHz | Paper states 5.6810–5.7290 GHz in one passage; this interval is 48 MHz, inconsistent with the stated 88 MHz. Verify against the plotted data. |

## 5. Importance and research contribution
The contribution is a compact, single-layer, PCB-manufacturable Uni-Spine slot-loaded radiator on RT5880 with deep S11, near-unity VSWR, moderate-high gain and approximately 90% reported radiation efficiency. The simple planar construction is a practical design feature. Its narrow bandwidth must be stated as a limitation.

## 6. Potential applications stated or proposed in the paper
6 GHz WLAN/Wi-Fi 6E, UAV communication links, IoT nodes, wireless sensing and radar front-end contexts, as proposed by the paper.

## 7. Comparison against the other papers in this portfolio

| Research paper | Frequency | Architecture | Key reported result | Application area |
|---|---|---|---|---|
| ICMNWC 2025 – Circular Crescent DGS | 3.3/3.5 GHz | Single-element FR4 patch + circular-crescent DGS | S11 reported −32.61 dB at 3.3 GHz; conclusion reports −35.29 dB at 3.28 GHz; gain 4.06 dB | 5G Sub-6, UAV, IoT |
| Sub-6 GHz 4×4 Phased Array | 3.5 GHz | 4×4 MDTS-MPA phased array on FR4 | Gain 6.82 dB; SLL −11 dB; bandwidth 160 MHz; S12 discrepancy | 5G small cells, indoor access, beam-steered links |
| SCPGCON 2026 – Uni-Spine | 5.73 GHz | Single-layer slot-loaded patch on RT5880 | S11 −35.72 dB; gain 6.84 dB; ~90% efficiency; bandwidth inconsistency | 6 GHz WLAN, UAV, IoT, sensing |
| MAPCON 2026 – Serrated Leaf MIMO | 26.853–37.579 GHz | 1×5 Ka-band MIMO; serrated leaf radiators | 10.726 GHz bandwidth; realized gain 10.60 dB; ECC 0.0001–0.016; RCS metrics | Airborne links, UAV, tactical mmWave, 5G/6G |

## 8. Technical limitations, discrepancies and verification notes
The stated 88 MHz bandwidth conflicts with the stated frequency endpoints 5.6810–5.7290 GHz, which span 48 MHz. The paper describes the design as simulated; no fabrication/measurement evidence is established by the supplied PDF.

## 9. Original paper PDF
[Open/download the original paper](papers/SCPGCON_2026_Uni_Spine_CBand_Antenna.pdf)

## 10. Suggested figures to add to this repository

Add only figures extracted from the original paper or your own HFSS/MATLAB project, with captions and page/figure references. Recommended: antenna geometry, S11/S-parameters, gain/radiation pattern, current distribution, and any design-specific metrics (beam steering, ECC, TARC, DG or RCS). Do not invent or redraw results as if they were measured.

## 11. Source and interpretation note

This page is based on the supplied conference-paper PDF. Numerical values are transcribed from that source and are not independently re-simulated. Any discrepancies in the source are explicitly flagged above. Unless stated otherwise in the paper, results should be described as simulated rather than measured.