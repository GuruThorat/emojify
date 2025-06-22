# 🎭 Emojify My Mood

Turn your diary entries into a matching emoji vibe using AI-powered emotion detection!

## ✨ Features

- Enter any text and get AI-detected emotion labels.
- Emojis are mapped to each detected emotion for a fun visual representation.
- Powered by pre-trained HuggingFace transformers models.
- Easy-to-use Streamlit web app interface.
- Optionally, deployable via ngrok for public sharing.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/GuruThorat/emojify.git
cd emojify
```

### 2. Install Dependencies

Make sure you have Python 3.7+ installed. Then install the required packages:

```bash
pip install streamlit transformers torch pyngrok
```

### 3. Run the App

```bash
streamlit run app.py
```

If you want to make your app accessible via a public URL, you can use ngrok:

```bash
python untitled0.py
```

This will set up ngrok and print a public URL in your terminal.

## 📝 Usage

- Open the app in your browser (usually at http://localhost:8501).
- Write a short diary entry in the text box.
- Click **"🔍 Emojify!"**
- See the detected emotion and the corresponding emojis!

## 🧠 Models Used

- [`nateraw/bert-base-uncased-emotion`](https://huggingface.co/nateraw/bert-base-uncased-emotion)
- [`j-hartmann/emotion-english-distilroberta-base`](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base)

## 📦 Dependencies

- streamlit
- transformers
- torch
- pyngrok

## 💡 Notes

- The app caches the model for performance.
- If you want to share your app publicly, you'll need an ngrok authtoken (get one from https://dashboard.ngrok.com/get-started/your-authtoken).
- Don't expose your authtoken in public repositories for security.

## 📄 License

This project is for educational/demo purposes.
