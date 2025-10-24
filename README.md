Cyber Bullying Tweet Detection (Machine Learning Project)

This project focuses on analyzing tweets and detecting cyberbullying behavior using Machine Learning techniques.
By understanding the words and patterns in a tweet, the model predicts whether it’s cyberbullying or non-cyberbullying, and if it’s cyberbullying, it further classifies it into six categories:

🧓 Age

🌍 Ethnicity

🚻 Gender

🙏 Religion

💬 Other Cyberbullying



📊 Dataset Used

Cyberbullying Classification Dataset from Kaggle





⚙️ Approach

Installed required libraries and imported the dataset using pandas.

Reviewed the data and checked for missing values.

Preprocessed text data including:

Removing emojis

Converting text to lowercase

Removing /r, /n, URLs, numbers, punctuations, stopwords

Removing contractions

Cleaning hashtags and special characters

Removing multi-space characters

Applying stemming and lemmatization

Handled duplicates and removed unnecessary entries.

Performed Exploratory Data Analysis (EDA) for better insights.

Split the dataset into training and testing sets.

Applied TF-IDF Vectorization to convert text into numerical form.

Tested multiple base models:

Logistic Regression

Support Vector Machine (SVM)

Naive Bayes

Decision Tree

Random Forest

AdaBoost

Fine-tuned the Support Vector Machine (SVM) — the best-performing model.

Evaluated model performance and saved the trained model.

Built a front-end Web App using Streamlit for real-time prediction.

Deployed the final application on Streamlit Cloud.





🧩 Model Performance

The SVM model achieved an impressive 84% accuracy in classifying tweets for cyberbullying detection.




📚 Libraries Used

pandas, numpy, matplotlib, seaborn, scipy, re, pickle, string, collections, statsmodels, nltk, emoji, wordcloud, streamlit



☁️ Deployment Platform

Streamlit — used for creating and deploying the interactive web application.



💻 How to Run the Project
# Clone this repository
git clone https://github.com/ItsAhsanSajjad/Cyber-Bullying-Tweet-Recognition-Web-Application.git

# Navigate to the project folder
cd Cyber-Bullying-Tweet-Detection

# Install required libraries
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py




👨‍💻 Author

Ahsan Sajjad
AI | ML Engineer & Software Engineer
📍 Bahawalpur, Pakistan
📧 contactahsansajjad@gmail.com

🌐 GitHub: ItsAhsanSajjad

📜 License

This project is open-source and available under the MIT License.

🌟 Highlights

End-to-end Machine Learning project on real-world text classification

Integrated with Streamlit for an easy-to-use front-end interface

Achieved 84% accuracy using SVM

Fully open-source for learning and contribution
