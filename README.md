#  Adaptive Meal Planner using RAG & Google Gemini

An intelligent, AI-powered **Adaptive Meal Planner** that leverages **RAG (Retrieval-Augmented Generation)** to generate personalized meal plans based on user-uploaded **Medical Health Reports**. The system intelligently adapts dietary recommendations to individual health conditions using Google Gemini 2.5 Pro and efficient semantic search embeddings.

---

##  Features

-  **Medical Report Analysis**  
  Upload your health reports (PDF, text) and extract meaningful data to guide dietary planning.

-  **LLM Integration with Google Gemini 2.5 Pro**  
  Uses a powerful LLM to generate health-conscious, context-aware responses and recommendations.

-  **RAG Architecture**  
  Combines vector-based retrieval with generative reasoning for accurate, personalized output.

-  **Embeddings with `all-MiniLM-L6-v2`**  
  Lightweight, fast, and highly effective model for sentence-level semantic understanding and retrieval.

-  **Custom Meal Plans**  
  Generates adaptive meal suggestions considering conditions like:
  - Diabetes
  - High/Low Blood Pressure
  - Obesity/Underweight
  - Cholesterol
  - Nutrient deficiencies

- 💬 **Conversational Meal Planning**  
  Users can interact with the chatbot to ask questions and get personalized meal plans in natural language.

---

##  Tech Stack

| Layer        | Technology                         |
|--------------|-------------------------------------|
| Frontend     | Streamlit                          |
| LLM          | Google Gemini 2.5 Pro              |
| Embeddings   | `all-MiniLM-L6-v2` (SentenceTransformers) |
| Vector Store | FAISS                              |
| Backend      | Python                             |
| RAG Framework| LangChain                          |
| File Parsing | PyMuPDF / LangChain Document Loaders|

---


---

## 🔧 How It Works

1. **Upload** a medical report via Streamlit UI.
2. **Parse & Embed** the report using `all-MiniLM-L6-v2`.
3. **Store** embeddings in a FAISS vector database.
4. **Query** the database with user questions.
5. **Generate** grounded responses using Gemini 2.5 Pro.

---

## Use Cases

- Patients seeking diet modifications for chronic conditions.
- Nutritionists and healthcare professionals building adaptive diet plans.
- Fitness-conscious users seeking AI-driven diet tracking.

---

##  Future Improvements

- Add multilingual support.
- Enable meal plan export (PDF, Calendar sync).
- Incorporate nutrition APIs for real-time food data.
- Build user profile history for progress tracking.

---

##  Skills Demonstrated

- LangChain-based RAG Implementation  
- LLM Integration (Google Gemini Pro)  
- Embedding Models & FAISS  
- Natural Language Processing (NLP)  
- Health & Wellness Application Design  
- Streamlit App Deployment

---

*This project showcases the power of LLMs combined with user-specific knowledge to build meaningful, real-world applications in the healthcare domain.*

---

