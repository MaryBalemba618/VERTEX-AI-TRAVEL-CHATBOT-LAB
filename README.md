# Vertex AI Travel Chatbot Lab

This project is a travel chatbot built with Streamlit and Gemini on Vertex AI. It can answer travel questions and request the current temperature through a weather function.

## Files

- `app.py` — chatbot interface, Gemini connection, and weather function
- `requirements.txt` — Python packages needed to run the app

## How to run in Google Cloud Shell

1. Select a Google Cloud project with billing enabled.
2. Enable the Vertex AI API:
   `gcloud services enable aiplatform.googleapis.com`
3. In `app.py`, set `PROJECT_ID` to your own project ID.
4. Create and activate a Python virtual environment.
5. Install packages:
   `uv pip install -r requirements.txt`
6. Start the app with Streamlit and open it through Cloud Shell Web Preview.

## What I learned

I practiced setting up a Python environment, connecting a Streamlit app to Gemini, working with a weather function, and troubleshooting project settings, file paths, indentation, and preview ports.
