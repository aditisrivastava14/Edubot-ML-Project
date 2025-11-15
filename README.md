🎓 EduBot – AI-Powered College Chatbot

EduBot is an intelligent, lightweight college-assistant chatbot built using Python, Streamlit, TF-IDF, and cosine similarity.
It answers student queries based on patterns stored in a CSV file — making it simple, fast, and fully customizable.

🚀 Features

Pattern-based query matching using TF-IDF
Auto-response generation based on similarity scores
Fallback responses for low-confidence matches
CSV-driven database for easy updates
Chat history preserved during the session
Simple and clean Streamlit UI

🧠 How EduBot Works

EduBot uses the following logic:

Loads patterns & responses from edubot.csv
Splits comma-separated patterns into individual entries
Converts all patterns into vectors using TF-IDF
Computes similarity with the user query using cosine similarity

Returns:

Best matching response
Or a fallback (“Could you rephrase?”) if similarity < threshold
This makes EduBot simple but surprisingly effective.

🎯 Use Cases

EduBot can be expanded for:

College website helpdesks
Student portals
FAQ automation
Department inquiry systems

