## Fake News Detection using Machine Learning
**Overview**

This project is a Fake News Detection System that classifies news articles as real or fake using machine learning techniques. It utilizes TF-IDF vectorization for text feature extraction and a Linear Support Vector Classifier (LinearSVC) for classification.

**Features**
- Classifies news articles into real or fake.
- Uses TF-IDF Vectorizer for text preprocessing.
- Employs LinearSVC (Support Vector Machine) as the classification model.
- Achieves an accuracy of ~92.89% on the test dataset.

**Technologies Used**
- Python
- scikit-learn
- pandas
- numpy

**Dataset**
- The dataset used is "fake_or_real_news.csv".
- The "label" column is converted to binary values:
- REAL → 0
- FAKE → 1

**Installation & Setup**
- Clone this repository:
- <git clone> https://github.com/yourusername/fake-news-detection.git
- cd fake-news-detection
 
**Install dependencies:**
- pip install numpy, pandas, scikit-learn

**Model Training**
- Preprocessing:
- Text data is vectorized using TfidfVectorizer.
- Stop words are removed, and a max document frequency of 0.7 is used.

**Model Training:**
- The dataset is split into 80% training and 20% testing.
- LinearSVC (Support Vector Machine) is trained on the vectorized text.

**Evaluation:**
- The model achieves an accuracy of 92.89%.

**Results**
- The model was evaluated on test data and achieved an accuracy of ~92.89%.

**License**
- This project is made for learning purpose only.

