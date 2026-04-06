# 🚀 Hello Captain – Python Flask App (Vercel + Docker)

A simple Python web application built with Flask that returns:

```
Hello, Captain!
```

This project demonstrates:

* ✅ Serverless deployment using Vercel
* ✅ Containerization using Docker

---

## Project URL

https://github.com/swatikeshri-2005/Dockerfile-scratch


## 📁 Project Structure

```
python-docker-app/
│
├── app.py              # Flask application
├── requirements.txt    # Dependencies
├── vercel.json         # Vercel config
├── Dockerfile          # Docker config
├── .dockerignore       # Ignore files for Docker
└── README.md
```

---

## ⚙️ Tech Stack

* Python 3.11
* Flask
* Gunicorn
* Docker
* Vercel

---

## 🧠 How It Works

* Flask handles HTTP requests
* `/` route returns "Hello, Captain!"
* Vercel runs the app as a serverless function
* Docker runs the app using Gunicorn in a container

---

## 🌐 Live Demo

After deployment on Vercel:

```
https://your-project-name.vercel.app
```

---

## 🚀 Deployment on Vercel

### 1. Push to GitHub

```
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/your-username/python-docker-app.git
git push -u origin main
```

---

### 2. Deploy

1. Go to Vercel Dashboard
2. Click **"Add New Project"**
3. Import your GitHub repository
4. Click **Deploy**

---

## 🐳 Run with Docker

### Build Image

```
docker build -t python-app .
```

### Run Container

```
docker run -p 8000:8000 python-app
```

Open in browser:

```
http://localhost:8000
```

---

## ▶️ Run Locally (Without Docker)

Install dependencies:

```
pip install -r requirements.txt
```

Run:

```
python app.py
```

---

## ❗ Important Notes

* Vercel does **not use Dockerfile**
* Docker is for local and cloud container deployments
* Keep the app lightweight for serverless environments

---

## 🔥 Future Improvements

* Add dynamic route: `/hello/<name>`
* Convert to FastAPI
* Add REST APIs
* Integrate ML/AI models
* Connect database (MongoDB/PostgreSQL)

---

## 👨‍💻 Author

Swati Keshri

---

## 📜 License

This project is open-source and free to use.



