🌍 Neural Machine Translation (Fine-Tuned T5 Model)

This is a Streamlit web app for translating English text to French using a fine-tuned T5 model.

The app uses the Hugging Face Transformers library and a custom fine-tuned T5 model hosted on Hugging Face.

🔗 Live Demo:https://translator-djpirvrt6c2n5gg5ayd299.streamlit.app/


Try the app online here:
Translator App

🛠 Features

Translate English text to French

Uses a fine-tuned T5 model for accurate translations

Simple and clean Streamlit interface

💻 Usage

Clone the repository:

git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app locally:

streamlit run app.py


Enter English text in the text area and click Translate to get French translation.

📦 Requirements

Python 3.10+

Streamlit

Torch

Transformers

Hugging Face Hub

SentencePiece

Example requirements.txt:

streamlit
torch
transformers
huggingface-hub
sentencepiece

🔑 Notes

The model is hosted on Hugging Face. If it’s a gated/private repo, make sure to provide your Hugging Face token in app.py or via Streamlit secrets.

Works both locally and on Streamlit Cloud.

✅ Conclusion

This project demonstrates how to deploy a fine-tuned NLP model on the web using Streamlit. It provides an easy-to-use interface for translating English text to French while leveraging the power of the T5 transformer model.

This setup can be extended to other languages, more complex translation tasks, or additional NLP applications, making it a solid foundation for exploring real-world AI-powered language tools