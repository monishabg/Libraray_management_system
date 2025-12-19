# Library Management System – FastAPI Backend

## 1️⃣ Clone the Repository
```bash
git clone <your-repo-url>
cd <repo-folder>
2️⃣ Install Requirements
bash
Copy code
pip install -r requirements.txt
3️⃣ Create .env File
Before running the server, create a .env file in the root directory:

env
Copy code
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.fbwqkgq.mongodb.net/Library_Management_System
4️⃣ Run the Server (Port 3000)
bash
Copy code
uvicorn app.main:app --host 0.0.0.0 --port 3000 --reload
5️⃣ Test API
Open your browser and go to:

bash
Copy code
http://localhost:3000/docs
