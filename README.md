# EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 30.01.26
### AIM:
To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
### DESIGN

<img width="1713" height="1063" alt="Screenshot 2026-01-30 162742" src="https://github.com/user-attachments/assets/da47533a-2222-4559-9052-0271446c80ab" />
<img width="1706" height="1061" alt="Screenshot 2026-01-30 162813" src="https://github.com/user-attachments/assets/c4c64321-48eb-4a5b-8c6c-83eaa58a0505" />

### RESULT

<img width="1730" height="1065" alt="image" src="https://github.com/user-attachments/assets/dc0b8df0-b9be-43ec-9d04-ab21abe1e282" />


### Result:
The implementation of preprocessing technique on Twitter Data using Rapidminer Executed Successfully.
