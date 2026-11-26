# Indonesian-Political-News-Hoax-Detection-Naive-Bayes-SVM

This project is a final assignment for the Data Science program,
focusing on Text Mining and Machine Learning for detecting hoax and
factual political news in Indonesia. This research compares the
performance of several Naive Bayes variants and Support Vector Machine
(SVM) kernels to classify Indonesian political news into two categories:
**Hoax and Fact**.

The dataset consists of 31,726 news articles collected from four
sources: CNN Indonesia, Kompas, Tempo, and TurnBackHoax. The
classification models are evaluated using Accuracy, Precision, Recall,
F1-Score, and Confusion Matrix.

The best-performing model is **SVM with RBF Kernel combined with SMOTE
and Chi-Square Feature Selection**, achieving an accuracy of **99.82%**,
with only 9 misclassified predictions out of 6,259 test samples. As a
computationally efficient alternative, Bernoulli Naive Bayes achieves an
accuracy of 98.90%.

## Methodology

1.  Data Preparation and Exploratory Data Analysis (EDA)
2.  Text Preprocessing (Cleaning, Tokenization, Normalization, Stopword
    Removal, and Stemming)
3.  Feature Extraction using TF-IDF (5,000 features)
4.  Handling Imbalanced Data using SMOTE
5.  Feature Selection using Chi-Square (2,000 best features)
6.  Model Training and Comparison:
    -   Support Vector Machine (Linear, RBF, Polynomial, and Sigmoid
        Kernels)
    -   Multinomial Naive Bayes
    -   Gaussian Naive Bayes
    -   Bernoulli Naive Bayes
    -   Complement Naive Bayes

## Technologies & Libraries

-   Python
-   Pandas & NumPy
-   Scikit-learn
-   Imbalanced-learn (SMOTE)
-   Sastrawi
-   Matplotlib & Seaborn
-   WordCloud

## Dataset Sources

-   CNN Indonesia (Fact)
-   Kompas (Fact)
-   Tempo (Fact)
-   TurnBackHoax (Hoax)

## Project Team

1.  Jeika Antama Syalom Tarigan (24031554011)
2.  Ayda Nur' Salzabillah (24031554017)
3.  Gresya Maranatha Sihaloho (24031554027)
4.  Muhammad Zikri Widiandra (24031554088)

**Bachelor of Data Science --- Faculty of Mathematics and Natural
Sciences --- Universitas Negeri Surabaya (UNESA)**
