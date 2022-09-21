# MBARI 12S PCR

MIOP protocol template

## AUTHORS

| PREPARED BY All authors known to have contributed to the preparation of this protocol, including those who filled in the template.  | AFFILIATION | ORCID (visit https://orcid.org/ to register) | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Jacoby Baker  | MBARI  |   | yyyy-mm-dd |
| Kobun Truelove  | MBARI  |   | yyyy-mm-dd |
| Kathleen Johnson Pitz  | MBARI  | 0000-0002-4931-8592  | 2022-04-25 |

## PROTOCOL REVISION RECORD

Version numbers start at "1.0.0" when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0). Please store all versions in the gDrive folder designated to your institute.

| VERSION  | RELEASE DATE This is the date when a given protocol version was finalised | DESCRIPTION OF REVISIONS Please include a brief description of what was changed relative to the previous version |
| ------------- | ------------- | ------------- |
| 1.0.0  | 2022-09-21  | Initial release  |
|    |    |    |

## RELATED PROTOCOLS IN YOUR FOLDER

This is a list of other protocols deposited in your folder which should be known to users of this protocol. For example, if you create a derivative or altered protocol, you would link to the original protocol in the section below. Please include the link to each related protocol. Also include the version number of that protocol when you linked to it.

| PROTOCOL NAME AND LINK  | VERSION The version of the protocol you linked to | RELEASE DATE This is the date corresponding to the version listed to the left |
| ------------- | ------------- | ------------- |
|    |    | yyyy-mm-dd  |
|    |    | yyyy-mm-dd  |

## RELATED EXTERNAL PROTOCOLS

This is a list of other protocols that are not in your folder which should be known to users of this protocol. These include, e.g., kit manuals. Please upload all relevant external protocols to Appendix A and link to them here.

| EXTERNAL PROTOCOL NAME AND LINK  | ISSUER / AUTHOR Please note who authored the protocol (this may also be a company name) | ACCESS DATE This is the date you downloaded or scanned the protocol and uploaded it. |
| ------------- | ------------- | ------------- |
|  Environmental DNA (eDNA) 12S Metabarcoding Illumina MiSeq NGS PCR Protocol (Touchdown) V.2 https://dx.doi.org/10.17504/protocols.io.bcppivmn  dx.doi.org/10.17504/protocols.io.bcppivmn  | Katie Pitz, Nathan Truelove, Charles Nye, Reiko P Michisaki, Francisco Chavez  | 2020-02-18  |


## ACRONYMS AND ABBREVIATIONS

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| MBARI   | Monterey Bay Aquarium Research Institute   |
| PCR   | polymerase chain reaction   |
|  NTC  |  no template control  |

## GLOSSARY

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
|  amplicon  | A piece of DNA or RNA that is the source and/or product of amplification or replication events (https://en.wikipedia.org/wiki/Amplicon)  |

# BACKGROUND

This protocol is aimed at amplifying the the hypervariable region of the mitochondrial DNA 12S rRNA gene in eukaryotes. The primers (MiFish-U-F & MiFish-U-R) used in this protocol were developed by Miya et al., 2015 for metabarcoding environmental DNA (eDNA) from fishes.

Touchdown thermocycling protocols were adapted from the CALeDNA group.

This work was supported by NASA grant NNX14AP62A ‘National Marine Sanctuaries as Sentinel Sites for a Demonstration Marine Biodiversity Observation Network (MBON)’ funded under the National Ocean Partnership Program (NOPP RFP NOAA-NOS-IOOS-2014-2003803 in partnership between NOAA, BOEM, and NASA), and the U.S. Integrated Ocean Observing System (IOOS) Program Office.

Citations
1) Miya M et al. 2015 MiFish, a set of universal PCR primers for metabarcoding environmental DNA from fishes: detection of more than 230 subtropical marine species. R.Soc.opensci. 2: 150088. http://dx.doi.org/10.1098/rsos.150088
2) CALeDNA. 2019. University of California Conservation Genomics Consortium.

## Summary

This method uses PCR to amplify a hyperviariable region of the mitochondrial 12S gene using primers MiFish-U-F & MiFish-U-R from  Miya et al., 2015.

## Method description and rationale

This method is applied because of its ability to amplify the target region (12S) targeting bony fishes, the target region's ability to discriminate between different fishes, and the common research application of this primer set allowing the data to be compared to a reference database and other published environmental datasets.

## Spatial coverage and environment(s) of relevance

- ocean [ENVO:00000015]
- freshwater lake [ENVO:00000021]

# PERSONNEL REQUIRED

- 1 technician

## Safety

> Identify hazards associated with the procedure and specify protective equipment and safety training required to safely execute the procedure

## Training requirements

> Specify technical training required for the good execution of the procedure.

## Time needed to execute the procedure

> Specify how much time is necessary to execute the procedure.

# EQUIPMENT

| DESCRIPTION e.g. filter | PRODUCT NAME AND MODEL Provide the official name of the product | MANUFACTURER Provide the name of the manufacturer of the product. | QUANTITY Provide quantities necessary for one application of the standard operating procedure (e.g. number of filters). | REMARK For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure. |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| ultraviolet light source [OBI:0002900] |  |  |  |  |
| PCR instrument [OBI:0000989] |   |   |   |   |
| electrophoresis system [OBI:0001053] |   |   |   |   |
| fluorometer [OBI:0400143] | FMAX Fluorometer | Molecular Devices |   | with SoftMaxPro v1.3.1 |
| **Consumable equipment** |
| Agarose gel |   |   | 2 |   |
| Agencourt AMPure XP bead system |  | Beckman Coulter, USA  |   |   |
| Quant-It Picogreen dsDNA Assay |   | Life Technologies |   |   |
| **Chemicals** |
| 10% Bleach |   |   |   |   |
| 70% Ethanol |   |   |   |   |
| RNase Away |   |   |   |   |
| Amplitaq Gold Fast PCR mastermix |   |   |   |   |
| molecular-biology grade water |   |   |   |   |
| forward and reverse primers (5 μM) |   |   |   |   |

# STANDARD OPERATING PROCEDURE

## Protocol

### Preparation

1.  Disinfect work surfaces with 10% bleach, followed by 70% ethanol.

2.  RNase Away and pipets with RNase Away

3. UV pipets, molecular grade water, and tube racks for 20 minutes prior to starting protocol.

### PCR

1. PCR reactions were run in triplicate 25 μl reactions for each sample using MiFish_U primers (Miya et al. 2015) with Fluidigm adapters CS1 & CS2. All primers listed in the 5’ to 3’ direction.

  - 1 μl DNA extract template
  - 12.5 μl Amplitaq Gold™ Fast PCR mastermix (Applied Biosystems)
  - 1 μl forward primer (10 μM)
  - 1 μl reverse primer (10 μM)
  - 9.5 μl molecular-grade, nuclease-free water

- Fluidigm CS1 + **12S MiFish_U** (forward):
  >ACACTGACGACATGGTTCTACA**GTCGGTAAAACTCGTGCCAGC**

- Fluidigm CS2 + **12S MiFish_U** (reverse):
  > TACGGTAGCAGAGACTTGGTCT**CATAGTGGGGTATCTAATCCCAGTTTG**

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
| Fluidigm CS1 + **12S MiFish_U**| forward | ACACTGACGACATGGTTCTACA**GTCGGTAAAACTCGTGCCAGC** |
| Fluidigm CS2 + **12S MiFish_U** (reverse) | reverse | TACGGTAGCAGAGACTTGGTCT**CATAGTGGGGTATCTAATCCCAGTTTG** |

2. PCR reactions were performed in 96-well plates with a no-template control (NTC) for each PCR plate, for a total of 3 PCR negative controls. An artificial community was used as a positive control.

3. Primary 12S cycling parameters, using the CALeDNA Touchdown method:

```
1. 95°C 15 minutes
*13 cycles of the following 3 steps (step 3 changes -1.5°C each cycle; "touchdown")
2. 94°C 30 seconds*
3. 69.5°C 30 seconds*
4. 72°C 90 seconds*
*25 cycles of the following 3 steps
5. 94°C 30 seconds*
6. 50°C 30 seconds*
7. 72°C 45 seconds*
8. 72°C 10 minutes
9. 4°C HOLD
```

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| denature | 95° C | 15 minutes | 1 |
| denature | 94° C | 30 seconds | 13 |
| anneal | 69.5° C (-1.5° C each cycle) | 30 seconds | 13 |
| extension | 72 °C | 90 seconds | 13 |
| denature | 94° C | 30 seconds | 25 |
| anneal | 50° C | 30 seconds | 25 |
| extension | 72 °C | 45 seconds | 25 |
| extension | 72° C | 10 minutes | 1 |
| hold | 4° C | infinity | 1 |



### Quality control, PCR clean-up

1. After primary PCR amplification of the marker region, the PCR products were pooled (75 μL total per unique environmental sample) and run through a 2% agarose gel to confirm the presence of target bands and absence of non-specific amplification across environmental samples.

2. Primary PCR products were purified and size selected using the Agencourt AMPure XP bead system (Beckman Coulter, USA) at 1.2x volume beads to product. 

3. A second agarose gel was run to confirm primer removal and retention of target amplicons after purification.

4. NTCs were also tested using a Qubit dsDNA 1x high sensitivity kit to ensure no amplification.

Secondary amplification and NGS were performed at Michigan State University's Research Technology Support Facility (RTSF).

(link to Protocol ###)

## Basic troubleshooting guide

> Identify known issues associated with the procedure, if any.
Provide troubleshooting guidelines when available.

# REFERENCES


# APPENDIX A: DATASHEETS

> Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance.
