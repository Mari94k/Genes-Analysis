# Gene-Analysis
Data Evaluation:

In this project, we found features that are associated with the "type". The dataset contains 122 samples and 19234 features and in the file of TCGABRCA.pheno we have 122 labels. Here, we had to subset and realign data which included in TCGA-BRCA.htseq_fpkm-uq_gene_name and TCGABRCA.pheno. Firstly, we extracted mutual columns by columns intersection which were features transposed the feature data frame. Secondly, we relabeled data with integers which 1 represented “Tumor” and 0 denoted “Normal”. Finally, it trained with Random Forest Regressor to discover relevant features by its feature_importances_ attribute. The top 30 features are demonstrated in the 
bar chart.
