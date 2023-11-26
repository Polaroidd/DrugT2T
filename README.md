# 딥러닝을 이용한 T2T-unique 유전자와 약물 간의 상관관계 규명

GNE 모델과 DGIdb를 활용하여 T2T-Unique 유전자와 약물 간의 상관관계를 예측하였다.

Data/human/ 에는 GNE 모델 학습을 위한 data (BioGrid edgelist, Chip-seq expression data)와 학습 결과인 embedding이 들어있다.

# References
1. Malki, M.A., Pearson, E.R. Drug–drug–gene interactions and adverse drug reactions. Pharmacogenomics J 20, 355–366 (2020). https://doi.org/10.1038/s41397-019-0122-0
2.  Lazarou J, Pomernaz B, Corey P. Incidence of adverse drug reactions in hospitalized patients: a meta-analysis of prospective studies. Surv Anesthesiol. 1999;43:53–4.
3. Sharon L Freshour, Susanna Kiwala, Kelsy C Cotto, Adam C Coffman, Joshua F McMichael, Jonathan J Song, Malachi Griffith, Obi L Griffith, Alex H Wagner, Integration of the Drug–Gene Interaction Database (DGIdb 4.0) with open crowdsource efforts, Nucleic Acids Research, Volume 49, Issue D1, 8 January 2021, Pages D1144–D1151, https://doi.org/10.1093/nar/gkaa1084
4. Sergey Nurk et al. ,The complete sequence of a human genome. Science 376,44-53(2022). DOI:10.1126/science.abj6987 
5. KC, K., Li, R., Cui, F. et al. GNE: a deep learning framework for gene network inference by aggregating biological information. BMC Syst Biol 13 (Suppl 2), 38 (2019). https://doi.org/10.1186/s12918-019-0694-y
6. Oughtred R, Rust J, Chang C, Breitkreutz BJ, Stark C, Willems A, Boucher L, Leung G, Kolas N, Zhang F, Dolma S, Coulombe-Huntington J, Chatr-Aryamontri A, Dolinski K, Tyers M. The BioGRID database: A comprehensive biomedical resource of curated protein, genetic, and chemical interactions. Protein Sci. 2020 Oct 18. 
7.  Gershman A, Sauria MEG, Guitart X, Vollger MR, Hook PW, Hoyt SJ, Jain M, Shumate A, Razaghi R, Koren S, Altemose N, Caldas GV, Logsdon GA, Rhie A, Eichler EE, Schatz MC, O'Neill RJ, Phillippy AM, Miga KH, Timp W. Epigenetic patterns in a complete human genome. Science. 2022 Apr;376(6588):eabj5089. doi: 10.1126/science.abj5089. Epub 2022 Apr 1. PMID: 35357915.
