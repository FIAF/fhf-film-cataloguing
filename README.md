
## FILM DOCUMENTATION WORKFLOW

The FHF film cataloguing workflow is customized, to complement the existing documentation that is being practiced by the conservators in the film section.

- The department maintains **three primary data record files**, all of which exist either in **Excel format** or as **paper records**.

Types of Documentation

[1] **Acquisition Log Sheet** 

At FHF, we maintain an **Acquisition Log** for every item that enters the collection. This is the very first file in our data entry workflow and is maintained in Excel. This log captures all the information that can and must be recorded at the time of acquisition. The primary metadata fields at this stage relate to acquisition details—including source, date, time, method, and place of acquisition. It also includes a basic technical record, such as film element type, gauge, color (or black & white), number of reels and cans, and an initial condition assessment of the reels. In addition, essential administrative metadata related to the acquisition is recorded at this level. The Administrative Department retains control over acquisition-sensitive documentation and manages related correspondence on behalf of the archive.

[2] **Film Inspection Report** 

The second level of documentation takes place during the physical inspection of film materials by our conservators. This stage involves **a reel-wise inspection form**, completed manually by the film conservators as they work with the materials. It is highly detailed and focuses primarily on technical metadata. While the emphasis is on technical details, the form also captures basic filmographic metadata such as film title, production details, processing lab, language (credits roll), and more.

Note: Both at the acquisition and inspection stages, we ensure there is photo documentation of
the film elements, which serves as a vital visual record for reference and preservation planning.

[3] **Film Archive Catalogue** 

The FHF film cataloguing format is structured based on the guidelines set forth in the FIAF Moving Image Cataloguing Manual. It represents an ongoing effort to adapt the hierarchical structure of EN15907 into a practical Excel-based format. While the initial intention was to implement the full four-tier hierarchy of EN15907, I eventually streamlined it to a two-level model: WORK → ITEM. Given the nature and current size of the FHF collection, this simplified structure has proven to be comprehensible.

When working within a spreadsheet environment, maintaining consistency and accuracy is critical. To support this, I use data validation lists for metadata fields that rely on a controlled vocabulary—such as date types, sound systems, color systems, aspect ratios, and others. This helps reduce entry errors and ensures uniformity across records. We maintain authority lists for film elements, gauge and condition remarks – these are modeled keeping the nature of the FHF collection in mind. 

Currently, no physical labeling of film elements is in place beyond basic descriptive information. While labels do exist, the field for the formal ID is left blank at this stage. All identifiers are manually generated and recorded at the documentation level. The **FHF accession number** is an institute-defined ID number. Each film is further assigned a **Work Record Identifier** and **Item Record Identifier**, using serial-sequence numbers prefixed with **“W”** (for Work) and **“I”** (for Item) to distinguish between them.

a) Some guidelines on the workflow:
- I am currently maintaining both **WORK** and **ITEM** records as separate sheets within a single Excel file. However, these can also be exported or managed as independent Excel files if needed.
- The cataloguer strictly refers to the **Film Inspection Report** when cataloguing at the **ITEM level**. In addition, the cataloguer consults other relevant documents, such as the **Acquisition Log**, and may also request information from the **Administrative Department** if any details are missing or unclear.
- Unlike the ideal practice where identifiers are assigned earlier in the process, all the above-mentioned identifiers are currently generated at the **cataloguing stage**. Once the **Accession Number** and **Item Number** are generated, they must be entered into the corresponding **Film Inspection Report** forms.

b) Some definitions of metadata fields –

| | | |
| --- | --- | --- | 
| Work Record Identifier | A serial number prefixed with **W** to distinguish Work-level entries. |
| Related Work | Corresponding work Id of any relation to the current work ID | Optional |
| Collection Name and ID | Institution-defined fields that help group and track records by their provenance and ownership | Optional |
| Title Type and Title (Work) | Includes a **title type** field and a free-text field for the title itself. Note: I include the **language and year of release in brackets** (e.g., Title (Hindi, 1972)) to aid in searchability. Country of origin is excluded, as the collection is predominantly national. | |
| Alias or Also known as | A crucial field in the Indian context, where alternate titles are common. XXX (language) | |
| Language type | Original, inter-titled, dialogue, spoken, sung | |
| Date Type | Indian release date, processing date, acquisitions date etc. | |
| Subjects | Keywords | |
| Censorship Details | Pertaining to **The Central Board of Film Certification** format. Records certification or censorship status, if available | As per specs | |
| Agents at Work level | **Creative Credits**: Includes a **selected list of key contributors**, such as: Director, Director of Photography, Music Director, Lyricist, Sound, Editing, Playback, Other roles, as applicable. Sequence: as per the credits shown in the film. | |
| Agents at Manifestation level | This is now part of the Work, and covers entities involved in the film's production and circulation, including: Producer, Presenter, Distributor, Processing Lab, Preservation and Restoration entities  | |
| Agents at Item level | Includes a list of **agents** involved in various aspects of the item's life cycle, such as: Conservator, Scanning Supervisor, Restorer, Inspection and Cleaner, Acquisition Representative, Cataloguer | |
| Events | This field is mostly left unfilled at the Work level. At the Item level, only includes information related to the acquisition **event**. While ideally there should also be **digitization** and **restoration events**, however, excel does not allow linking these separate events that may take place multiple times. | |
| Contains | Lists all **Item Record Identifiers** (linked by serial numbers) that are associated with the given Work. | |
| Note & Cataloguer Note | A free-text field for additional information, comments, or observations about the item  | |
| Title (Item) | The title is recorded with a **title type** and a free-text field for the title itself. I include the **language** and an **abbreviation of the element** (e.g., "16mm") in brackets to improve searchability. | |
| Status | Master, Viewing, Preservation, On Loan etc. The status is typically marked as **preservation**. For **De-accessioned** items, the status is recorded as **removed**. | Optional |
| Holding Status | This field helps track whether the film is complete. Since we don’t currently track at the **manifestation level**, this serves as an additional field to indicate completeness. | |
| Holding Unit & Number of Cans | Each unit is measured in **reels**, and the total number of **cans** is recorded, along with the **can size** (e.g., 14 Reels > 14 (1000 ft.) cans) | |
| Generation | Indicated as **institutional**—the conservators record the generation of the film print (e.g., original, first-generation, etc.). | |
| Condition Remarks | FHF defined condition markers | |
| Fit For | For scanning, projection etc. | Optional |
| Access & Condition | This field links to **conservation** and **restoration events**, though due to the flat structure of Excel, the details are kept in a simplified format. The condition is noted from the **condition inspection report**, and additional details about the event (e.g., who and when) are stored in a physical file folders. A related field indicates whether a **condition report is available** ("yes" or "no") along with the file number and location for traceability | |
| Part of | This field links the item to its **associated Work identifier** | |

c) Searching methodology

Currently, the catalog is designed primarily for **internal access**, and this use case guided both its development and structure.

To conduct a basic search: To perform a basic search, users typically begin with an ITEM number, from which they locate the corresponding WORK identifier in order to extract filmographic data. In cases where a user’s request is focused on filmographic information rather than a specific item, the process is reversed: the WORK identifier is identified first, and then a list of associated ITEMs is compiled. For any technical metadata related query, we rely heavily on the ITEM-level records in the Excel catalog.

~

*MURCHANA BORAH*   
*Senior cataloguer FILM HERITAGE FOUNDATION*    
*DATE: FEBRUARY, 2024*
