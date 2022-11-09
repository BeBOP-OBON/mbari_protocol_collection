# MBARI 18S PCR

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
| 1.0.0  | 2022-04-25  | Initial release  |
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
|  Environmental DNA (eDNA) 18S metabarcoding Illumina MiSeq NGS PCR Protocol V.2 https://dx.doi.org/10.17504/protocols.io.n2vdge6 dx.doi.org/10.17504/protocols.io.n2vdge6  | Collin Closek, Anni Djurhuus, Katie Pitz, Ryan Kelly, Reiko Michisaki, Kristine Walz, Hilary Starks, Francisco Chavez, Alexandria Boehm, Mya Breitbart  | yyyy-mm-dd  |
| 18S Illumina Amplicon Protocol https://earthmicrobiome.org/protocols-and-standards/18s/ dx.doi.org/10.17504/protocols.io.nuvdew6 |  Earth Microbiome Project  | yyyy-mm-dd  |

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

This protocol is aimed at amplifying the 18S rRNA hypervariable region 9 (18S V9) in eukaryotes with a focus on microbial eukaryotes. Amplicons generated using this protocol can then be sequenced using the Illumina platform. The primers (1391F, EukBr) utilized in this protocol are based on the primer utilized in Amaral-Zettler et al. (2009), Stoek et al. (2010), and the Earth Microbiome Project (EMP).

This work was supported by NASA grant NNX14AP62A ‘National Marine Sanctuaries as Sentinel Sites for a Demonstration Marine Biodiversity Observation Network (MBON)’ funded under the National Ocean Partnership Program (NOPP RFP NOAA-NOS-IOOS-2014-2003803 in partnership between NOAA, BOEM, and NASA), and the U.S. Integrated Ocean Observing System (IOOS) Program Office.

## Summary

This method uses PCR to amplify the 18S V9 region using primers 1391F and EukBr from Amaral-Zettler et al 2009 and the Earth Microbiome Project (EMP).

## Method description and rationale

This method is applied because of its ability to amplify the target region (18S V9) across many different groups of organisms, the target region's ability to discriminate between different taxa, and the common research application of this primer set allowing the data to be compared to a reference database and other published environmental datasets.

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

1. PCR reactions were run in single 75ul reactions for each sample using 12-basepair Golay barcoded reverse primers [Amaral-Zettler et al. (2009), Stoek et al. (2010), Earth Microbiome Project] with Fluidigm adapters CS1 & CS2. All primers listed in the 5’ to 3’ direction.
  - 3 μl DNA extract template
  - 37.5 μl Amplitaq Gold Fast PCR mastermix (Applied Biosystems)
  - 3 μl each of forward and reverse primers (5 μM)
  - 28.5 μl molecular-biology grade water

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
| **Euk1391F** and Fluidigm CS1| forward | ACACTGACGACATGGTTCTACA**GTACACACCGCCCGTC** |
| **EukBr** and Fluidigm CS2 | reverse | TACGGAGCAGAGACTTGGTCT**TGATCCTTCTGCAGGTTCACCTAC** |

2. PCR reactions were run in 96-well plates with a NTC run in singleton for each plate

3. 18S thermal cycling parameters
- These parameters use a normal ramp speed

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| denature | 95° C | 10 minutes | 1 |
| denature | 94° C | 45 seconds | 35 |
| anneal | 57° C | 30 seconds | 35 |
| extension | 68 °C | 90 seconds | 35 |
| extension | 72° C | 10 minutes | 1 |
| hold | 4° C | infinity | 1 |



### Quality control, PCR clean-up

1. After PCR amplification of the marker region, PCR products were run through an agarose gel to confirm the presence of target bands and absense of non-specific amplification across environmental samples as well as the absence of amplification in no-template controls (NTCs).

2. PCR products were purified and size selected using the Agencourt AMPure XP bead system (Beckman Coulter, USA). 

3. A second agarose gel was run to confirm primer removal and retention of target amplicons after purification. 

3. Purified products were then quantified using Quant-It Picogreen dsDNA Assay (Life Technologies) on an fmax Molecular Devices Fluorometer with SoftMaxPro v1.3.1


## Basic troubleshooting guide

> Identify known issues associated with the procedure, if any.
Provide troubleshooting guidelines when available.

# REFERENCES

Amaral-Zettler LA, McCliment EA, Ducklow HW, Huse SM (2009) A Method for Studying Protistan Diversity Using Massively Parallel Sequencing of V9 Hypervariable Regions of Small-Subunit Ribosomal RNA Genes. PLOS ONE 4(7): e6372. https://doi.org/10.1371/journal.pone.0006372

Stoeck, T., Bass, D., Nebel, M., Christen, R., Jones, M. D. M., Breiner, H.-W., & Richards, T. A. (2010). Multiple marker parallel tag environmental DNA sequencing reveals a highly complex eukaryotic community in marine anoxic water. Molecular Ecology, 19 Suppl 1, 21–31. https://doi.org/10.1111/j.1365-294X.2009.04480.x

Caporaso, J. G., Lauber, C. L., Walters, W. A., Berg-Lyons, D., Huntley, J., Fierer, N., Owens, S. M., Betley, J., Fraser, L., Bauer, M., Gormley, N., Gilbert, J. A., Smith, G., & Knight, R. (2012). Ultra-high-throughput microbial community analysis on the Illumina HiSeq and MiSeq platforms. ISME J 6, 1621–1624. http://doi.org/10.1038/ismej.2012.8

# APPENDIX A: DATASHEETS

> Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance.
