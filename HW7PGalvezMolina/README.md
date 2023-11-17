This assignment was worked in collaboration with Masooma Sarfraz, Tali Natan. I consulted Rayta Pradata, Sarah Henderson, Zach Savory and Shar Daniels. I also consulted with TA Willow.

My interactions with Masooma and Tali we mostly discussions on the interpretation of results, and I received some code to set-up subplots from Masooma, and provided some code to Tali to create the dendograms.

The homework had as a main goal to apply three clustering methods and use two visualization tools to assess our clustering. The data set used was the Kidpack microarray that contained 74 columns, each pertaining to a tissue of a tumor a different cancer patient. Each sample had over 4,000 rows of gene information. The columns (tissue sample) were used as our features to be clustered.
Besided clustering the data, we first pre-processed it which corresponded to normalizing our data, and we also analyzed it based on our 2D projections. 

The hardest part was understanding that normalization had to be done over the tissue's samples and not the genes. For this reason, and because the equation in the notebook did not specify that it was supposed to be the squared magnitude of the variance, I also struggled with setting up my intracluster variance function.

I gained experience using TSNE and UMAP projections (espcially in a 2D space) and applying the three clustering techniques (KMEANS, BDSCAN and Agglomerative). Addtionally I gained more experience in interpreting dendograms.
