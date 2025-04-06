🛡️ SafeScanAI

**SafeScanAI** is an AI-powered tool that detects toxic or harmful content (hate speech, bullying, threats, etc.) using a pre-trained NLP model. It helps platforms moderate conversations at scale and maintain safer online communities.

---

💡 Features

- 🔍 Real-time detection of toxic content  
- ⚙️ Uses pre-trained BERT-based model from HuggingFace  
- ✅ Labels text as TOXIC or NON-TOXIC  
- 📈 Displays prediction confidence score  
- 💻 Runs in Google Colab and locally via Streamlit  
- 📦 Lightweight, fast, and easy to use  

---

🚀 Link
https://colab.research.google.com/drive/1MniKOqeXlO9C3F7z1rQSjNVWPvYBfEoK?usp=sharing



---
 🏗 Architecture Diagram

User Input --> Preprocessing --> ToxicBERT Model --> Output Prediction


---

🔄 Process Flow

1. User inputs text  
2. Text is preprocessed (cleaning, tokenization)  
3. Passed to `unitary/toxic-bert` model  
4. Model returns a toxicity probability  
5. System labels the input based on a threshold (e.g., 0.5)  
6. Result shown to user  

---

 🛠 Technologies Used

- Python
- HuggingFace Transformers (`unitary/toxic-bert`)
- Google Colab

---

 📸 Screenshots

![image](https://github.com/user-attachments/assets/36b4dc94-7f47-44cf-af6c-17c8927191bf)

---

