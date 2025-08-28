### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
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
<img width="1711" height="941" alt="Screenshot 2025-08-28 211451" src="https://github.com/user-attachments/assets/c97f431d-b423-449c-aa61-9be5b43473f0" />

<img width="1692" height="909" alt="Screenshot 2025-08-28 211441" src="https://github.com/user-attachments/assets/954c1558-d501-4a8a-8741-085193da06a4" />

<img width="943" height="921" alt="Screenshot 2025-08-28 214559" src="https://github.com/user-attachments/assets/8f5ef5be-8590-4e9d-a9d5-0b6f3d160db0" />

<img width="1355" height="885" alt="Screenshot 2025-08-28 214655" src="https://github.com/user-attachments/assets/7c9cdbb7-7526-4430-a08e-344a649d676c" />

### Result:
Thus, the implement preprocessing technique on Twitter Data using Rapidminer.
