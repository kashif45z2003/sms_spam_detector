# SMS Spam Detector (Module 21 Challenge)

## 📌 Overview

This project is part of the Module 21 Challenge from the Ohio State University AI Bootcamp. The goal was to refactor an SMS spam classifier using a machine learning pipeline and deploy it as a user-friendly Gradio web app. 

Users can enter a text message and receive a classification result — either **ham (not spam)** or **spam** — based on a trained model using a real-world SMS dataset.

---

## 🔍 How It Works

- The model is trained using a **TF-IDF Vectorizer** and a **Linear Support Vector Classifier (LinearSVC)**.
- Data is split into **67% training** and **33% testing** to evaluate model performance.
- The Gradio interface allows users to test any SMS message and receive immediate classification.

---

## 📁 Files Included

- `gradio_sms_text_classification.ipynb`: Final Gradio app notebook.
- `sms_text_classification_solution.ipynb`: Original solution file used for refactoring.
- `SMSSpamCollection.csv`: Dataset used to train and test the model.
- `README.md`: Documentation for the project.

---

## 🚀 How to Run

1. Clone this repo to your local machine.
2. Install dependencies: `scikit-learn`, `pandas`, `gradio`.
3. Run the Gradio app cell to launch the interface.
4. Input any text message to see whether it's classified as spam or not.

---

## 🌐 Public Gradio App (Optional)

If you enabled `share=True`, include your public app link here:

**🔗 [Launch App](https://your-gradio-link.gradio.live)**

---

## 📊 Dataset Reference

**Tiago, A., Hidalgo, J. (2012).** SMS Spam Collection.  
UCI Machine Learning Repository  
[https://archive.ics.uci.edu/dataset/228/sms+spam+collection](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)

License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## 🧠 Notes

- The model may classify borderline messages differently based on training data.
- Accuracy may slightly vary due to data shuffling and split.

---

## 👤 Author

**Kashif Zafar**  
AI Bootcamp – OSU (edX/Trilogy)
