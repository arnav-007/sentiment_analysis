# sentiment_analysis
### 1) EDA (Exploratory Data Analysis):

* Installed necessary libraries for analysis.

* Checked for null values and outliers in the dataset.

* Removed unnecessary columns.

* Replaced the value '4' with '1' in the dataset.


### 2)Data Preprocessing:

* Downloaded NLTK downloader, including stopwords and WordNet.
  
* Cleaned the 'sentiment' column through tokenization, stemming, lowering, and format correction.
  
* Divided the column into positive and negative lists based on '1' and '0'.
  
* Joined them into two different strings.


### 3)Data Visualization:

* Created a word cloud to visualize all the words present in positive and negative sentiments.
  
* Constructed a bar chart to identify the most frequently occurring words in both positive and negative lists.


### 4)Convert Data into Numerical Form:

* Used TF-IDF to convert text to numerical values, enhancing prediction accuracy.

### 5)Data Splitting and Training:

* Split the data into training and testing sets.
  
* Conducted training and testing on the divided dataset.

### 6)Model Implementation:

* Imported different modeling algorithms such as logistic regression, SVM, and Naive Bayes.
  
* Checked the accuracy of each model to identify the one with the best performance.

### 7)Model Evaluation:

* Assessed different accuracies of various models.
  
* Constructed a confusion matrix to evaluate model performance, ensuring a balance between accuracy and avoiding overfitting.
