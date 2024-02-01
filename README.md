**Caltech AI/ML Project Capstone Project**

ICMR Cancer Genes Analysis

 Healthcare

Analysis of Gene Expression Data for Cancer Classification

Eaint Kyawt Hmu

https://github.com/eaintkyawthmu/

https://www.linkedin.com/in/eaintkyawthmu/



**Abstract**

Cancer remains one of the leading causes of mortality worldwide, necessitating ongoing research into its early detection and treatment. This study aims to leverage gene expression data to classify different types of cancer, potentially contributing to more accurate diagnoses and personalized treatment strategies. Utilizing a dataset comprising 802 samples, each with expression values for over 20,000 genes, we employed a variety of dimensionality reduction techniques, including Principal Component Analysis (PCA), Linear Discriminant Analysis (LDA), and t-Distributed Stochastic Neighbor Embedding (t-SNE), to identify the most informative features. Clustering techniques such as k-means, hierarchical, and mean shift clustering were applied to discern patterns within the gene expression data. Subsequently, multiclass classification models, including Support Vector Machine (SVM), Random Forest, and Deep Neural Networks, were built and validated. The models' performance was assessed using metrics such as accuracy, precision, recall, and F1-score. Our findings indicate that certain genes play pivotal roles in cancer classification, with the potential to enhance our understanding of cancer genomics and inform future research directions in the quest for improved cancer diagnostics and therapeutics.



Introduction

The project is aimed at understanding the genetic underpinnings of different cancers. By exploring over 20,000 gene expressions per sample, the study seeks to uncover patterns and correlations specific to each cancer type. Exploratory Data Analysis, Dimensionality reduction techniques such as PCA, LDA, and t-SNE were employed. Clustering techniques were applied to both genes and samples. K-means clustering grouped genes with similar expression values and identified the distribution of samples corresponding to each cancer type. Multiclass SVM, Random Forest, and Deep Neural Network models were built and evaluated. The models showed high precision, recall, and F1-scores, with overall accuracies reported as high as 0.99 for some models.



**Methodology**

This methodology section provides a comprehensive overview of the steps taken to analyze the gene expression data for cancer classification. The study aimed to identify patterns in gene expression that could be significant for cancer diagnosis and treatment.The methodology of the study can be detailed as follows:

1\. Exploratory Data Analysis:

- The initial step involved merging the datasets and plotting the merged dataset as a hierarchically-clustered heatmap.
- The dataset contains 802 samples with expression values for more than 20,000 genes, with each sample corresponding to one of five cancer types: BRCA, KIRC, COAD, LUAD, and PRAD.

2\. Dimensionality Reduction:

- Given the high dimensionality of the data, dimensionality reduction techniques such as PCA, LDA, and t-SNE were employed.
- The output of each method was a selected subset of genes that captured the most variance or separated the classes most distinctly.

3\. Clustering Genes and Samples:

- Clustering techniques like k-means, hierarchical, and mean shift clustering were applied to identify groups of genes with similar expression values across all samples or within each cancer type.
- The clustering was also applied to samples to identify if samples of the same cancer type corresponded to the same cluster.

4\. Building Classification Models:

- Multiclass classification models such as SVM, Random Forest, and Deep Neural Networks were built to classify the input data into the five cancer types.
- Feature selection algorithms, forward selection, and backward elimination were applied to refine the attributes selected from the dimensionality reduction step.
- The genes selected from the last step were validated using statistical significance testing (t-test for one vs. all and F-test).

5\. Model Evaluation:

- The models were evaluated using metrics such as precision, recall, F1-score, and accuracy.
- A confusion matrix was used to visualize the number of correct and incorrect predictions made by the model.

6\. Null-Hypothesis Testing:

- ANOVA and t-tests were performed to determine if there were significant differences in gene expression levels across different cancer types.

7\. Optimization and Validation:

- The Adam optimizer and categorical cross-entropy loss function were used for the deep learning models.
- Early stopping was implemented to prevent overfitting, and the best model weights were restored based on validation accuracy.

8\. Visualization:

- The results of dimensionality reduction and clustering were visualized using scatter plots, with different colors representing different cancer types.

Results and Discussion

The results reveal distinct genetic profiles for each cancer type, underscoring the potential of using gene expressions as diagnostic markers. The study also highlights the efficacy of various data science techniques in biomedical research.

The merged dataset was visualized using a hierarchically-clustered heatmap, revealing patterns in gene expression across different cancer types. PCA, LDA, and t-SNE were used to reduce the high-dimensional gene expression data. The number of components varied, with PCA showing a potential elbow point around 150-200 components. Feature selection was performed using statistical significance testing, with several genes showing strong differential expression for specific cancer types. The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. Confusion matrices were used to visualize the performance of the models.

Discussion:

- The study's findings indicate that certain genes play pivotal roles in cancer classification, which could enhance the understanding of cancer genomics.
- The high accuracy of the classification models suggests that the selected features are highly predictive of the cancer types.
- The results were compared with existing literature to validate the significance of the identified genes and patterns.
- Potential implications for cancer diagnosis and treatment were discussed, emphasizing the importance of early identification of cancer types.

Conclusion

This research offers valuable insights into the genetic basis of cancers, paving the way for more personalized and effective diagnostic and treatment strategies.
