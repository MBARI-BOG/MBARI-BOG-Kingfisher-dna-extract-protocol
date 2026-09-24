---
# MIOP terms
methodology_category: sample extraction and purification
project: Marine Biodiversity Observation Network (MBON)
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: Monterey Bay [GAZ:00002509]
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: upwelling [ENVO:01000005]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Jacoby Baker, Kobun Truelove, Kathleen Pitz
materials_required: Kingfisher (Thermo Scientific), vortexer [OBI:0400118], centrifuge [OBI:0400106], DNA extraction/purification instrument [OBI:0001117]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 300
personnel_required: 1
language: en
issued: 2026-09-22
audience: scientists
publisher: Monterey Bay Aquarium Research Institute
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: 500
samp_vol_we_dna_ext_unit: µL
nucl_acid_ext_lysis: physical
nucl_acid_ext_sep: magnetic beads
nucl_acid_ext: https://files.zymoresearch.com/protocols/_d4302_d4306_d4308_zymobiomics-96_magbead_dna_kit.pdf
nucl_acid_ext_kit: ZymoBIOMICS 96 Magbead DNA Kit
nucl_acid_ext_modify: Standard protocol is for extraction of 200 µL of lysed sample. We modified the KingFisher protocol to extract a total of 500 µL lysed sample across two plates.
dna_cleanup_0_1: 1.0
dna_cleanup_method: ZymoBIOMICS 96 Magbead DNA Kit
concentration: not applicable
concentration_method: Microplate Reader, Quant-iT dsDNA Assay Kit High Sensitivity
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable
---

# PROTOCOL WRITING IN PROGRESS
# Environmental DNA (eDNA) Extraction using KingFisher
## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Jacoby Baker | MBARI | 0000-0002-0673-7535 | 2025-11-25 |
| N. Kobun Truelove | MBARI | 0000-0002-2236-1849 | 2025-11-25 |
| Kathleen J. Pitz | MBARI | 0000-0002-4931-8592 | 2025-11-25 |

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Internal Protocols: Derivative or altered protocols, or other protocols in this workflow.
- External Protocols: Protcols from manufacturers or other groups. 
- Include the link to each protocol.
- Include the version number (internal) or access date (external) of the protocol when it was accessed.

#### Internal Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE |
| ------------- | ------------ | ------------ | ---------- |
| Environmental DNA (eDNA) 12S Metabarcoding PCR Protocol (with Platinum SuperFi II Taq) V.3 [Previous protocol] |  [https://github.com/MBARI-BOG/MBARI-BOG-12S-superfiII-metabarcoding-pcr-protocol/blob/main/MBARI-BOG-12S-superfiII-metabarcoding-pcr-protocol.md](https://github.com/MBARI-BOG/MBARI-BOG-12S-superfiII-metabarcoding-pcr-protocol/blob/main/MBARI-BOG-12S-superfiII-metabarcoding-pcr-protocol.md) | 3.0 | yyyy-mm-dd   | Internal      |
| Content Cell  | Content Cell | Content Cell | yyyy-mm-dd   | Content Cell      |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| ZymoBIOMICS Manual 96 MagBead DNA Kit | https://files.zymoresearch.com/protocols/_d4302_d4306_d4308_zymobiomics-96_magbead_dna_kit.pdf | ZymoBIOMICS | 2025-11-25 |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2026-09-22 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| eDNA | environmental DNA |
| PPE | Personal protective equipment |
| PCR | Polymerase chain reaction |
| EtOH | Ethanol |
| NTC | No template control |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction Blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty filter extracted and PCR amplified alongside other samples. |
| No Template Control | A type of negative control during PCR to confirm there is no contamination during the PCR process. Normally nuclease-free water run in place of DNA on a PCR. |

## BACKGROUND

### Summary

KingFisher Flex robot

### Method description and rationale

This protocol is optimized for high throughput DNA extractions of flat PVDF & GFF 25mm diameter filters.

### Spatial coverage and environment(s) of relevance

This protocol has been used to extract DNA from thousands of [sea water](environmental_medium) eDNA samples taken from stations off of South Florida coasts (Atlantic Ocean and Gulf of Mexico). Sample collection depths range from 1m to 200m in the epipelagic zone (marine photic zone [ENVO:00000209]).

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

MagBinding Buffer from the [ZymoBIOMICS 96 Magbead DNA Kit](nucl_acid_ext_kit) is classified as category 4 for acute toxicity and causes severe skin burns and serious eye damage. It is also noted that the MagBinding Buffer is harmful to aquatic life with long lasting effects. MagWash 1 from the [ZymoBIOMICS 96 Magbead DNA Kit](nucl_acid_ext_kit) is classified as category 4 for acute toxicity, is highly flammable, causes skin and serious eye irritation and may cause drowsiness or dizziness. MagWash2 from the [ZymoBIOMICS 96 Magbead DNA Kit](nucl_acid_ext_kit) is flammable, causes serious eye irritation and may cause drowsiness or dizziness. Additional details available on SDS (<https://files.zymoresearch.com/sds/_d4302_d4308_zymobiomics-96_magbead_dna_kits.pdf>). For other reagents, standard precautions for handling chemicals including wearing PPE is recommended to avoid skin and eye exposure.

### Training requirements

Basic molecular biology training (including sterile technique, pipetting) is required to conduct this protocol.

### Time needed to execute the procedure

Extracting DNA from 91 25 mm PVDF/GFF samples takes about 5 hours ([300](time_required) minutes) over two days (overnight incubation needed) including KingFisher run time.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| TissueLyser | TissueLyser II | QIAGEN | 2 min @ 30 hz |   |
| TissueLyser adapter plates |TissueLyser Adapter Set 2 x 24| QIAGEN | 2 |   |
| Centrifuge | Centrifuge 5430 | Eppendorf | 1 | Can be substituted with generic |
| Opentrons OT-2 Robot | OT-2 Pipetting Robot | Opentrons | 1 | Optional equipment for protocol; 8-Channel pipette recommended |
| KingFisher | KingFisher Flex Purification System | ThermoFisher | 1 | |
| 100-1250 uL Pipette | Integra adjustable pipette | Integra | 1 | Can be substituted with any accurate pipette |
| 20-200 uL 8 Channel Pipette | Integra adjustable pipette | Integra | 1 | Can be substituted with any accurate pipette |
| 100-1250 8 Channel Adjustable Spacer Pipette | Integra VOYAGER Adjustable Spacer Pipette | Can be substituted with any accurate pipette |
| Tube Racks | 2 mL tube 96-well tube racks | Generic | 1 | Can be any brand, must fit 2 mL tubes |
| PCR Plate Sealer | PX1 PCR Plate Sealer | BIO-RAD | 1 | Can be substituted with generic |
| **Consumable equipment** |
| PVDF Filter | Millipore Durapore, 0.22µm pore size, 25mm filter GVWP02500 | Millipore Sigma | 91 | |
| DNA/RNA Shield Collection Tubes | Zymo DNA/RNA Shield Collection Tubes R1103 | Zymo Research | 91 | Samples are stored in these tubes after collection/filtration |
| KingFisher 96 deep-well plate | KingFisher Plastics for 96 deep-well format | ThermoFisher | 6 | |
| KingFisher 96 tip comb for deep-well magnets | Kingfisher Flex 96 Deep-Well Tip Combs | ThermoFisher | 1 | |
| 96-well PCR plate | Hard-Shell PCR Plates 96-well, thin wall | BIO-RAD | 2 | Can be substituted with generic |
| Plate Seals | Peelable Foil Heat Seal cat#1814045 | BIO-RAD | 2 | Can be substituted with generic |
| 1000µL Filter Tips | Integra VIAFLO, 1250µL | Integra | 5 | (boxes) Can be substituted with generic |
| 200µL Filter Tips | Integra VIAFLO, 200µL | Integra | 3 | (box) Can be substituted with generic |
| 2.5 mL Combitips | Combitips advanced, 2.5 mL, green, colorless tips | Eppendorf | 1 | (tip) Optional for MagBinding Beads with repeater pipette |
| 10 mL Combitips | Combitips advanced, 10 mL, orange, colorless tips | Eppendorf | 3 | (tips) Optional for KF plate prep with repeater pipette |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | KimTech | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| **Chemicals** |
| 70% EtOH | Molecular bio grade ethanol | Generic | 1 | (Wash Bottle) only used for cleaning lab surfaces |
| **ZymoBIOMICS 96 MagBead DNA Kit** |
| Proteinase K | Proteinase K w/ Storage Buffer Set | Zymo Research | 3,640 | (uL) |
| MagBinding Buffer | ZymoBIOMICS MagBinding Buffer | Zymo Research | 115.2 | (mL) |
| MagBinding Beads | ZymoBIOMICS MagBinding Beads | Zymo Research | 2.4 | (mL) |
| MagWash 1 | ZymoBIOMICS MagWash 1 | Zymo Research | 48 | (mL) |
| MagWash 2 | ZymoBIOMICS MagWash 2 | Zymo Research | 86.4 | (mL) |
| DNAse/RNAse Free Water | ZymoBIOMICS DNAse/RNAse Free Water | Zymo Research | 11.04 | (mL) |


- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.


## STANDARD OPERATING PROCEDURE

### DNA extraction Protocol

#### Preparation

1. Sterilize all workspaces and durable equipment with 70% EtOH.
2. Create a plate template organizing the samples into wells of a 96 well plate.
3. Resuspend powdered Proteinase K according to manufacture direction (e.g., 135 mg Proteinase K powder + 6.5 mL Proteinase K Storage Buffer).
  
#### Extraction
Sample Lysis (day 1)

1. Remove preserved filter from freezer, order in tube rack based on the template, and bring to room temperature.
2. Make sure caps are tightly sealed. Transfer samples to the Tissuelyser adapters (24 per adapter) and homogenize samples at 30 hz for 2 minutes. (This will be done in two batches).
3. After homogenization, centrifuge the DNA/RNA Shield collection tubes (samples) at ≥ 10,000xg for 1 minute.
4. Return the samples to the tube rack in the correct order.
5. Carefully remove caps of the DNA/RNA Shield collection tubes and add 40 uL of Proteinase K to each samples. Carefully replace caps and tighten well.
6. Place sample tubes in a secured rack and incubate at 55 C overnight with a slow rotation.

Run Kingfisher (day 2)

7. Take samples out of the incubator and allow to cool.
8. While the samples are cooling, prepare KingFisher plates:

   - Sample Plate 1: Add 600 µl of MagBinding Buffer and 25 µl of MagBinding beads to each well.
   - Sample Plate 2: Add 600 µl of MagBinding Buffer to each well (do not add MagBinding beads to Sample Plate 2; the binding capacity of these beads are high enough that the initial 25ul are plenty).
   - MagWash 1: Add 500 µl of ZymoBiomics MagWash 1 to each well.
   - MagWash 2-1: Add 900 µl of ZymoBiomics MagWash 2 to each well.
   - Wash 2-2: Add 900 µl of ZymoBiomics MagWash 2 to each well.
   - Elution: Add 115 µl of ZymoBiomics RNAse Free Water to each well.

9. After the samples have cooled, centrifuge tubes at ≥ 10,000 x g for 1 min to pellet the beads and leave the sample as supernatant. Return samples to tube rack in the correct order.
10. Using a 1250 uL Integra 8-channel Adjustable Spacer Pipette, gently pipette 500 uL of sample supernatant and dispense 250 uL into its respective well for KingFisher Sample Plate 1, and Sample Plate 2. Repeat for each column. Alternatively, this can be done on a sample by sample basis if no adjustable spacer pipette is available.
10. Turn on the KingFisher instrument and computer and open up the BindIt software for KingFisher.
11. Choose correct protocol for a 2-plate run.
12. Press start and save a new run file.
13. Follow along with instructions on the KingFisher screen to load the appropriate plates onto the KingFisher carousel and ensure all plates are in the correct position (including the tip-comb plate). Once the last plate has been added, the run will begin.
14. Run will last ~1hr 5min for a 2-plate protocol.
15. Once the run is complete, appropriately discard the wash, sample, and tip plates. DO NOT THROW OUT ELUTION PLATE.
16. Transfer samples in Elution plate (~115 uL per well) and split between two permanent 96-well PCR plates (one for lab use and one to archive) for long term storage of DNA at –80 °C. Make sure to keep the samples in the correct sample template order. Seal the plates with the heat sealer
17. Turn off KingFisher instrument and computer.

### Quality control

- An extraction blank (negative control) is included in every extraction set (91 samples + 6 extraction blanks). All samples and controls are then quantified to confirm DNA concentration. Samples are also PCR amplified with a NTC and positive controls.

### Basic troubleshooting guide
Not applicable.

## REFERENCES
Not applicable.

## APPENDIX A: DATASHEETS
Not applicable.
