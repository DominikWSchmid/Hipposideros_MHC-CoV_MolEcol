###### Hipposideros_MHC-CoV_MolEcol
Here we deposit the data presented in the upcoming Mol Ecol research paper entitled "MHC class II genes mediate susceptibility and resistance to coronavirus infections in bats".

We provide three datasets (Hip_MHC-CoV-data_Schmidetal2023MolEcol.csv; Hip_community-data_Schmidetal2023MolEcol.csv; and Hip_community-CoV-data_Schmidetal2023MolEcol.csv) as CSV format. They form the backbone of the analysis performed in the associated R Markdown (Schmid.Meyer_MolEcol23_Rscript.Rmd).

Additionally, we provide an excel file (Hip_MHCII-DRB2_sequences_Schmidetal2023MolEcol) with four sheets listing the MHC class II DRB exon 2 allele sequences identified among the four hipposiderid species.



- Hip_MHC-CoV-data_Schmidetal2023MolEcol.csv contains 191 columns containing the individual information of each of the 569 MHC-typed bats as rows:

> A. ID (a unique identfier)
B. species (taxonomic identity) 
C. sample_period (two months window in which the sample was taken) 
D. X229ELogical (binary presence/absence data for CoV-229E infections)
E. X229Elike (CT-values for CoV-229E infected bats)
F. X2bLogical (binary presence/absence data for CoV-2B infections)
G. X2b (CT-values for CoV-2B infected bats)
H. X2bBasalLogical (binary presence/absence data for CoV-2Bbasal infections)
I. X2bBasal (CT-values for CoV-2Bbasal infected bats)
J. Location (five different core sampling locations in Ghana)
K. REP (Reproductive status; P=pregnant; PL=pregnant lactating; NR=non-reproductive; NRF=non-reproductive female; L=lactating; RA=reproductively active) 
L. FA (forearm length; mm)
M. Mass (body mass; g)
N. number_ST (individual number of MHC supertypes)
O. number_alleles (individual number of MHC alleles)
P.-AO. Hiab alleles 001-027 (presence/absence data on MHC class II DRB exon 2 alleles for *Hipposideros abae*)
AP.-BS. Hica B alleles 001-030 (presence/absence data on MHC class II DRB exon 2 alleles for *Hipposideros caffer B*)
BT.-ET. Hica C alleles 001-087 (presence/absence data on MHC class II DRB exon 2 alleles for *Hipposideros caffer C*)
EU.-FW. Hica D alleles 001-029 (presence/absence data on MHC class II DRB exon 2 alleles for *Hipposideros caffer D*)
FX.-GI. MHC STs 1-12 (presence/absence data on MHC class II DRB exon 2 supertypes common to the four Hipposideros species)



- Hip_community-data_Schmidetal2023MolEcol.csv contains 16 columns:

> A. Location (five different core sampling locations in Ghana)
B.-P.: Bat species presence/absence data 



 - Hip_community-CoV-data_Schmidetal2023MolEcol.csv contains 7 columns: 
 
 > A. ID (a unique identifier)
 B. X229ELogical (binary presence/absence data for CoV-229E infections)
 C. X2bLogical (binary presence/absence data for CoV-2B infections)
 D. X2bBasalLogical (binary presence/absence data for CoV-2Bbasal infections)
 E. Lineage (species name or lineage membership of hipposideros bats)
 F. Location (five different core sampling locations in Ghana)
 G. Species (taxonomic identity) 




For a R script concerning the codon usage analysis please enquire with M. Gillingham and A. Courtiol (associated paper: Gillingham, M. A.F., Courtiol, A., Teixeira, M., Galan, M., Bechet, A., & Cezilly, F. (2016). Evidence of gene orthology and trans-species polymorphism, but not of parallel evolution, despite high levels of concerted evolution in the major histocompatibility complex of flamingo species. Journal of Evolutionary Biology, 29(2), 438–454. doi: 10.1111/jeb.12798). 

The rationale behind the codon usage analysis is based on work presented by T. Lenz (Lenz, T. L., Eizaguirre, C., Kalbe, M., & Milinski, M. (2013). Evaluating patterns of convergent evolution and trans-species polymorphism at mhc immunogenes in two sympatric stickleback species. Evolution, 67(8), 2400–2412. doi: 10.1111/evo.12124)
