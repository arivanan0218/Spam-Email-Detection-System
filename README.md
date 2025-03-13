# Spam Email Classifier

This project is a **Spam Email Classifier** built using Python, **Natural Language Processing (NLP)** techniques, and machine learning. It uses the **Multinomial Naive Bayes** algorithm and **CountVectorizer** for text processing. The model is integrated with a **Flask web application** to provide a user interface for predictions.

---

## Features
- Email text preprocessing using **NLTK** (Stemming, Tokenization, etc.)
- Advanced **NLP techniques** for text cleaning and transformation
- Bag of Words (BoW) model created using **CountVectorizer**
- Spam and Ham email classification using **Multinomial Naive Bayes**
- Flask web application for user-friendly predictions

---

## Dataset
The dataset used in this project is the **Spam Email Dataset**, where each email is labeled as either "ham" (non-spam) or "spam".

---

## Project Structure
```
|-- app.py
|-- train.py
|-- model.pkl
|-- cv-transform.pkl
|-- templates
|   |-- home.html
|   |-- result.html
|-- static
|-- README.md
```

---

## Installation
To run this project, follow these steps:

### Step 1: Clone the Repository
```
git clone https://github.com/arivanan0218/Spam-Email-Detection-System.git
cd Spam-Email-Detection-System
```

### Step 2: Run the Training Script
Since dependencies are installed globally, ensure you have the required libraries:

**Required Libraries:**
- pandas
- scikit-learn
- nltk
- flask
- seaborn
- matplotlib

If any library is missing, install it using:
```
pip install <library_name>
```

### Step 3: Run the Training Script
```
python train.py
```

### Step 4: Run the Flask Application
```
python app.py
```

### Step 5: Access the Web App
Open your browser and go to: `http://localhost:5000`

---

## Usage
### Training the Model
- The `train.py` file handles data preprocessing, model training, and saving the model as a `.pkl` file.
- Run `train.py` to create the `model.pkl` and `cv-transform.pkl` files required for predictions.

### Running the Web Application
- Run `app.py` to launch the Flask web application.
- Enter an email message in the text box on the homepage.
- The app will predict whether the message is **Spam** or **Ham**.

---

## Example Predictions
| Email Message | Prediction |
| -------------- | ----------- |
| "Win $1000 now! Click here." | Spam |
| "Hey, let's catch up for dinner." | Ham |

---

## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request.

---

## Contact
For questions or support, please contact Arivanan V at vamathevanarivanan@gmail.com.

