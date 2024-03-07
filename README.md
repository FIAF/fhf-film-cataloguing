
## FILM DOCUMENTATION WORKFLOW - FHF ARCHIVE

The FHF film cataloguing workflow is customized, keeping with the on-practice workflow
of documentation in the film section of the archive.

- There are primarily THREE data record files in the film department.
- All the files are either in EXCEL format or PAPER format.

Types of Documentation

1. **Acquisition Log Sheet** This is the first file in the flow of data entry and maintained in Excel. This file will have all information that can and must be recorded at the time of acquisition. Important metadata fields are in this level are mostly about the acquisition information like – acquisition source, time, date, method, place etc. and a minimum record of the technical metadata like film element, gauge, color or B&W, Number of reels and cans, and at the end the initial condition assessment of the reels. Minimum acquisition related administrative metadata is also recorded at this level.

2. **Film Inspection Report** This is a physical form that the film conservators prepared while working of films. This is per reel-wise report and very detailed in recording the technical metadata. This form has minimum filmographic metadata like the film title, production, processing lab, language, language, subtitle and a field for Accession No and Item No. We generate these unique numbers manually at FHF during cataloguing.

3. **Film Archive Catalogue** FHF film cataloguing format is structured by following the rules stated by FIAF Moving Image Cataloguing Manual. It is an attempt to adapt EN16907 hierarchy in a excel format, it is still a work-in-progress, however till now at least 150 ITEMS are catalogued in this style. I am following only 2-level hierarchy model at FHF: WORK -> ITEM. Note that I use data validation lists for metadata fields with limited vocabulary like date types, sound system, color system, aspect ratio etc. to reduce error. We also have authority lists for gauge and film elements.

a) Some guidelines:
- I am keeping both WORK and ITEM as different sheets within one excel file. You can make both independent excel file.
- I have unique identifier for each entry – WORK RECORD IDENTIFIER and ITEM RECORD IDENTIFIER. To separate each, I am using W and I as prefix for each generated ID
- An accession number is generated at the end of each entry. This is a meaningfully coded alpha-numeric number.
- The cataloguer strictly refer “Film Inspection Report” while cataloguing film
- After generating the Accession Number and Item No., the same needs to be filled in the corresponding sets of “Film Inspection Report”.
- These IDs then labeled on the can (however, we have not yet proceed with physical labeling yet)

b) Some definitions of metadata fields –

| | | |
| --- | --- | --- | 
| Serial No | Common serial numbering ex. 1, 2, 3,… | |
| Work Record Identifier | Institute defined. Manually defined Alphanumeric Ex. W0059 or I-0022 | |
| Related Work | Corresponding work Id of any relation to the current work ID | Optional |
| Collection Title | Name of the collection the Item belong to. FHF has assigned names to each collection. It is often communicate the original owner (director/cinematographer/producer) or the production house name | |
| Collection ID | Very specific to FHF. Each collection is assigned a random number. The reason of the collection ID is to create some kind of internal authority record | Optional |
| Title Types | Original Title, working title, acquisition title, translated title etc. | |
| Title (WORK LEVEL) | Name of the film [Language - Year of Release] Ex. Bombay [Tamil – 1992] | |
| Also known as | Alias Name of the film (In what language) | |
| Language type | Original, inter-titled, dialogue, spoken, sung | |
| Date Type | Indian release date, processing date, acquisitions date etc. | |
| Subjects | Keywords | |
| Censorship Details | Pertaining to The Central Board of Film Certification format | Optional |
| Filmography detail | As per the credits shown in the film |  |
| Contains | List of ITEM(S) under the following WORK | |
| Note | Free text field to record additional information| |
| Cataloguer’s Note | Specific to cataloguer on the work level information | Optional |
| Accession No | Manually generated | Optional |
| Title (ITEM LEVEL) | Name of the film [Language -Element] | |
| Status | Master, Viewing, Preservation, On Loan etc. | Optional |
| Generation | Generation in the printing process of the film | |
| Condition | FHF defined condition markers | |
| Fit For | For scanning, projection etc. | Optional |
| Part of | The WORK ID number the ITEM belongs to | |

c) Searching methodology
At the moment, internal access is the primary function of the catalog. Internal access was considered when I developed and structured it.

To conduct a basic search, follow the ITEM number and then locate the appropriate WORK identifier to extract the filmographic data; alternatively, if the user's request is for any filmographic data, we will track down the WORK identifier and compile a list of the ITEMs that fall under it. For technical metadata, we are highly dependent on ITEM levels in Excel. To trace information back from the film can, we would reply to the on-can labeling of the accession number along with ITEM No.

~

*MURCHANA BORAH*   
*Senior cataloguer FILM HERITAGE FOUNDATION*    
*DATE: FEBRUARY, 2024*
