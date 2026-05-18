# Leadora - AI-powered embeddable chat widget for lead generation and customer engagement.


* ⚛️ Frontend: React (Vite)
* ⚙️ Backend: Node.js + Express
* 📦 Package Manager: pnpm

---

## 📁 Project Structure

```
project/
├── frontend/        # React + Vite app
├── backend/         # Express API
└── README.md
```

---

## ⚡ Tech Stack

### Frontend

* React
* Vite
* JavaScript / TypeScript (optional)

### Backend

* Node.js
* Express
* CORS
* dotenv

### Tooling

* pnpm
* nodemon (dev)

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/USERNAME/REPO.git
cd REPO
```

---

## 📦 Install Dependencies

### Install frontend dependencies

```bash
cd frontend
pnpm install
```

### Install backend dependencies

```bash
cd ../backend
pnpm install
```

---

## 🚀 Run the Project

### ▶️ Start Frontend

```bash
cd frontend
pnpm dev
```

Frontend runs at:

```
http://localhost:5173
```

---

### ▶️ Start Backend

```bash
cd backend
pnpm dev
```

Backend runs at:

```
http://localhost:5000
```

---

## 🌐 API Example

Backend test route:

```
GET /
```

Response:

```
API running...
```

---

## 🔧 Environment Variables

Create a `.env` file inside `backend/`:

```env
PORT=5000
```

---

## 📌 Scripts

### Backend (`backend/package.json`)

```json
{
  "scripts": {
    "dev": "nodemon index.js",
    "start": "node index.js"
  }
}
```

---

## 🔗 Future Improvements

* Add authentication (JWT / Better Auth)
* Connect frontend & backend properly
* Add database (MongoDB / PostgreSQL)
* Setup pnpm workspaces (monorepo optimization)
* Deploy frontend (Vercel) + backend (Render / Railway)


