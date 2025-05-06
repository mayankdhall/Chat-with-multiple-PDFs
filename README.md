# 📄 Chat with Your PDF using Gemini AI

A smart, interactive Streamlit app that allows you to chat with your PDF files using Google's **Gemini 1.5 Flash** model. Upload one or more PDFs, ask any question about the contents, and get accurate, context-aware responses powered by AI.

## 💡 Features

- 📂 Upload multiple PDF files
- 🤖 Ask questions in natural language
- 🧠 Uses Google's Gemini 1.5 Flash LLM
- 🔍 Semantic search with FAISS and embeddings
- 🧾 Extracts content from long documents
- ✅ Provides accurate answers based on context

- ## ⚙️ Tech Stack

| Tool               | Purpose                                 |
|--------------------|-----------------------------------------|
| Streamlit          | Frontend web app                        |
| LangChain          | LLM orchestration & prompt templates    |
| Google Generative AI | Embeddings & LLM (Gemini 1.5)         |
| FAISS              | Vector search on text chunks            |
| PyPDF2             | Extract text from PDF files             |
| dotenv             | Load API keys securely                  |

---

# Chat with PDF, Text, or JSON Files App

This app allows you to chat with PDF, text, or JSON files using AI. You can upload your files, ask questions, and get intelligent responses based on the file content. Below are the steps to use the app.

---

## Steps to Use the App

### Step 1: Access the File Upload Interface
1. Open the app in your browser (e.g., at `localhost:8501` if running locally).
2. On the left sidebar, locate the **Upload Files** section.
3. You’ll see a box labeled **"Drag and drop files here"** with the note: **"Limit 200MB per file • PDF, TXT, JSON"**.
4. You can either:
   - Drag and drop your files into the box, or
   - Click the **Browse files** button to select files from your device.

   ![3](https://github.com/user-attachments/assets/c8272f24-26c6-4680-a0cf-f9f2633ee785)


---

### Step 2: Upload Files
1. Upload the files you want to process.
2. Example files uploaded:
   - **Hybrid.txt** (4.0KB)
   - **ev.json** (3.8KB)
   - **AI_file.pdf** (37.9KB)
3. After uploading, the files will appear in the sidebar with their names and sizes.
   - Each file has an "X" button to remove it if needed.
4. Click the **Submit & Process** button below the file list to process the uploaded files.

![1](https://github.com/user-attachments/assets/c66b2338-013a-4a78-a179-4d6c0dc4e31a)


---

### Step 3: Ask a Question About Your Files
1. Once the files are processed, the main section will display: **"Chat with your PDF, Text, or JSON Files using AI"**.
2. Below this, find the text input field labeled **"Ask a question about your files:"**.
3. Type your question in the input field. For example:  
   - **Example Question:** _"What challenges do businesses face when managing hybrid teams, and how can they address them?"_
4. Press **Enter** or wait for the app to process the question automatically.
5. The app will display the response below the input field.  
   **Example Response:**
   - **Communication and Collaboration:** Issues with managing a workforce split between in-office and remote employees.
   - **Isolation and Disengagement:** Challenges with hybrid teams feeling isolated.
   - **Equity and Fairness:** Potential divides between in-office and remote employees.

---

### Step 4: View Suggested Questions (Optional)
1. After processing the files, the app may generate suggested questions based on the file content.
2. These questions will appear below the main input field under a **"Suggested Questions"** section.
3. Click on any suggested question to automatically ask it and receive a response.

---

### Step 5: Ask Another Question and View Conversation History
1. To ask another question, type it into the same input field.  
   **Example Question:** _"How can AI art be integrated into various industries, such as advertising, film, and design?"_
2. The app will respond based on the files you’ve uploaded. If the files don’t contain specific details, the app will provide a general answer, often using web search as a fallback.

![2](https://github.com/user-attachments/assets/b25ffe63-c89e-4e21-bab0-af2f34c1e599)

---

Feel free to explore and experiment with different files and questions. Happy chatting!
