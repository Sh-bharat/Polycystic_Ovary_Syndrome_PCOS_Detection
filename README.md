# PCOS Dataset Analysis

## Description
This dataset comprises 2000 rows and 44 columns, collected for Polycystic Ovary Syndrome (PCOS) analysis. PCOS is a hormonal disorder common among women of reproductive age, characterized by irregular periods, excess androgen levels, and ovarian cysts. The dataset includes various parameters related to patients' demographics, medical history, physical attributes, and test results.

## Columns Dropped
- Serial Number ("Sl. No"): Not relevant to PCOS prediction.
- Patient File Number: Likely an identifier and not useful for analysis.
- Weight and Height: Derivable from the Body Mass Index (BMI) if needed.
- Hip and Waist (individually): Already captured in the hip-to-waist ratio.
- Marital Status: No established link between marital status and PCOS.

## Outlier Handling
Certain columns had predefined ranges for outlier handling:
1. Pulse rate (bpm)
2. FSH (mIU/mL)
3. LH (mIU/mL)
4. FSH/LH
5. TSH (mIU/L)
6. Vitamin D3 (ng/mL)
7. Systolic Blood Pressure (mmHg)
8. Diastolic Blood Pressure (mmHg)
9. Endometrium thickness (mm)

## Model Evaluation
Various machine learning models were applied to predict PCOS presence:
- Artificial Neural Network (ANN)
- Support Vector Machine (SVM)
- Naive Bayes
- Decision Tree
- Random Forest

### Best Models
- **ANN**: Accuracy - 0.9889
- **Random Forest**: Accuracy - 0.9834
- **Decision Tree**: Accuracy - 0.9752<br>
#### These three models were combined into a ensemble model and Providing Accuracy : 0.9917

## Conclusion
The hybrid model demonstrates high accuracy and robust performance in PCOS prediction. Further refinement and validation could enhance its utility in clinical settings.

For more details, refer to the Jupyter Notebook and Python scripts provided in the repository. 
