---
# MIOP terms
methodology_category: sample extraction and purification
project: NOAA Ocean Exploration seawater eDNA metabarcoding
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: Atlantic Ocean [GAZ:00000344], Gulf of Mexico [GAZ:00002853], Pacific Ocean
broad_scale_environmental_context: # marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: # marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Steven Auscavitch, Allen Collins
materials_required: vortexer [OBI:0400118], centrifuge [OBI:0400106], DNA extraction/purification instrument [OBI:0001117], heat block, laminar flow hood
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 2880 # minutes (integer); approximately 48 hours across 2 days
personnel_required: 1
language: en
issued: 2024-03-01
audience: scientists
publisher: National Museum of Natural History, Smithsonian Institution
hasVersion: 1.1.2
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: # actual volume extracted depends on volume filtered and varies by sample
samp_vol_we_dna_ext_unit: # actual volume extracted depends on volume filtered and varies by sample
nucl_acid_ext_lysis: enzymatic
nucl_acid_ext_sep: centrifugation
nucl_acid_ext_kit: Qiagen DNeasy Blood & Tissue Kit (cat. no. 69504 or 69506)
nucl_acid_ext_modify: Adapted from Spens et al. 2017 and Wacker et al. 2019 for Sterivex filters
dna_cleanup_0_1: 0
dna_cleanup_method: not applicable
concentration: not applicable
concentration_method: not applicable
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: Two sequential elutions with preheated Buffer AE (56°C); eluate reloaded onto spin column membrane between elutions
---

# NMNH DNA Extraction Protocol using Qiagen DNeasy Kit

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------ | ------------ | ------------ | ---------- |
| Steven Auscavitch | National Museum of Natural History, Smithsonian Institution | <https://orcid.org/0000-0001-5777-4814> | 2024-03-01 |
| Allen Collins | NOAA NSL; Smithsonian Institution | <https://orcid.org/0000-0002-3664-9691> | 2024-03-01 |
| K. Murphy | Smithsonian Institution, Laboratories of Analytical Biology | Not available | 2020-03-18 |

### Related Protocols

#### Internal Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE |
| ------------- | ------------ | ------------ | ---------- |
| Content | Content | Content | Content |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| Comparison of capture and storage methods for aqueous macrobial eDNA using an optimized extraction protocol: advantage of enclosed filter | <https://doi.org/10.1111/2041-210X.12683> | Spens et al. 2017 | 2024-03-01 |
| Downstream transport and seasonal variation in freshwater pearl mussel (*Margaritifera margaritifera*) eDNA concentration | <https://doi.org/10.1002/edn3.10> | Wacker et al. 2019 | 2024-03-01 |
| DNeasy Blood & Tissue Kit Handbook | <https://www.qiagen.com/us/resources/resourcedetail?id=6b09dfb8-6319-464d-996c-79e8c7045a50> | QIAGEN | 2024-03-01 |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2020-03-18 | Initial release (K. Murphy, Smithsonian Institution LAB) |
| 1.1.0 | 2024-03-01 | Adapted for OKEX project; updated authorship and affiliation |
| 1.1.1 | 2026-04-10 | Updated YAML front matter |
| 1.1.2 | 2026-04-10 | Updated YAML front matter with version number |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| eDNA | environmental DNA |
| NOAA | National Oceanic and Atmospheric Administration |
| NSL | National Systematics Laboratory |
| SI | Smithsonian Institution |
| NMNH | National Museum of Natural History |
| LAB | Laboratories of Analytical Biology |
| ATL | Buffer ATL (QIAGEN lysis buffer) |
| AE | Buffer AE (QIAGEN elution buffer) |
| AL | Buffer AL (QIAGEN lysis buffer) |
| AW1 | Buffer AW1 (QIAGEN wash buffer 1) |
| AW2 | Buffer AW2 (QIAGEN wash buffer 2) |
| EtOH | Ethanol |
| ProtK | Proteinase K |
| RT | Room temperature |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Sterivex capsule | An enclosed inline filter capsule (0.22 µm or 0.45 µm) used to filter water samples for eDNA collection |
| Spin column | A silica membrane column used in kit-based DNA purification that retains DNA during centrifugation wash steps |
| Lysate | The liquid mixture containing cellular debris and DNA after enzymatic digestion |
| Eluate | The liquid collected after DNA is washed off a spin column membrane with elution buffer |

## BACKGROUND

### Summary

This document describes the protocol to extract environmental DNA (eDNA) from seawater samples collected on sterivex capsule filters using the Qiagen DNeasy Blood & Tissue Kit. The protocol is adapted from Spens et al. (2017) and Wacker et al. (2019) and was updated on 18-Mar-2020 by K. Murphy (Smithsonian Institution, Laboratories of Analytical Biology). It is applied here to samples collected at sea on the NOAA Ship Okeanos Explorer.

### Method Description and Rationale

This protocol provides a method to extract and purify environmental DNA from eDNA samples preserved in sterivex capsule filters filled with Buffer ATL (or stored dry). Enzymatic lysis using Proteinase K followed by silica membrane spin column purification (DNeasy kit) enables efficient recovery of high-quality DNA from filtered seawater samples.

### Spatial Coverage and Environment(s) of Relevance

Oceanic Epipelagic Zone [ENVO:01000035]
Marine Mesopelagic Zone [ENVO:00000213]
Marine Bathypelagic Zone [ENVO:00000211]
Marine Abyssopelagic Zone [ENVO:00000212]

## PERSONNEL REQUIRED

This procedure can be performed by one individual trained in basic wet lab bench techniques.

### Safety

Basic laboratory safety measures and appropriate personal protective equipment (nitrile gloves, lab coat, eye protection) should be used. Work should be conducted in a laminar flow hood when possible. Standard precautions for working with ethanol and bleach solutions apply.

### Training Requirements

Basic wet lab bench skills including pipetting, aseptic technique, and centrifuge operation are required. Familiarity with spin column-based DNA extraction protocols is recommended.

### Time Needed to Execute the Procedure

Total time (estimated): ~48 hours across 2 days
- Day 1 sample preparation and incubation: 1–2 hours active time + 24 hours incubation
- Day 2 extraction and elution: 3–4 hours active time

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Laminar flow hood | Nonspecific | Nonspecific | 1 | UV sterilize between uses |
| Benchtop vortexer | Nonspecific | Nonspecific | 1 | N/A |
| Heat block or incubator with shaking | Nonspecific | Nonspecific | 1 | Must maintain 56°C with agitation |
| Refrigerated centrifuge | Nonspecific | Nonspecific | 1 | Must reach 20,000g; compatible with 1.5/2.0 mL and 5.0 mL tubes |
| P1000 Pipette | Nonspecific | Nonspecific | 1 | Or similar |
| P200 Pipette | Nonspecific | Nonspecific | 1 | Or similar |
| P20 Pipette | Nonspecific | Nonspecific | 1 | Or similar |
| **Consumable equipment** |
| 3 mL syringes | Fisher 14-955-457 | Fisher Scientific | 1 per sample | For lysate recovery from sterivex inlet port |
| Outlet caps (Female Luer) | Cole-Parmer EW-30800-12 | Cole-Parmer | 1 per sample | Only needed if sterivex units are not already capped |
| Inlet caps (Male Luer) | Cole-Parmer EW-30800-30 | Cole-Parmer | 1 per sample | Only needed if sterivex units are not already capped |
| Eppendorf LoBind Tubes (5 mL) | Eppendorf 30108310 | Eppendorf | At least 1 per sample | For lysate collection |
| Eppendorf LoBind Tubes (2 mL) | Eppendorf 22431048 | Eppendorf | At least 2 per sample | For final eluate storage |
| DNeasy spin columns and collection tubes | Included in DNeasy Blood & Tissue Kit | QIAGEN | 1 per sample | From kit |
| Parafilm | Nonspecific | Nonspecific | As needed | For sealing sterivex ports |
| Filter tips | Nonspecific | Nonspecific | As needed | Use for all steps |
| Hype-Wipes | CurrentTechnologies 9103 | Current Technologies | As needed | For surface decontamination |
| KimWipes | KimwipesTM 34155 | Kimberly-Clark | 1 box | As needed |
| **Chemicals** |
| DNeasy Blood & Tissue Kit | QIAGEN 69504 or 69506 | QIAGEN | As needed | Contains spin columns, collection tubes, and Buffers AW1, AW2, AE |
| Proteinase K | QIAGEN 19133 | QIAGEN | As needed | Alternatively, prepare 20 mg/mL stock in-house |
| Buffer AL | QIAGEN 19075 | QIAGEN | As needed | For lysis step; mix fresh 1:1 with 100% EtOH on day of extraction |
| Buffer ATL | QIAGEN 939011 | QIAGEN | As needed | Only needed if sterivex units were stored dry (not pre-filled with ATL) |
| Absolute Ethanol (100%) | Nonspecific | Nonspecific | As needed | Mixed with Buffer AL; do not store EtOH:AL mixture |
| Ethanol (70%) | Nonspecific | Nonspecific | As needed | For surface decontamination |
| 10% Bleach or Hype-Wipes | Nonspecific | Nonspecific | As needed | For surface decontamination |
| Surface Disinfectant | DNA Away | Thermo-Fisher | 1 bottle | For decontamination of pipettes and surfaces |

## STANDARD OPERATING PROCEDURE

### Methodological Notes

- All eDNA extractions should ideally be performed in a laminar flow hood.
- The hood, any necessary bench space, and pipettes must be cleaned with 10% bleach and 70% ethanol immediately prior to use. The hood should be UV sterilized between uses.
- Before starting, calculate how much Proteinase K, Buffer ATL, and Buffer AL will be needed and confirm sufficient supply before beginning extractions.
- Prepare a fresh EtOH:AL mixture on the day of extraction; do not store this mixture.
- Use filter tips for all extractions.
- Always include an extraction blank alongside sample preparations.

### Preparation

1. Decontaminate and disinfect the work area by wiping down the work surface with 10% bleach or a Hype-Wipe, followed by 70% ethanol. Pipettes should be wiped down with DNA Away followed by 70% ethanol, then UV-irradiated for 15 minutes in the fume hood or laminar flow cabinet.

2. Remove sterivex capsules from storage. If samples were stored at -80°C, thaw to room temperature. Wipe the outside of each sterivex capsule with 10% bleach or a Hype-Wipe and allow to dry, then wipe with 70% ethanol and allow to dry.

3. Ensure that the outlet cap is firmly in place and para-filmed to prevent leakage.
   - If the outlet was previously covered only with parafilm, add an outlet cap before proceeding. Remove the original parafilm, add an outlet cap, and re-parafilm.

4. An extraction negative control (extraction blank) should be prepared at this time. Use a sterivex capsule containing only Buffer ATL with no sample filtrate, or follow your laboratory's standard blank protocol.

### Day 1 — Lysis

5. Carefully remove the inlet cap from each sterivex unit.

6. ONLY if samples were stored dry (not pre-filled with ATL): add 1.5 mL Buffer ATL through the inlet port. Omit this step if samples already contain ATL.

7. Add 150 µL of Proteinase K through the inlet port.
   - Note: if a volume other than 1.5 mL was used for ATL, use 1/10th that volume for Proteinase K (e.g., 2 mL ATL → 200 µL Proteinase K).

8. Cap the inlet port with an inlet cap and seal with parafilm to prevent leakage. Do not rely on parafilm alone — use an inlet cap.

9. Invert 5 times to mix.

10. Incubate at 56°C for 24 hours with shaking/agitation.
    - If incubation is less than 24 hours (e.g., overnight), record the actual length of incubation.

### Day 2 — Extraction

11. Preheat Buffer AE to 56°C in a heat block.

12. Remove samples from incubator. Shake each capsule vigorously by hand five times.

13. Using a 3 mL syringe attached to the inlet port, remove all liquid from the sterivex capsule. Record the volume and transfer the lysate to a labeled 5 mL Lo-Bind tube.

14. Prepare the EtOH:AL mixture fresh: mix 100% EtOH and Buffer AL in a 1:1 ratio, preparing sufficient volume to add 2 volumes of EtOH:AL mixture per 1 volume of lysate across all samples.
    - Example: 1.5 mL of lysate requires 3.0 mL of EtOH:AL mixture.

15. Add 2 volumes of EtOH:AL mixture to each tube of lysate. Vortex vigorously to mix.

16. Pipette 650 µL of the mixture into a DNeasy spin column seated in a 2 mL collection tube (from kit).

17. Centrifuge at 6,000g (8,000 rpm) for 1 minute, then discard flow-through.

18. Repeat steps 16–17 until the entire sample volume has been passed through the same spin column, discarding the flow-through each time.

19. Place the spin column into a new 2 mL collection tube (from kit).

20. Add 500 µL Buffer AW1, then centrifuge for 1 minute at 6,000g (8,000 rpm). Discard flow-through and collection tube.

21. Place the spin column into a new 2 mL collection tube. Add 500 µL Buffer AW2, then centrifuge for 3 minutes at 20,000g (14,000 rpm). Discard flow-through.

22. Replace the spin column onto the same collection tube and centrifuge again for 1 minute at 17,000g (13,000 rpm) to dry the membrane.

23. Transfer the spin column to a new, labeled 2 mL DNA Lo-Bind tube with the cap removed.

24. Add 100 µL of 56°C Buffer AE directly to the filter membrane.

25. Incubate at room temperature for 10 minutes.

26. Centrifuge for 1 minute at 6,000g (8,000 rpm).

27. Add the eluate back onto the spin column membrane, then incubate at room temperature for another 10 minutes.

28. Centrifuge for 1 minute at 6,000g (8,000 rpm).

29. Discard the spin column.

30. Transfer the DNA eluate to a new, labeled 2.0 mL DNA Lo-Bind tube.

31. Optional: Aliquot 3–5 µL to a separate tube for DNA quantification.

32. Store DNA at -20°C.

### Quality Control

No quantification step is specified in the source protocol beyond optional aliquoting for downstream quantification (step 31). If quantification is desired, a Qubit dsDNA HS Assay or equivalent fluorometric method is recommended. Record DNA concentration [ng/µL] for each sample.

### Basic Troubleshooting Guide

| PROBLEM | POSSIBLE CAUSE | SUGGESTED ACTION |
| ------------- | ------------- | ------------- |
| Low DNA yield | Insufficient lysis time or ATL volume | Confirm 24-hour incubation; confirm ATL was added if stored dry |
| Low DNA yield | Incomplete lysate recovery from sterivex | Use syringe carefully to withdraw all liquid from capsule |
| Contamination in extraction blank | Cross-contamination during pipetting | Re-decontaminate workspace; replace pipette tips; UV sterilize hood |
| EtOH:AL mixture precipitate | Old or improperly mixed reagents | Prepare fresh EtOH:AL mixture on day of extraction; do not store |
| Leakage from sterivex during incubation | Inadequate sealing of ports | Confirm outlet and inlet caps are in place and parafilmed before incubation |

## REFERENCES

Spens, J., Evans, A. R., Halfmaerten, D., Knudsen, S. W., Sengupta, M. E., Mak, S. S., Sigsgaard, E. E., and Hellström, M. (2017). Comparison of capture and storage methods for aqueous macrobial eDNA using an optimized extraction protocol: advantage of enclosed filter. *Methods in Ecology and Evolution*, 8: 635–645. <https://doi.org/10.1111/2041-210X.12683>

Wacker, S., Fossøy, F., Larsen, B. M., Brandsegg, H., Sivertsgård, R., and Karlsson, S. (2019). Downstream transport and seasonal variation in freshwater pearl mussel (*Margaritifera margaritifera*) eDNA concentration. *Environmental DNA*, 1: 64–73. <https://doi.org/10.1002/edn3.10>

## APPENDIX A: DATASHEETS

Not applicable in this version.
