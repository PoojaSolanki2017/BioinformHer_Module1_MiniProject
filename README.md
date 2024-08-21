# BioinfoHer_Module1_MiniProject
## **PROJECT TITLE**
Comprehensive Sequence Analysis of the Human TNF Gene

## **OBJECTIVE**
To apply bioinformatics skills to download, analyse, and interpret the sequence of the human TNF gene, which encode a proinflammatory cytokine call TNF.

## **PROJECT OVERVIEW**
In this project, a series of Bioinformatics steps were performed on the human TNF gene which can be useful for further biological research. Firstly, data was retrieved from NCBI in FASTA format. Subsequently, the nucleotide sequence was visualized and translated into amino acid with BioEdit tool. The finding of ORFs and analysis of sequence composition was also performed using BioEdit tool.  After that, PROMO tool was used to identify Transcription Factor Binding Sites and MEME Suite was used for finding motifs. At last, coding and non-coding regions were predicted with GENSCAN and the FASTA sequence of TNF gene was concerted to PHYLIP format using BioEdit tool.  

### **Instruction**
Downlaod Module1_MiniProject.zip folder to check the project report, outputs and screenshots.

## **Task 1: Download a Biological Sequence from NCBI and View/Edit it**
In any bioinformatics project, the first step is to download data from reliable sources. So, here the human TNF sequence was downloaded from the NCBI gene database in FASTA format and opened in BioEdit to view and edit it (Figure 1).  

## **Task 2: Generate a Translation of a DNA or RNA Sequence into Amino Acids**
In biological research, it is important to know the protein sequence to find the function and structure of that protein. Thus, the DNA sequence of the TNF gene was translated into Amino Acids using the Translate function of the BioEdit tool (Figure 2).

## **Task 3: Find ORFs (Open Reading Frames) in a DNA or RNA Sequence**
In any nucleotide sequence, finding a protein coding sequence is the crucial step. As, this protein sequence could be helpful in drug development and designing primers for that region. Thus, there were a total of 17 ORFs were found in the human TNF gene with ORF prediction function of BioEdit tool (Figure 3). From those, 6 were found in frame 1, 5 in frame 2, and 6 in frame 3. The smallest ORF is made of 25 amino acids while the largest one is of 178 amino acids. Each ORF starts with methionine which is the START codon AUG.

## **Task 4: Analyse Sequence Composition (Nucleotide or Amino Acid Frequencies)**
Finding the nucleotide composition of the gene is an extremely useful step in genetic research. For example, rich GC regions suggest higher stability of the nucleotide sequence as GC has three hydrogen bonds. So, the total nucleotide composition of the human TNF gene is as follows: A 25.58%, C 24.53%, G 28.28%, and T 21.61%. The total GC content of the gene is 52.81%, which is a good GC content and suggests stability of the gene (Figure 4).

## **Task 5: Identify Transcription Factor Binding Sites Using the PROMO Tool**
In any gene identifying TFB sites is important as they regulate the gene expression. In many research areas for example Cancer, if some particular TFB is responsible for cancer causing genes, scientists could target those sites to suppress them. TNF gene encodes one cytokine which is involved in various diseases including cancer and autoimmune diseases. The TFBs FOXP3 encodes a protein that is a member of forkhead-helix family of transcriptional regulators and defects in this gene can cause X-linked autoimmunity-immunodeficiency syndrome. Another found TFBs is IRF-1 and mutation in this gene could cause gastric and lung cancer.  Thus, it is observed that TNF gene takes part in cancer and immune diseases (Figure 5).

## **Task 6: Search for Functional Motifs in a Genome or Transcriptome Using MEME Suite**
Found three functional motifs in TNF gene sequence. The lower p-value suggests the higher significance of these motifs. The location of each motif is shown in the picture (Figure 6).

## **Task 7: Predict Coding/Non-Coding Regions in a Genome Using GENSCAN**
To identify coding and non-coding regions is essential to understand the function of the different parts of the gene. So, here for TNF gene, a total of five exons were predicted, out of that one is an initial exon with length of 186, two are internal exons with a length of 46 and 48 respectively, and one is a terminal exon with a length of 422 and one has PolyA signal with 6 nucleotides (Figure 7). The coding region score of the initial exon (207) and terminal exon (518) is higher than internal exons, while p-value of one internal exon (0.987) and terminal exon (0.985) is greater than 0.95. The exon score of the initial exon is 22.03 and the terminal exon is 48.73. Thus the terminal exon is the most reliable out of all the exons as it has the highest exon score, p-value, and coding region score.

## **Task 8: Convert Between Sequence File Formats Using BioEdit (FASTA to PHYLIP)**
Different tools require different file formats, so it is important to learn about file conversion. Thus, here, the TNF FASTA file was saved in PHYLIP format using BioEdit (Figure 8), which can be shared with others for phylogenetic analysis.

## **REFERENCES**
•	Idriss HT, Naismith JH. TNF alpha and the TNF receptor superfamily: structure-function relationship(s). Microsc Res Tech. 2000 Aug 1;50(3):184-95. doi: 10.1002/1097-0029(20000801)50:3<184::AID-JEMT2>3.0.CO;2-H. PMID: 10891884.
•	van der Vliet HJ, Nieuwenhuis EE. IPEX as a result of mutations in FOXP3. Clin Dev Immunol. 2007;2007:89017. doi: 10.1155/2007/89017. PMID: 18317533; PMCID: PMC2248278.
•	Nozawa H, Oda E, Ueda S, Tamura G, Maesawa C, Muto T, Taniguchi T, Tanaka N. Functionally inactivating point mutation in the tumor-suppressor IRF-1 gene identified in human gastric cancer. Int J Cancer. 1998 Aug 12;77(4):522-7. doi: 10.1002/(sici)1097-0215(19980812)77:4<522::aid-ijc8>3.0.co;2-w. PMID: 9679752.

