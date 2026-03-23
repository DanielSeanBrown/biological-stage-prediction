# Gene Expression Classification & Clustering

### Overview
This project explores how gene expression data can be used to predict stages within a biological process. Using a combination of supervised and unsupervised learning techniques, the analysis focuses on extracting meaningful patterns from high-dimensional continuous data and evaluating model performance under varying conditions. The project emphasises reproducibility, model interpretability, and robustness, with additional simulation work to better understand model stability. For full documentation, please refer to the report file.

### Methods
- After data cleaning and exploratory analysis, logistic regression was used as a baseline high interpretability model.
- Random Forest models were used to produce a high performance classifier.
- LDA and PCA were performed to produce two dimensional visualisations of the dataset classes.
- Bootstrapping was used produce simulated datasets, with logistic regression performed on each simulation to produce a dataset of coefficients.
- GMM was performed on teh simulated coefficients dataset to assess model stability.

### Key Results
A high performance model was produced, where sensitivity and recal reached above 90% on all classes.

### Key Insights
Key genes for identifying bioligcal state were identified, with figures detailing the exact way in which they change and interact.
It was also understood why one of the states was more challenging to classify on.

### Tools & Technologies
Language: R
Environment: RStudio
Techniques: Machine Learning, Clustering, Dimensionality Reduction, Simulation


Project Details
Duration: 2 months
Dataset: 20 gene expression features

Grade: [84% (Distinction)]
