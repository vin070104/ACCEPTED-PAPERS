# High Performance Sub-6 GHz Patch Antenna with Circular Crescent DGS for 5G Applications

**Conference:** 2025 5th International Conference on Mobile Networks and Wireless Communications (ICMNWC)  
**Research area:** RF engineering · Antenna design · Microwave engineering

## 1. Authors and affiliation
Vinay P Bhavi; Preetham H; Pratik Ukey; Divya T M; Venkatesha Muniswamy; Shashikumar D

Affiliation shown in the paper: Department of Electronics and Communication Engineering, Sai Vidya Institute of Technology, Bengaluru, India (some co-authors have separately stated affiliations in the paper).

## 2. Research objective and technical concept
The study demonstrates the use of a circular-crescent slotted DGS to modify ground-current distribution and improve impedance matching of a compact Sub-6 GHz patch. The most defensible takeaway is the improvement in S11 and VSWR relative to the conventional patch. The reported gain increase is modest, and the paper itself notes possible trade-offs involving surface waves.

## 3. Design specifications

- **Operating band/frequency:** 3.3 GHz and 3.5 GHz
- **Substrate:** FR4, εr = 4.4 (the paper identifies FR4; dielectric constant is not clearly stated in the extracted paper text)
- **Antenna/array architecture:** Inset-fed rectangular microstrip patch with circular-crescent Defected Ground Structure (DGS) and rectangular slot
- **Dimensions:** Patch: 27.2 × 19.6 mm; ground: 36.8 × 47.35 mm; feed width: 3.08 mm; feed length: 25 mm; substrate thickness: 1.6 mm. The source's substrate width/length entries appear inconsistent with the ground dimensions; verify before reuse.
- **Design/simulation method:** Designed and simulated in ANSYS HFSS; parametric tuning of patch, feed and DGS geometry.

## 4. Simulation result sheet

| Parameter | Reported result | Notes |
|---|---:|---|
| Conventional patch S11 | −7.25 dB at 3.5 GHz (abstract); −7.2238 dB in results text | Without DGS |
| DGS S11 | −32.61 dB at 3.3 GHz; −21.2 dB at 3.5 GHz | Abstract/results narrative |
| DGS S11 (conclusion/table) | −35.29 dB at 3.28 GHz; −20.7 dB at 3.5 GHz | Conclusion and comparison table; differs from abstract |
| Gain | 4.06 dB | Proposed DGS antenna |
| Realized gain | 3.93 dB | Abstract |
| VSWR | 1.518 at 3.5 GHz | DGS antenna; paper labels the value with dB although VSWR is dimensionless |
| Conventional VSWR | 8.159 at 3.5 GHz | Without DGS; paper labels the value with dB |
| Patch footprint | 19.6 × 27.2 mm² | Proposed patch |

## 5. Importance and research contribution
The study demonstrates the use of a circular-crescent slotted DGS to modify ground-current distribution and improve impedance matching of a compact Sub-6 GHz patch. The most defensible takeaway is the improvement in S11 and VSWR relative to the conventional patch. The reported gain increase is modest, and the paper itself notes possible trade-offs involving surface waves.

## 6. Potential applications stated or proposed in the paper
Sub-6 GHz 5G base stations; UAV communication; IoT and compact wireless systems, as proposed by the paper.

## 7. Comparison against the other papers in this portfolio

| Research paper | Frequency | Architecture | Key reported result | Application area |
|---|---|---|---|---|
| ICMNWC 2025 – Circular Crescent DGS | 3.3/3.5 GHz | Single-element FR4 patch + circular-crescent DGS | S11 reported −32.61 dB at 3.3 GHz; conclusion reports −35.29 dB at 3.28 GHz; gain 4.06 dB | 5G Sub-6, UAV, IoT |
| Sub-6 GHz 4×4 Phased Array | 3.5 GHz | 4×4 MDTS-MPA phased array on FR4 | Gain 6.82 dB; SLL −11 dB; bandwidth 160 MHz; S12 discrepancy | 5G small cells, indoor access, beam-steered links |
| SCPGCON 2026 – Uni-Spine | 5.73 GHz | Single-layer slot-loaded patch on RT5880 | S11 −35.72 dB; gain 6.84 dB; ~90% efficiency; bandwidth inconsistency | 6 GHz WLAN, UAV, IoT, sensing |
| MAPCON 2026 – Serrated Leaf MIMO | 26.853–37.579 GHz | 1×5 Ka-band MIMO; serrated leaf radiators | 10.726 GHz bandwidth; realized gain 10.60 dB; ECC 0.0001–0.016; RCS metrics | Airborne links, UAV, tactical mmWave, 5G/6G |

## 8. Technical limitations, discrepancies and verification notes
The paper reports inconsistent S11 values between its abstract, results and conclusion/table. VSWR is dimensionless even though the paper appends dB. Treat all values as reported simulation results; do not claim fabrication or measurement unless supported separately.

## 9. Original paper PDF
[Open/download the original paper](papers/ICMNWC_2025_Circular_Crescent_DGS.pdf)

## 10. Suggested figures to add to this repository

Add only figures extracted from the original paper or your own HFSS/MATLAB project, with captions and page/figure references. Recommended: antenna geometry, S11/S-parameters, gain/radiation pattern, current distribution, and any design-specific metrics (beam steering, ECC, TARC, DG or RCS). Do not invent or redraw results as if they were measured.

## 11. Source and interpretation note

This page is based on the supplied conference-paper PDF. Numerical values are transcribed from that source and are not independently re-simulated. Any discrepancies in the source are explicitly flagged above. Unless stated otherwise in the paper, results should be described as simulated rather than measured.