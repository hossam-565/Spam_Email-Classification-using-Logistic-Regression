# Spam_Email-Classification-using-Logistic-Regression
📧 Spam Email Classification using Logistic Regression
📝 Description
This project implements a logistic regression model to classify emails as Spam or Non-Spam.
It uses TF-IDF vectorization to convert email text into numerical data and applies a custom-trained model for accurate predictions.
The application includes visualization features and an interactive interface to test custom emails.

📚 Table of Contents
✨ Features
⚙️ Installation
🚀 Usage
📊 Visualizations
📋 Example Output
💡 Future Improvements
👤 Author
✨ Features
✅ Preprocesses email text using TF-IDF vectorization.
✅ Implements a logistic regression model with gradient descent.
✅ Generates visualizations to monitor training progress:
Loss and accuracy curves.
Confusion matrix.
Most significant words for spam and non-spam classification.
✅ Provides an interactive mode to classify custom emails.
⚙️ Installation
1️⃣ Clone the project
Download the project from GitHub or any other repository. For example:
git clone https://github.com/your-repo/spam-classifier.git

2️⃣ Navigate to the project directory
cd spam-classifier

3️⃣ Install dependencies
Ensure Python 3.x is installed, then run:
pip install -r requirements.txt

4️⃣ Add the dataset file
Place the file spam_dataset.csv in the same directory as the main script.

🚀 Usage
Run the script:
python spam_classifier.py

Process:

The model will train, and metrics will be displayed.
You can enter custom emails to test whether they are classified as spam or not.
📊 Visualizations
This project generates several visualizations to analyze results:

Loss and Accuracy Curves

Confusion Matrix

Top Words for Spam and Non-Spam

📋 Example Output
Interactive Prediction Example
Email: "Congratulations! You've won a free iPhone. Click here to claim your prize."
Prediction: Spam
Probability: 87.23%

Email: "Let's meet for coffee tomorrow at 10 AM."
Prediction: Non-Spam
Probability: 12.45%

💡 Future Improvements
🔍 Incorporate advanced text embedding techniques like BERT or Word2Vec.
⚙️ Experiment with modern optimizers such as Adam.
🌐 Develop a web interface for easier interaction.
