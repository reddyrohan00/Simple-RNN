# Simple-RNN
🎬 IMDB Movie Review Sentiment Analysis
This is a simple web application built with Streamlit and TensorFlow that analyzes the sentiment (positive or negative) of a movie review using a pre-trained ReLU-activated Simple RNN model trained on the IMDB dataset.

🚀 Features
Accepts free-text movie reviews from users.

Classifies the review as Positive or Negative.

Displays the confidence score of the prediction.

Easy-to-use web interface via Streamlit.

🧠 Model Overview
Trained on the IMDB movie review dataset.

Uses a Simple RNN architecture with ReLU activation.

Input reviews are tokenized and padded to a maximum length of 500 words.

Output is a binary classification (positive or negative sentiment).

📁 Project Structure
bash
Copy
Edit
.
├── simple_rnn.h5              # Pre-trained RNN model
├── main.py                    # Streamlit app and prediction logic
└── README.md                  # This file
🛠️ Requirements
Install the dependencies using pip:

bash
Copy
Edit
pip install -r requirements.txt
Required Libraries:

numpy

tensorflow

streamlit

You can also install them manually:

bash
Copy
Edit
pip install numpy tensorflow streamlit
🏃‍♂️ How to Run the App
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/imdb-sentiment-rnn.git
cd imdb-sentiment-rnn
Make sure simple_rnn.h5 is in the project directory. (Train it yourself or download a provided one.)

Run the Streamlit app:

bash
Copy
Edit
streamlit run main.py
Open your browser to http://localhost:8501 to use the app.

✏️ Example Usage
Type your review:

csharp
Copy
Edit
The movie was absolutely fantastic with brilliant performances!
Click Classify, and get an output like:

✅ We think it is a Positive review
💬 Prediction Score: 0.92

📌 Notes
The model uses a word index from the Keras IMDB dataset.

Unknown or rare words are replaced with a ? placeholder.

Input reviews are tokenized and padded to 500 words.

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Keras IMDB Dataset

Streamlit

TensorFlow & Keras team

Let me know if you'd like a version with badges, installation GIFs, or GitHub Actions integration!
