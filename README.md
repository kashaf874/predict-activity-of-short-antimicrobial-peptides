# predict activity of short antimicrobial peptides (QSAR models) Quantitative structure–activity relationship models 

## Capstone First Project At DevNation
[![N|Solid](https://uploads-ssl.webflow.com/5ff6c1dbc139fb9bf9f6a511/6089ced541a4550bbc1e1a65_Dev__1_-removebg-preview.png)](https://uploads-ssl.webflow.com/5ff6c1dbc139fb9bf9f6a511/6089ced541a4550bbc1e1a65_Dev__1_-removebg-preview.png)



## **FUNCTIONAL and TECHNICAL REQUIREMENTS**


### **Title**


# predict activity of short antimicrobial peptides

## Develop By -  Kashaf Naz





### __TABLE OF CONTENTS__

**Obj.**	|**Heading**
-----------|---------------------------------------
1|	General Information 	
2|	Purpose	
3|	Scope	
4|	Acronyms and/or definitions	
5|	Project Overview	
6|	Functional Requirements and user Impact	
7|	Data Resource	
8|      Lazypredict




### 1. **General information**
    Predict activity of short antimicrobial peptides.
    will be building a machine learning model to predict antimicrobial peptides
	
### **2.Purpose**
    Antimicrobial resistance is an urgent and global health problem as existing,
    drugs are becoming ineffective against the treatment of antimicrobial infections.
    
    
  ### 3. **Scope**
    Particularly, we will be retrieving 2 datasets consisting of antimicrobial peptides (positive set) and non-antimicrobial peptides (negative set).
    Then, I will be computing some peptide features to quantitatively describe peptides followed by model building.
    finally model interpretation where we shed light on the key important features important for predicting antimicrobial peptides.
    
    
    
### 4.  **Acronyms and/or definitions**

Modules      |  Discription
-------------|------------------------------------------------
 Conda	       |In which we install packages like python, Our working Environments
Pfeature      |Pfeature allow us to compute properties of Amino Acid which will be crucial to Quantify the Molecular properties of peptides 
Jupyter NoteBook/ Colab	|  Note book
CD-Hit from bioconda	|A library allows us to fit or out any Redundancy in Peptide Sequence, meaning that peptide that are Much Similar will be removed, So We will get non-redundant and a unique sub set of Peptides that will be using in Molecular sequence
Pandas	|It’s data-frame for viewing Visualization
Python	|For Programing
Random Forest classifier|	modeling
Matplotlip|	Graph visualization




### 5.  **Project Overview**
     I will be computing some peptide features to quantitatively describe peptides followed by model building
     
     
### **6.  Functional Requirements and user Impact**
     Calculate Features Using P features
     Featuring most to least featured amino acid
     
     
### **7. Data Resource:**
     A research paper

# **Quickly compare >30 ML algorithms**

In order to apply Quickly compare >30 ML algorithms​
we used:

## 8. **Lazypredict: The automl library​**

- Lazy Predict Helps build a lot of basic models without much code and helps understand
which models works better without any parameter tuning.

- There are two classes, LazyClassifier and LazyRegressor, respectively for classifier and regressor.
- We can import the classifier class if your problem is classification, and import regressor if you have a regression problem.​





