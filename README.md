
# 📝 TODO Web Application

A simple and elegant TODO web app built using **Flask** as the backend framework and styled with **Bootstrap**. The app is deployed and live using **Render**.

---

## 🚀 Live Demo

🔗 [https://todo-xrkd.onrender.com](https://todo-xrkd.onrender.com)

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, Bootstrap 5
- **Database**: SQLite (default with Flask)
- **Deployment**: Render

---

## 📦 Features

- ✅ Add new TODO tasks
- 🗑️ Delete existing tasks
- 🧾 Store tasks persistently using SQLite
- 📱 Responsive design using Bootstrap
- ⚡ Fast and minimal web UI

---

## 🧑‍💻 Local Setup

Follow these steps to run the app locally:

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate      # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python app.py
```

Now open your browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📁 Project Structure

```
.
├── app.py                  # Main Flask app
├── requirements.txt        # Python dependencies
├── Procfile                # For Render deployment
├── templates/
│   └── index.html          # Main HTML page
├── static/                 # CSS/JS files (if any)
└── README.md               # This file
```

---

## 🌐 Deployment on Render

Steps to deploy this project on [Render](https://render.com):

1. Push your code to a GitHub repository.
2. Go to Render and create a new **Web Service**.
3. Connect your GitHub repo.
4. Set the build and run commands:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `gunicorn app:app`
5. Make sure your repo includes:
   - `requirements.txt`
   - `Procfile` with:
     ```
     web: gunicorn app:app
     ```

---

## 📬 Contact

Created by **Vishal Kumar**

- 📧 Email: [vishalcr9028@gmail.com](mailto:vishalcr9028@gmail.com)
- 🔗 LinkedIn: [Vishal Chaudhary](www.linkedin.com/in/vishal-chaudhary--)

---

⭐ If you found this project helpful, feel free to star the repository!
