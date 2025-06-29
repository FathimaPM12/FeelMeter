💬 FeelMeter

A simple web-based Sentiment Analysis application built using Python, Flask, and TextBlob.  
It classifies user input text as *Positive, **Negative, or **Neutral* based on emotional tone.


📌 Features

- Analyze any English sentence for sentiment.
- Categorizes text as Positive 😊, Negative 😞, or Neutral 😐.
- Easy-to-use web interface with Flask.
- Built using TextBlob NLP library.


🛠 Technologies Used

- Python 
- Flask (for web server)
- TextBlob (for NLP)
- HTML (for frontend form)
- Jinja2 (templating engine)

🚀 How It Works

1. User enters a sentence in the web interface.
2. Backend sends it to TextBlob.
3. TextBlob calculates *polarity* score:
   - > 0 = Positive
   - < 0 = Negative
   - == 0 = Neutral
4. The app displays the sentiment to the user.

🧪 Example Inputs

"I love this app!" → Positive

"This is terrible." → Negative

"I am at the store." → Neutral

📁 Project Structure

FeelMeter/
├── app.py
└── templates/
    └── index.html
