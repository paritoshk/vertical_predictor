# vertical_predictor
Predict verticals based on crunchbase like data for startups 
# 🚀 Vertical Predictor Extravaganza 🚀

Hello, world! 🌍 Here, we present the ultimate Vertical Predictor, an AI system that's so sleek and so powerful, you would think it's from the future! 🤖 Powered by state-of-the-art NLP models and Machine Learning algorithms, this tool makes bold predictions with accuracy that will make your jaw drop.👏

💡 Whether you're a data scientist, a developer, or a C-level executive, this script is your magic wand that turns raw data into gold. 🧙‍♂️🔮✨

## 📚 Documentation

### 🧰 What does it do?
#### 🧲 Data Transformation: Convert names, short descriptions, and industries into numerical embeddings with the power of NLP!
#### 🎯 Vertical Prediction: Elegantly predicts verticals for your data using sophisticated ensemble algorithms!
#### 📊 Performance Metrics: Reports how well the prediction performs with classification reports, accuracy scores!
#### 📈 Visualizations: Beautifully visualizes AUC-ROC curves and confusion matrices!
#### 🕵️ Explainability: Utilizes SHAP values to explain what features are driving the predictions!
#### 🧱 How does it work?
Here's a breakdown of the architecture of this marvellous creation:

Sentence Transformers: They're the hot rods 🏎️ of NLP. We use them to encode the text data into embeddings.
Ensemble Classifiers: Our engine is revved-up with Random Forests, AdaBoost, and Extra Trees classifiers. 🌲🔥
SHAP: SHAP (SHapley Additive exPlanations) lights the way 🌟 by explaining the output of our machine learning model.
Seaborn and Matplotlib: Our artists 🎨 behind those beautiful plots and visualizations.
⚙️ The System Diagram
`
+--------------------+
| Input Data         |
| (Name, Description,|
| Industry, Vertical)|
+---------+----------+
          |
          | (Sentence Transformers)
          |
+---------v----------+
|   Embeddings       |
| (Name, Description,|
|      Industry)     |
+---------+----------+
          |
          | (Machine Learning Models)
          |
+---------v----------+
|   Predicted        |
|     Verticals      |
+---------+----------+
          |
          | (Metrics & Visualizations)
          |
+---------v------------------------+
| Reports (AUC-ROC, SHAP, Confusion|
|       Matrix, Classification)    |
+----------------------------------+
`
####🏁 Getting Started
Just feed in your Data into the main(data) function, and it's Showtime! 🎬 The script will take the raw text data, transform it, predict the verticals, and conjure up visualizations that you can brag about in meetings! 😎

## 🚦 Ready, Set, Go! 🚦

Grab a cup of coffee ☕ or a magic potion, and watch as the script reads your data's palm and predicts its verticals. 🌌

With the accuracy and insights this provides, who needs a crystal ball? Get ready for your data to put on its dancing shoes, because this Vertical Predictor is a party for your spreadsheets! 🎊

Made with ❤️ by coding wizards 🧙 and sold to you with the flair of a rockstar! 🎸

Stay ahead, stay informed, and let the data drive your decisions.
