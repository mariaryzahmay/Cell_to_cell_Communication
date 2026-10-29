# Cell_to_cell_Communication

# Trophoblast–Decidual Cell Communication: A Bioinformatics Investigation of CXCL12–CXCR4 Signaling

*A proposed paracrine signaling model integrating evidence from the Human Protein Atlas, OmniPath, STRING, and IntAct.*

## Overview

Cell-to-cell communication is essential for coordinating cellular activities and maintaining physiological homeostasis. At the maternal–fetal interface, placental trophoblasts communicate with maternal cells through signaling molecules that contribute to implantation, placental development, and tissue remodeling.


**Biological Question:** How might trophoblast-derived CXCL12 interact with CXCR4 on maternal decidual stromal cells and influence processes involved in the establishment of the maternal–fetal interface?

The proposed signaling system consists of:

- **Sender cell:** Placental trophoblast, specifically first-trimester human trophoblast cells
- **Signaling ligand:** CXCL12
- **Proposed receptor:** CXCR4
- **Receiver cell:** Decidual stromal cell
- **Communication type:** Paracrine signaling
- **Proposed response:** Increased cellular invasion and changes in matrix metalloproteinase activity

---

## Placental Trophoblasts as the Signaling Source

Placental trophoblasts were selected as the sender cells because they form important cellular components of the placenta and participate in interactions with maternal tissues. Different trophoblast subtypes have specialized functions in placental development and maternal–fetal exchange.

The Human Protein Atlas (HPA) was used to examine trophoblast-associated gene expression and investigate the expression of CXCL12.

### CXCL12 Expression and Secretion

CXCL12, also known as stromal cell-derived factor 1 (SDF-1), is a chemokine involved in cellular signaling and migration.

Published research has reported that human trophoblast cells express and spontaneously secrete CXCL12 in vitro. Experimental studies have also investigated the effects of CXCL12 on trophoblast behavior and communication with decidual stromal cells.

These findings provide biological support for selecting CXCL12 as the candidate signaling molecule. However, the specific expression level in a database must be recorded from the selected cell population rather than assumed from published studies.


<img width="2358" height="1372" alt="IMG_3045" src="https://github.com/user-attachments/assets/54cb2f3c-15c2-4ec8-8328-68c747dff89a" />
**Figure 1.** Human Protein Atlas evidence for CXCL12 expression in placental trophoblast cells.

## CXCR4 as a Candidate Receiver Receptor

CXCR4 is a chemokine receptor that recognizes CXCL12. It has been investigated in trophoblast cells and maternal decidual cells.

Decidual stromal cells were selected as the receiver population because they participate in maternal tissue remodeling and interactions with invading trophoblasts during early pregnancy.

Published research has reported that CXCL12 released by trophoblast cells can promote the invasive ability of decidual stromal cells through CXCR4-mediated signaling.


<img width="1257" height="979" alt="IMG_3048" src="https://github.com/user-attachments/assets/a32b110a-1e73-4377-b4d9-d316129212ca" />

**Figure 2.** Human Protein Atlas evidence for CXCR4 expression in the selected receiver cell 


### CXCL12 (UniProt P48061), 46 Intercell records

| Field | Annotation |
|---|---|
| Parent classification | ligand (30), secreted (8), extracellular (4), receptor (2), intracellular (2) |
| Aspect | functional (32), locational (14) |
| Ligand designation | Yes (parent "ligand", 30 records) |
| Secreted / extracellular localization | Yes (location "Secreted"; extracellular also annotated) |
| Transmitter role | Not shown in Causality column; ligand parent indicates sender role |
| Score | 7 |
| Source type | resource_specific (41), composite (5) |
| Databases | UniProt_keyword, UniProt_location, HPA_secretome, connectomeDB2020, Baccin2019, Matrisome, Cellinker, OmniPath |

<img width="2358" height="1384" alt="IMG_3054" src="https://github.com/user-attachments/assets/3971ff2d-a8dd-47b5-bc3c-94182839149f" />

**Figure 3.** OmniPath Intercell annotations for CXCL12 in humans. The protein is annotated as a secreted ligand, with extracellular localization supported by multiple 

### CXCR4 (UniProt P61073), 72 Intercell records

| Field | Annotation |
|---|---|
| Parent classification | receptor, transmembrane, transmembrane_predicted, plasma_membrane, cell_surface, extracellular, cell_adhesion, intracellular |
| Aspect | locational (visible rows) |
| Receptor designation | Yes ("receptor" listed under Parent) |
| Localization | Transmembrane |
| Scope | generic (one row specific) |
| Receiver role | Not shown in Causality column |
| Score | Not shown in screenshot |
| Databases | Not shown in screenshot |

<img width="2358" height="1180" alt="IMG_3055" src="https://github.com/user-attachments/assets/c55f1fd2-7eec-4a5f-a3d9-beac8223b2d1" />

**Figure 4.** OmniPath Intercell annotations for CXCR4 in humans. The protein is annotated as a transmembrane receptor located at the cell surface.


---

## Functional Protein Association Network from STRING

STRING was used to investigate proteins functionally associated with CXCR4 in *Homo sapiens*.

<img width="2360" height="1258" alt="IMG_3059" src="https://github.com/user-attachments/assets/410697d2-3e55-4850-b2bf-5271879e4b5b" />
**Figure 5.** STRING functional protein association centered on CXCR4 in Homo sapiens. The network contains 11 proteins: CXCL12, CXCR4, ACKR3, CCR5, CD4, GNAI1, GNAI2, GNB1, GNG2, ARRB1 and ITCH.

## Functional Enrichment (GO Biological Process)

| Enriched term | Category | Signal (approx.) | FDR (approx., from color bin) |
|---|---|---|---|
| Chemokine-mediated signaling pathway | GO Biological Process | 2.67 | ~2.8e-06 |
| Cytokine-mediated signaling pathway | GO Biological Process | 1.53 | ~1.1e-04 |
| Response to prostaglandin E | GO Biological Process | 1.81 | ~3.8e-04 |
| Symbiont entry into host cell | GO Biological Process | 1.62 | ~3.8e-04 |
| CXCL12-activated CXCR4 signaling pathway | GO Biological Process | 1.59 | ~1.3e-03 |
| Adenylate cyclase-modulating G protein-coupled receptor signaling pathway | GO Biological Process | 1.49 | ~3.8e-04 |
| Adenylate cyclase-activating G protein-coupled receptor signaling pathway | GO Biological Process | 1.36 | ~1.3e-03 |
| Response to alcohol | GO Biological Process | 1.44 | ~3.8e-04 |
| Positive regulation of cytosolic calcium ion concentration | GO Biological Process | 1.38 | ~1.3e-03 |
| Calcium-mediated signaling | GO Biological Process | 1.37 | ~1.3e-03 |

Gene counts are shown only as circle sizes (legend: 2, 4, 6). Chemokine-mediated signaling has the largest circle (about 6). Exact counts, GO identifiers, strength and the proteins in each term are not shown in the plot.

<img width="2360" height="1344" alt="IMG_3062" src="https://github.com/user-attachments/assets/0a650d9c-53d8-461f-a795-c7b80638a9fe" />

**Figure 6.** STRING Gene Ontology Biological Process enrichment for the CXCL12–CXCR4 network. Dot position is signal, dot size is gene count and color is FDR, with terms grouped at similarity 0.8. Chemokine-mediated signaling pathway is the strongest and most significant term.

### Interpretation

The enriched terms are dominated by chemokine and cytokine signaling, G protein-coupled receptor signaling (the adenylate cyclase terms) and calcium signaling. This fits CXCL12 acting as a secreted ligand that signals through the CXCR4 receptor and its G protein partners (GNAI1, GNAI2, GNB1, GNG2) and ARRB1. The CXCL12-activated CXCR4 signaling pathway term directly matches the ligand–receptor pair. In the trophoblast–decidual setting, this supports the idea that CXCL12 released by the sender cell could signal to CXCR4-expressing receiver cells at the maternal–fetal interface. ACKR3 appears as an additional CXCL12-binding receptor in the network. Terms such as symbiont entry into host cell and response to alcohol most likely come from shared network members (CD4, CCR5, CXCR4) and are not specific to placental biology.

---

## Experimental Interaction Evidence from IntAct

IntAct will be examined for experimentally reported molecular interactions involving CXCR4 and proteins identified in the STRING network.

## IntAct Validation (CXCR4)

### Selected interaction

| Parameter | Information |
|---|---|
| Protein pair | CXCR4 (P61073) – ACKR3/CXCR7 (confirm accession on the IntAct page) |
| Organism | Experimental host: *Homo sapiens* (HEK293 embryonic kidney cells) |
| Interaction type | Physical association |
| Experimental method | Anti tag coimmunoprecipitation |
| Experimental system | HEK293 cells (co-expression of CXCR4 and ACKR3; figure 2A/B/C) |
| IntAct accession | EBI-21294877 |
| Publication | Décaillot FM, Kazmi MA, Lin Y, Ray-Saha S, Sakmar TP, Sachdev P (2011), *J Biol Chem* |
| PubMed ID | 21730065 |

### Supporting record

| Parameter | Information |
|---|---|
| Protein pair | CXCR4 – ACKR3/CXCR7 |
| Organism | Experimental host: *Mus musculus* (albino neuroblastoma cells) |
| Interaction type | Colocalization |
| Experimental method | Confocal microscopy |
| IntAct accession | EBI-21298271 (IMEx IM-26941-9) |
| Publication | (PubMed 21730065), figure 2d |

<img width="2360" height="1245" alt="IMG_3067" src="https://github.com/user-attachments/assets/e960bbd2-7dc7-496f-93cf-97599b789107" />

**Figure 7.** IntAct network for CXCR4 (Homo sapiens and Mus musculus records). Edge color shows MI score and edge width shows the number of supporting evidence 

---

## Proposed Model of Trophoblast–Decidual Cell 

<img width="2520" height="1426" alt="att i1835-z-p23PNkN9-zEmGm8IGbOL3iffALevhIygzuc" src="https://github.com/user-attachments/assets/2ae36a55-87bb-4c3d-a566-ee4567c846dd" />

**Figure 8.** Proposed model of paracrine CXCL12–CXCR4 communication between placental trophoblasts and maternal decidual stromal cells.

### Biological Interpretation

The proposed model describes how trophoblast-derived CXCL12 may influence maternal decidual stromal cells through CXCR4. Published experimental evidence supports the biological relevance of this ligand–receptor system in the early maternal–fetal interface.

The database analyses will provide complementary information about gene expression, signaling annotations, protein associations, and experimentally reported molecular interactions. These evidence types must be interpreted separately: gene expression supports cellular plausibility, curated annotations support documented signaling roles, and interaction experiments provide evidence about particular molecular Paragraph form please each number

## Synthesis of Findings
——
### 1. Sender cell
The sender cell is the human first-trimester placental trophoblast. These cells drive placental development and invade the maternal decidua, so they communicate directly with maternal cells at the maternal–fetal interface.

### 2. Signaling molecule and evidence
The signaling molecule is CXCL12. In OmniPath, CXCL12 (P48061) is annotated as secreted, with location records from UniProt and HPA_secretome among others, and it carries 30 ligand-parent annotations. These database annotations are separate from the published evidence. Wu et al. (2004) reported CXCR4 and CXCL12 expression in first-trimester human trophoblast cells, and Wu et al. (2005) reported that these cells express and secrete CXCL12. RNA expression in the Human Protein Atlas is a third and distinct line of evidence, so insert your own HPA result (cell type and expression level) here.

### 3. Receptor and receiver cell
The receptor is CXCR4, which OmniPath annotates as a transmembrane receptor, and the receiver is the maternal decidual stromal cell. In first-trimester decidual stromal cells, CXCL12 and trophoblast-conditioned medium increased migration and invasion, and neutralizing antibodies against CXCL12 or CXCR4 abolished the effect. A related study is Ren et al. 2012 (Hum Reprod 27:366–74).

### 4. Type of signaling
The mechanism is paracrine signaling. One study concluded that trophoblast-derived CXCL12 promoted migration and invasion of decidual epithelial cells through CXCR4 rather than CXCR7 in a paracrine manner, although that study used epithelial cells rather than stromal cells. CXCL12 also acts in an autocrine manner, because trophoblast-derived CXCL12 increases trophoblast invasiveness by binding CXCR4.

### 5. Most relevant STRING proteins
The STRING network contains 11 proteins. GNAI1, GNAI2, GNB1 and GNG2 are G protein subunits and connect to the GPCR and adenylate cyclase terms in the enrichment. ARRB1 is β-arrestin, and the title of the IntAct publication describes the CXCR7/CXCR4 heterodimer recruiting β-arrestin. ACKR3 is a second CXCL12-binding receptor that forms a heterodimer with CXCR4. CCR5 and CD4 are related chemokine-receptor and HIV entry proteins, which explains the symbiont entry term but makes them less relevant to placenta. ITCH is an E3 ubiquitin ligase, and I would describe it only as a network member unless you find a source linking it to CXCR4 regulation. STRING alone does not place any of these proteins in a pathway sequence.

### 6. Enriched process
The strongest term was chemokine-mediated signaling pathway (GO Biological Process), with a signal of about 2.67, an FDR of about 2.8e-06 and a gene count of about 6. Check these values against the Analysis table. The directly matching term was CXCL12-activated CXCR4 signaling pathway, with an FDR of about 1.3e-03. These results fit CXCL12 acting through CXCR4, and the GPCR and calcium terms point to receptor signaling that could drive migration and invasion. The GO identifiers and the proteins in each term are not visible in your screenshot, so copy them from the table.

### 7. IntAct
The protein pair was CXCR4 and ACKR3 (CXCR7), and the main record was EBI-21294877. It is classified as a physical association and was detected by anti-tag coimmunoprecipitation in human HEK293 cells. The supporting publication is Décaillot et al. 2011 (J Biol Chem, PubMed 21730065). A second record, EBI-21298271, reports colocalization by confocal microscopy in mouse neuroblastoma cells. This evidence shows a physical association between the two receptors. It does not prove direct binding, and it does not place ACKR3 downstream of CXCR4 after CXCL12 stimulation.

### 8. Strong support versus inference
The strongly supported parts are trophoblast CXCL12 expression and secretion, and the CXCR4-dependent increase in decidual stromal cell migration and invasion. OmniPath, STRING and IntAct give complementary database support. The specific downstream proteins and their order remain inference, because STRING and IntAct report associations rather than stepwise evidence. The MMP-2/MMP-9 link is also inference (see question 9).

### 9. Expected response in the receiver cell
The expected response is increased decidual stromal cell migration and invasion, based on the studies cited above. The MMP-2/MMP-9 link needs care. The evidence I found is from trophoblast cells: in HTR8/SVneo trophoblast cells, SDF-1 raised MMP-2 and MMP-9 expression, and this was blocked by inhibiting the receptor. I found no direct evidence of this link in decidual stromal cells, so the dashed arrow in your diagram is appropriate, and the text should call MMP-2/MMP-9 a proposed mechanism borrowed from trophoblast data. The response also isn't simply "more invasion," because trophoblast-derived CXCL12 can raise CD82 expression in decidual stromal cells, which controls trophoblast over-invasion. The magnitude and mechanism should not be generalized beyond the cells and conditions used in the studies.


### References and Database Resources

- Human Protein Atlas. [Trophoblast cell-type information](<https://www.proteinatlas.org/humanproteome/single+cell/single+cell+type/trophoblast+cells>).
- Liu, Y., et al. (2008). [Chemokine CXCL12 promotes the cross-talk between trophoblasts and decidual stromal cells in human first-trimester pregnancy](<https://pubmed.ncbi.nlm.nih.gov/18687671/>).
- Ren, L., Liu, Y.-Q., Zhou, W.-H., \& Zhang, Y.-Z. (2012). [Trophoblast-derived chemokine CXCL12 promotes CXCR4 expression and invasion of human first-trimester decidual stromal cells](<https://pubmed.ncbi.nlm.nih.gov/22114110/>).
- [OmniPath](<https://omnipathdb.org/>).
- [STRING](<https://string-db.org/>).
- [IntAct](<https://www.ebi.ac.uk/intact/>).
