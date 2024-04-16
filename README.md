# Fake News Detection using Machine Learning
This project aims to detect fake news using machine learning techniques. Fake news has become a significant issue in today's information age, spreading misinformation and influencing opinions. By employing machine learning algorithms, this project endeavors to classify news articles as either real or fake based on their content.

### Dataset
The dataset used for this project can be downloaded from [this link](https://drive.google.com/file/d/1q5jpI5M1EA9x3YPrLupmiu3gffkmGlHj/view). It consists of news articles with corresponding labels indicating whether they are real (class 1) or fake (class 0).

### Libraries Used
- pandas: For data manipulation and analysis.
- seaborn & matplotlib: For data visualization.
- tqdm: For displaying progress bars during data preprocessing.
- nltk: For natural language processing tasks such as tokenization, stopwords removal, and stemming.
- wordcloud: For generating word clouds to visualize most frequent words in the text.
- scikit-learn: For machine learning tasks like feature extraction, model training, and evaluation.

### Code Overview
The Python script provided in this repository performs the following tasks:

1. **Data Preprocessing**: The script preprocesses the text data by removing punctuation, converting text to lowercase, removing stopwords, and stemming words.
2. **Exploratory Data Analysis**: Visualizations such as count plots and word clouds are generated to gain insights into the data.
3. **Feature Extraction**: TF-IDF vectorization is applied to convert text data into numerical features.
4. **Model Training**: Two classifiers, Logistic Regression and Decision Tree, are trained on the preprocessed data.
5. **Model Evaluation**: The accuracy of the trained models is evaluated on both training and testing datasets. Additionally, confusion matrices are plotted for better understanding of classification performance.

### Instructions
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Download Dataset**: Download the dataset from the provided link and place it in the project directory.
3. **Install Dependencies**: Ensure all required libraries are installed. You can install them using pip.
```
pip install pandas seaborn matplotlib tqdm nltk wordcloud scikit-learn
```
4. **Run the Script**: Execute the Python script in your preferred environment. Make sure to adjust file paths if necessary.

### Results
- Logistic Regression Model:
   - Training Accuracy: 99.33%
   - Testing Accuracy: 98.95%
- Decision Tree Classifier:
   - Training Accuracy: 99.99%
   - Testing Accuracy: 99.59%
Both models demonstrate high accuracy in classifying news articles as real or fake.

### Contributing
Contributions are welcome! Please feel free to submit issues and pull requests.

### License
This project is licensed under the MIT License.
