This assignment was worked in collaboration with Masooma Sarfraz, Sarah Dellorco and Rayta Pradata. Masooma shared a code snippet for the ROC curve with me as I was having trouble as I did not need to flatten my array because of how I had initially set it up.
My main contribution to the group was during the pre-processing stage of the data by calculating the greatest data loss for various data elimination methods. 
Sarah, Masooma and Rayta all contributed explaning how various code snippets worked and helped de-bugging.

As a group we splitted into two subgroups (Rayta and Sarah, and Masooma and I) to test how our models performed based on different pre-processing method. Massoma and I decided to preserve the maximum number of features (column) at the cost of a greater data loss, while Rayta and Sarah preserved the most data points over the number of features. 
Our results did not yield a great difference in the AUC measure.

I consulted Tali Natan and Shar Daniels about the meaning of the data. After consulting with Tali I realized that I had forgot to fit my new model only with the best 4 parameters, I had previously trained it with all. Once I changed this I realized that my ROC and AUC indicate a worse performance which makes sense as 4 was chosen arbitrarily out of the 21 features I had available. So, by truncating a lot of data without an educated reason to do so, a big loss of information is to be expected.

The homework had as a main goal to use a Random Forest Classifier and a Gradient Boosting Tree Classifier. I learned to make decisions about preprocessing and gained more insight on the importance on controlling the maximum depth hyperparemeter for the forect classifiers.

The hardest part was interpreting the ROC curve. After consulting with Federica and watching a video on the meaning, I understood a little more what the curve portrais.

I gained experience using sklearn to set up tree classifiers and preprocessing "large" data.
