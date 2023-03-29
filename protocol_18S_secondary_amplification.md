# Protocol Template

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
| protocol_18S_PCR.md   |    | yyyy-mm-dd  |
|  protocol_18S_sequencing  |    | yyyy-mm-dd  |

## RELATED EXTERNAL PROTOCOLS

This is a list of other protocols that are not in your folder which should be known to users of this protocol. These include, e.g., kit manuals. Please upload all relevant external protocols to Appendix A and link to them here.

| EXTERNAL PROTOCOL NAME AND LINK  | ISSUER / AUTHOR Please note who authored the protocol (this may also be a company name) | ACCESS DATE This is the date you downloaded or scanned the protocol and uploaded it. |
| ------------- | ------------- | ------------- |
|  Environmental DNA (eDNA) 18S metabarcoding Illumina MiSeq NGS PCR Protocol V.2 https://dx.doi.org/10.17504/protocols.io.n2vdge6 dx.doi.org/10.17504/protocols.io.n2vdge6  | Collin Closek, Anni Djurhuus, Katie Pitz, Ryan Kelly, Reiko Michisaki, Kristine Walz, Hilary Starks, Francisco Chavez, Alexandria Boehm, Mya Breitbart  | yyyy-mm-dd  |
| 18S Illumina Amplicon Protocol https://earthmicrobiome.org/protocols-and-standards/18s/ dx.doi.org/10.17504/protocols.io.nuvdew6 |  Earth Microbiome Project  | yyyy-mm-dd  |

## ACRONYMS AND ABBREVIATIONS

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|    |    |

## GLOSSARY

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
|    |    |
|    |    |

# BACKGROUND

This protocol is aimed at amplifying the 18S rRNA hypervariable region 9 (18S V9) in eukaryotes with a focus on microbial eukaryotes. Amplicons generated using this protocol can then be sequenced using the Illumina platform. The primers (1391F, EukBr) utilized in this protocol are based on the primer utilized in Amaral-Zettler et al 2009 and the Earth Microbiome Project (EMP).

This work was supported by NASA grant NNX14AP62A ‘National Marine Sanctuaries as Sentinel Sites for a Demonstration Marine Biodiversity Observation Network (MBON)’ funded under the National Ocean Partnership Program (NOPP RFP NOAA-NOS-IOOS-2014-2003803 in partnership between NOAA, BOEM, and NASA), and the U.S. Integrated Ocean Observing System (IOOS) Program Office.

## Summary

Insert a short description of the background for the method/protocol (e.g. why and for which purpose do you perform water sampling).
Please provide a brief summary of your method including, as appropriate, a brief description of what techniques your best practice is about, which ocean environments or regions it targets, the primary sensors covered, what type of data/measurements/observing platform it covers, limits to its applicability.

## Method description and rationale

Insert a short description of the functioning principal of the methodology used in the protocol (i.e. how does the method work?). Please note that this is different from the step-by-step description of the protocol procedure.
Insert a short statement explaining why the specific methodology used in the protocol has been selected (e.g. it is highly reproducible, highly accurate, procedures are easy to execute etc….).

## Spatial coverage and environment(s) of relevance

If applicable, please specify the region where the protocol is applied. For regional term guidance see here. If applicable, please indicate here the environment(s) of relevance for the protocol, e.g. Abyssal plain. Select from the ENVO terminology.

# PERSONNEL REQUIRED

Insert the number of technicians, data managers, and scientists required for the good execution of the procedure

## Safety

Identify hazards associated with the procedure and specify protective equipment and safety training required to safely execute the procedure

## Training requirements

Specify technical training required for the good execution of the procedure.

## Time needed to execute the procedure

Specify how much time is necessary to execute the procedure.

# EQUIPMENT

| DESCRIPTION e.g. filter | PRODUCT NAME AND MODEL Provide the official name of the product | MANUFACTURER Provide the name of the manufacturer of the product. | QUANTITY Provide quantities necessary for one application of the standard operating procedure (e.g. number of filters). | REMARK For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure. |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
|  |   |   |   |   |
|  |   |   |   |   |
|  |   |   |   |   |
|  |   |   |   |   |
| **Consumable equipment** |
|  |   |   |   |   |
|  |   |   |   |   |
| **Chemicals** |
|  |   |   |   |   |
|  |   |   |   |   |

# STANDARD OPERATING PROCEDURE

In the following SOP, please use the exact names of equipment as noted in the table above.

## Protocol

### Preparation

1.  Complete "protocol_18S_PCR.md" and ship samples to Michigan State University RTSF Genomics Core.

### _The following steps are performed by [MSU's RTSF Genomics Core](https://rtsf.natsci.msu.edu/genomics/)_

### Secondary Amplification

10. Secondary amplification and NGS were performed at Michigan State University's Research Technology Support Facility (RTSF).
    An aliquot of 20 μL from each purified primary PCR product was sent to RTSF Genomics Core at MSU for secondary PCR amplification with primers which targeted the CS1/CS2 ends of the primary PCR products and added dual indexed, Illumina compatible adapters with barcodes.
 - PE1-BC-CS1 (forward): `AATGATACGGCGACCACCGAGATCT-[i5-BC(index 2)]-ACACTGACGACATGGTTCTACA`
 - PE2-BC-CS2 (reverse): `CAAGCAGAAGACGGCATACGAGAT-[i7-BC(index 1)]-TACGGTAGCAGAGACTTGGTCT`


 | Primer Name | Direction | Sequence (5’ -> 3’)|
 | ----- | ----- | ----- |
 | PE1-BC-CS1 | forward | AATGATACGGCGACCACCGAGATCT-[i5-BC(index 2)]-ACACTGACGACATGGTTCTACA |
 | PE2-BC-CS2 | reverse | CAAGCAGAAGACGGCATACGAGAT-[i7-BC(index 1)]-TACGGTAGCAGAGACTTGGTCT |


11. The secondary PCR amplifications were carried out in 15 μL reactions, using 1 μL original pooled PCR product.
 - 6 μl 2.5X HotMaster Mix
 - 7 μl DI water
 - 1 μl Primer Mix (6uM)
 - 1 μl original eDNA PCR product
12. Secondary 18S cycling parameters:
 ```
 95°C 3 minutes
 15 cycles of the following three steps:
 - 95°C 15 seconds
 - 60°C 30 seconds
 - 72°C 1 minute
 72°C 3 minutes
 25°C Hold
 ```
 | PCR step | Temperature | Duration | Repetition |
 | ----- | ----- | ----- | ----- |
 | denature | 95° C | 3 minutes | 1 |
 | denature | 95° C | 15 seconds | 15 |
 | anneal | 60° C | 30 seconds | 15 |
 | extension | 72 °C | 1 minute | 15 |
 | extension | 72° C | 3 minutes | 1 |
 | hold | 25° C | infinity | 1 |

 11. An agarose gel was run after secondary PCR to confirm the presence of target bands and absence of non-specific amplification across environmental samples as well as the absence of amplification in NTCs.
 12. After secondary PCR, products were run through Invitrogen SequalPrep Normalization Plate (ThermoFisher Scientific) using manufacturer's protocol to create pooled library.


### Quality control, PCR clean-up

1. After PCR amplification of the marker region, PCR products were run through an agarose gel to confirm the presence of target bands and absense of non-specific amplification across environmental samples as well as the absence of amplification in no-template controls (NTCs).
2. PCR products were purified and size selected using the Agencourt AMPure XP bead system (Beckman Coulter, USA). 
3. A second agarose gel was run to confirm primer removal and retention of target amplicons after purification. 
3. Purified products were then quantified using Quant-It Picogreen dsDNA Assay (Life Technologies) on an fmax Molecular Devices Fluorometer with SoftMaxPro v1.3.1


## Basic troubleshooting guide

Identify known issues associated with the procedure, if any.
Provide troubleshooting guidelines when available.

# REFERENCES

Insert all references cited in the document.
Please insert full DOI address when available, e.g. http://doi.dx.org/10.1007/s11258-014-0404-1

# APPENDIX A: DATASHEETS

Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance.
