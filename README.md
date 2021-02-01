# PROJECT - DATATON 2020 Bancolombia

This project is about the process development to compete in a Kaggle competition called DATATON_2020 sponsored by Bancolombia.

## PURPOSE 

Ilustrates the approach used to participate in the [competition](https://www.kaggle.com/c/datatonbc-2020).

## DATASETS

The datasets used was 21 Million rows of custom data about variables related to family expenses and a 200 thousand rows test dataset.

## FILES:

- Dev:
    
    Thi folder contains a series of exercises to build the data pipeline of the training and testing in the statistical learning process.
    
    - EXPLORATION:
        - DATATON_I
        - DATATON_II
        - DATATON_III
        - DATATON_IV
        - DATATON_V
    - PRE-PROCESSING:    
        - DATATON_VI
    - MODELING:
        - DATATON_VII_LR
        - DATATON_VII_GBT

- Pro:

    This folder takes thes best of the learnings in the dev process, for the sake of the evaluatin of the trained model.
    
    - 1_PRE-PROCESSING_Traing
    - 2_PRE-PROCESSING_Test
    - 3_FEATURES_ENGINEER
    - 4_MODELING_LR
    - 5_MODELING_GBT
    - 6_MODELING_RF
    

## FOLLOW NEXT INSTRUCTION TO RUN THE PROJECT

0. Download the train set from [here](https://www.kaggle.com/c/datatonbc-2020/data).
1. Download the test set from [here](https://www.kaggle.com/c/datatonbc-2020/data).
2. Create an the following folders:
 - input.
 - output.
 - implementations.
3. Run the PRE-PROCESSING notebooks.
4. Run the Modeling LR Notebook for linear regression.
5. Run the Modeling GBT Notebook for Gradient Boosting Trees.
6. Run the Modeling RF Notebookf to Random Forest.