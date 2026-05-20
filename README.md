# Mini-Project-Data-Science

**Project Problem Statement**

**Project Title:  PREDICTIVE HEALTHCARE ANALYTICS**

**Abstract:** 
Predictive Healthcare Analytics leverages data science and machine learning to forecast patient outcomes, optimize treatment strategies, and improve healthcare quality. This project develops a predictive model integrating electronic health records (EHRs), genetic data, and environmental factors to identify high-risk patients and recommend personalized interventions. Methodologies include data integration, machine learning algorithms (e.g., logistic regression, decision trees, neural networks), and model evaluation using metrics like accuracy and F1-score. By harnessing predictive analytics, healthcare providers can proactively address potential health risks, reduce costs, and enhance patient outcomes.
The model has various applications in healthcare, including early disease detection, personalized medicine, and resource optimization. For instance, it can identify high-risk patients and intervene early to prevent disease progression, tailor treatment strategies to individual patient characteristics, and allocate healthcare resources more efficiently. Overall, Predictive Healthcare Analytics has the potential to transform healthcare delivery and improve patient outcomes.

**Methodology :**
1.	Data Collection: Integrate EHRs specifically from Existing Laboratories, genomic data, and lifestyle factors. 
2. Data Preprocessing: Clean, transform, and feature engineer data
3. Model Development: Train machine learning models for risk prediction

**Keywords:**
 - Predictive Analytics, Healthcare, Machine Learning, Electronic Health Records  
   (EHRs), Genetic Data,  Personalized Medicine, Disease Prediction, Patient  
   Outcomes, Healthcare Optimization, Data Science, Clinical Decision Support.

**Tools Used :**
WEKA Software

**How To Run Project :**
The output of this project is achieved through a structured, three-step machine learning pipeline designed to transform raw laboratory data into accurate medical predictions,.
The following steps outline how the final results are generated:
Step 1: Data Acquisition
The process begins by sourcing the "Multiple Disease Prediction" dataset from Kaggle,,. This dataset contains vital human health metrics and blood parameters, including:

    Cholesterol (125–200 mg/dL)
    Hemoglobin (13.5–17.5 g/dL)
    Platelets (150,000–450,000 per microliter)
    White Blood Cells (4,000–11,000 per cubic mm)
    Insulin (5–25 microU/mL)

Step 2: Data Preprocessing (WEKA Workshop)
Raw data is often "messy" and must be translated into a language machine learning models can understand using WEKA software,. This stage involves four critical sub-steps:

    Loading: Importing the Kaggle dataset (CSV or ARFF files) into the WEKA Explorer.
    Cleaning: Identifying and replacing missing values (represented by "?") and removing duplicate entries to ensure data integrity.
    Normalization: Scaling all parameters to the same level (e.g., ensuring a large platelet count doesn't artificially overshadow a smaller hemoglobin number) so the algorithm treats all data fairly,.
    Noise Removal: Eliminating irrelevant data or anomalies so the algorithm focuses on the "true signal" rather than "static",,.

Step 3: Machine Learning Model Development
Once the data is cleaned and normalized, it is fed into three distinct classification algorithms for benchmarking,:

    Naive Bayes: A fast, simplistic model,.
    J48: An interpretable decision-tree-based model,.
    Random Forest: A powerful ensemble model known for high predictive capability,.

Step 4: Output Generation and Comparison
The final output is a comparison of these models based on Accuracy and Recall (the ability to find all actual disease cases without missing any),. The results produced were:

    Naive Bayes: 87% Accuracy with medium recall,.
    J48: 87.02% Accuracy with medium-high recall,.
    Random Forest (Final Output): This model achieved the project's peak performance with 100% predictive accuracy and a perfect recall score of 1.00,,.

The ultimate output is the identification of a Random Forest-based tool that can provide doctors with mathematical certainty for early disease detection and evidence-based decision-making.
   
**Output Summary :**
The project successfully identified the Random Forest model as the most effective tool for predictive healthcare, achieving a staggering 100% accuracy and a perfect recall score of 1.00. Other models tested, such as Naive Bayes and J48, achieved respectable accuracies of 87% and 87.02% respectively.
The summary of findings includes:
 Model Superiority: Random Forest provided absolute mathematical certainty in identifying diseases within the tested Kaggle dataset.
 Methodological Validation: The results confirm that using WEKA software for critical preprocessing steps like normalization and noise removal is essential for                             high-performance medical modeling.
 Societal Value: The final output demonstrates that early detection through such models can transform reactive medicine into proactive wellness, significantly                    reducing healthcare costs and improving patient outcomes
