# IntelliMentor AI

**IntelliMentor** is an AI-powered personal coach designed to help users master mock interviews, practice aptitude and reasoning questions, boost their personality development, conduct group discussions (GDs), and even generate images & videos for creative and training purposes.

---

## 🚀 **Key Features**

- ✅ **Mock Interviews** — Practice technical & HR questions with AI.
- ✅ **Aptitude & Reasoning Q&A** — Get accurate answers and explanations.
- ✅ **Personality Development** — Tips & guidance to boost confidence and communication.
- ✅ **GD Simulator** — Conduct and participate in AI-driven group discussions.
- ✅ **Creative Generation** — Generate custom images and 3D videos as per user requirements.

---

## ⚙️ **Tech Stack**

**Backend:** Python (FastAPI)  
**Frontend:** Next.js (React)  
**AI/LLM:** OpenAI API (or custom models)  
**Optional:** Vector DB (e.g., Pinecone), Authentication, Cloud Storage

---

## 📂 **Project Structure**

my-intellimentor-ai/
├── backend/
│ ├── app.py
│ ├── routes/
│ │ ├── chat.py
│ │ ├── interview.py
│ │ ├── gd.py
│ │ ├── imagegen.py
│ ├── requirements.txt
│
├── frontend/
│ ├── package.json
│ ├── pages/
│ │ ├── index.js
│ │ ├── interview.js
│ │ ├── gd.js
│ ├── components/
│ │ ├── ChatBox.js
│ │ ├── GDChatBox.js

## COMANDS FOR BACKEND
cd backend
python -m venv venv
# Activate venv:
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

pip install -r requirements.txt

# Run backend server
uvicorn app:app --reload

By default, FastAPI runs on http://127.0.0.1:8000.

cd ../frontend
npm install
npm run dev
Frontend runs on http://localhost:3000.

📌 Future Enhancements
✅ OAuth login (Google, GitHub)
✅ Role-based access
✅ Data storage with PostgreSQL
✅ Vector DB for context memory
✅ Cloud deployment (Docker, Kubernetes)
✅ Advanced prompt tuning and multi-modal AI

