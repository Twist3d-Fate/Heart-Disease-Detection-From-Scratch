# Heart-Disease-Detection-From-Scratch

## Description: <br>
Classify the presence or absence of heart disease in a patient based on various features indicating the heart's condition and health. 

## Method: <br> 
Performed exploratory data analysis (EDA) and visualize the data through various plots, and then implemented a Multi-Layer Perceptron (MLP) from scratch using NumPy. 

## Dataset: <br> 
The dataset used was the Cleveland Heart Dataset accessible from the UCI repository through the following link: https://archive.ics.uci.edu/ml/datasets/heart+disease. <br><br> The original dataset consisted of 75 input features and 1 output label, but that was tailored down to 13 features relevant to heart disease prediction. The detailed description of these features is available in the following table: <br><br>

<table> 
    <tr> 
        <th align=\centre\><b>Features</b></th> 
        <th align=\centre\><b>Description</b></th> 
    </tr> 
    <tr> 
        <td>Age</td>  
        <td>Age of the Patient</td> 
    </tr> 
    <tr> 
        <td>Sex </td> 
        <td>Sex of the Patient</td> 
    </tr> 
    <tr> 
        <td>cp </td> 
        <td>Chest Pain Type: 
            <ul> 
                <li>Value 1: Typical Angina</li> 
                <li>Value 2: Atypical Angina</li> 
                <li>Value 3: Non-Anginal Pain</li> 
                <li>Value 4: Asymptomatic</li> 
            </ul> 
        </td> 
    </tr> 
    <tr> 
        <td>trestbps </td> 
        <td>Resting Blood Pressure (in mm Hg)</td> 
    </tr> 
    <tr> 
        <td>chol </td> 
        <td>Serum Cholestoral in mg/dl</td> 
    </tr> 
    <tr> 
        <td>fbs </td> 
        <td> 
            (Fasting blood sugar > 120 mg/dl)  
            <li>1 = true</li> 
            <li>0 = false </li> 
        </td> 
    </tr> 
    <tr> 
        <td>restecg</td> 
        <td> 
            <ol> 
                <li>Value 0: Normal</li> 
                <li>Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)</li> 
                <li>Value 2: Showing probable or definite left ventricular hypertrophy by Estes criteria</li> 
            </ul> 
        </td> 
    </tr> 
    <tr> 
        <td>thalach </td> 
        <td>Maximum Heart Rate achieved</td> 
    </tr> 
    <tr> 
        <td>exang</td> 
        <td>Exercise induced angina                         
        <li>1 = yes</li> 
            <li>0 = no</li> 
        </td> 
    </tr> 
    <tr> 
        <td>oldpeak</td>  
        <td>ST depression induced by exercise relative to rest </td> 
    </tr> 
    <tr> 
        <td>slope </td> 
        <td>Peak exercise ST segment Slop 
            <li> 0 = Downsloping</li> 
            <li> 1 = Flat</li> 
            <li> 2 = Upsloping</li> 
        </td> 
    </tr> 
    <tr> 
        <td>ca</td>  
        <td>The number of major vessels (0–3) colored by flouroscopy</td> 
    </tr> 
    <tr> 
        <td>thal </td> 
        <td>A blood disorder called Thalassemia 
            <li> Value 1: normal blood flow</li>
            <li> Value 2: fixed defect (no blood flow in some part of the heart)</li> 
            <li> Value 3: reversible defect (a blood flow is observed but it is not normal)</li> 
        </td> 
    </tr> 
    <tr> 
        <td>target </td> 
        <td>Percentage of deliverable volume 
            <li> 0 = Absence of heart disease</li> 
            <li> 1 = Presence of heart disease </li> 
        </td> 
    </tr> 
</table><br> 

## Results: <br> 
The model was very accurate, achieving an accuracy of 100% on the test data. On the website for the dataset, the most accurate model had an accuracy of 89.474%, making this model a significant improvement in terms of accuracy and an effective tool to classify the presence of heart disease.
