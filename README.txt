© Copyright YMCY7, July 2023

------------------------------------------------------------------------------------------------------------------

This GitHub Repository only contains the code.

Data can be found through the following link:
https://drive.google.com/drive/folders/1d6i2IMLlR8azfA8istorH0AwMzjtANzr?usp=sharing

------------------------------------------------------------------------------------------------------------------

The data folder consists of 17 .csv files:

Raw_Patents_2022.csv -> raw data extracted.
Cleaned_Patent_2022.csv -> cleaned raw data (contains all columns)
Data_Originial.csv -> data contains two columns; context and classification code

The rest of the 15 data files are preprocessed data split into groups. 
For example: 
Data_Preprocessed_SubGroup.csv -> contains all data and classification codes are in the format subgroup.
Data_Preprocessed_SubGroup_Top18.csv -> contains data for top 18 classification codes only and are in the format subgroup.
Data_Preprocessed_SubGroup_Selected7.csv -> contains data for selected 7 classification codes only and are in the format subgroup.

The rest follows the same formatting

------------------------------------------------------------------------------------------------------------------

The Code Files consists of 9 .ipynb files:

Prepare_Data.ipynb -> This notebook generates the 15 data files from the raw data.

Exploratory Data Analysis.ipynb -> This notebook computes EDA on the data

Modelling_SubGroup.ipynb -> Experiments different types of modelling with the following data files: Data_Preprocessed_SubGroup.csv, Data_Preprocessed_SubGroup_Top18.csv and Data_Preprocessed_SubGroup_Selected7.csv.

Modelling_MainGroup.ipynb -> Experiments different types of modelling with the following data files: Data_Preprocessed_MainGroup.csv, Data_Preprocessed_MainGroup_Top18.csv and Data_Preprocessed_MainGroup_Selected7.csv.

Modelling_SubClass.ipynb -> Experiments different types of modelling with the following data files: Data_Preprocessed_Subclass.csv, Data_Preprocessed_Subclass_Top18.csv and Data_Preprocessed_Subclass_Selected7.csv.

Modelling_Class.ipynb -> Experiments different types of modelling with the following data files: Data_Preprocessed_Class.csv, Data_Preprocessed_Class_Top18.csv and Data_Preprocessed_Class_Selected7.csv.

Modelling_Section.ipynb -> Experiments different types of modelling with the following data files: Data_Preprocessed_Section.csv, Data_Preprocessed_Section_Top18.csv and Data_Preprocessed_Section_Selected7.csv.

Finetuning.ipynb -> Experiments with different configurations to determine the optimal hyper-parameters for deep nerual networks.

Prediction.ipynb -> Uses the optimal model to predict a unseen patent classification code.

------------------------------------------------------------------------------------------------------------------

© Copyright YMCY7, July 2023
