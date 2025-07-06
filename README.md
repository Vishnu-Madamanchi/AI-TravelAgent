# 🧳 End-to-End Travel Agent using LangGraph

This project demonstrates how to build a fully functional AI Travel Agent using **LangGraph**, **Streamlit**, and **OpenAI** tools. It can search for places, suggest destinations, plan itineraries, and send travel recommendations via email.

---

## 🚀 Features

- Conversational AI-powered travel assistant
- Uses SerpAPI for search results
- Uses SendGrid to email the final travel plans
- Built using LangGraph and deployed via Streamlit
- End-to-end application runnable from Google Colab

---

## 🛠️ Setup Instructions

### 1. Install Required Packages

Run the following inside a Colab or compatible Python environment:

```bash
pip install langgraph openai streamlit sendgrid serpapi
```

### 2. Set Environment Variables

Replace with your actual credentials before running:

```python
import os

os.environ["OPENAI_API_KEY"] = "<your_openai_api_key>"
os.environ["SERPAPI_API_KEY"] = "<your_serpapi_key>"
os.environ["SENDGRID_API_KEY"] = "<your_sendgrid_key>"
os.environ["SENDGRID_SENDER_EMAIL"] = "<your_verified_sender_email>"
os.environ["USER_EMAIL"] = "<recipient_email>"
```

---

## 📜 How It Works

1. The notebook writes a `travel_app.py` file containing:
   - Streamlit web interface
   - LangGraph-powered AI logic
   - Tool integrations (Search and Email)
2. The Streamlit app is launched to interact with the user.
3. Travel recommendations are generated and emailed to the user.

---

## ▶️ Running the App

After setting up the environment, run the app:

```bash
streamlit run travel_app.py
```

Use tools like `ngrok` or Google Colab's public link feature to expose the UI.

---

## 📁 File Structure

```
.
├── End_to_End_Travel_Agent_using_Langgraph.ipynb
└── travel_app.py
```

---

## 📸 Sample Output

- Interactive trip planning
- Sent email with personalized itinerary
- Real-time search for destination highlights

---

## 🙏 Credits

Code and approach courtesy of **Vizuara**. Huge thanks to their contribution to open-source AI projects.

---

## 📬 Contact

Feel free to contribute or ask questions via GitHub issues or pull requests.
