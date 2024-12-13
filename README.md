# NLP Chatbot Using Transformers, FastAPI, and Uvicorn

## Overview  
This repository showcases an advanced NLP-powered chatbot using Hugging Face's `Transformers` library, `FastAPI` for API development, and `Uvicorn` for asynchronous API deployment. The chatbot is designed for query understanding, intent recognition, and seamless API integration.

---

## Key Features  

### 🔍 **Query Understanding & Intent Recognition**  
- Utilizes Hugging Face `Transformers` for tokenization, contextual embedding, and query processing.  
- Implements pre-trained models like `GPT-2` for Natural Language Understanding (NLU).  
- Supports contextual query handling and fine-tuning for enhanced accuracy.

### ⚙️ **Model Deployment & API Integration**  
- **FastAPI**-based REST API for real-time chatbot interaction.  
- **Uvicorn** server for scalable, asynchronous API deployment.  

### 📡 **Secure Public Hosting**  
- **Ngrok** integration for secure public URL access during development.
- Extensible API endpoints compatible with third-party services like **Dialogflow**.

---

## Technical Stack  

| **Category**              | **Technologies**            |
|--------------------------|------------------------------|
| **Languages**             | Python                     |
| **NLP Framework**         | Hugging Face Transformers  |
| **API Framework**         | FastAPI, Uvicorn           |
| **Hosting & Deployment**  | Ngrok                      |

---

## Current Status  
🚧 **Work in Progress**  
- [ ] Custom chatbot model training using `GPT-2`-based models.  
- [ ] Enhancing context-aware query understanding.  
- [ ] Expanding real-time response generation.  

---

## Installation Guide  

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/Gaurav-B-R/NLP_Chatbot_Transformers_FastAPI.git
   cd NLP_Chatbot_Transformers_FastAPI
   ```

2. **Create a Virtual Environment and Install Dependencies:**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

---

## Usage  

1. **Run the API Server:**  
   ```bash
   uvicorn main:app --host 0.0.0.0 --port 8000 --reload
   ```

2. **Access API Endpoints:**  
   - Visit: `http://localhost:8000/docs` for interactive API documentation.  

---

## Roadmap  

- [x] Setup FastAPI and Uvicorn  
- [x] Build Initial API Endpoints  
- [ ] Integrate Pre-trained Transformers (`GPT-2`)  
- [ ] Improve Intent Recognition Accuracy  
- [ ] Add Contextual Memory for Multi-turn Conversations  
- [ ] Deploy on Cloud Platforms  

---

## Contribution  
Contributions are welcome! Feel free to raise issues, suggest new features, and submit pull requests.  

---

## License  
Pending License Addition (MIT Recommended).

