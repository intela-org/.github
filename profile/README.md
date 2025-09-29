# 🎓 Intela Platform

Udemy kabi **o‘quv platforma** – kurslar yaratish, sotish va o‘qitish uchun.
Bu repo ichida **client (frontend)** va **server (backend)** kodlari jamlangan 🖥️📱.

---

## 📂 Project Structure

```
intela-platform/
 ├── client/   # 🎨 Frontend (Next.js / React)
 ├── server/   # ⚙️ Backend (NestJS / Express)
 ├── shared/   # 📦 Shared code (models, types, utils)
 ├── docker/   # 🐳 Docker configs
 ├── .github/  # 🤖 CI/CD workflows
 └── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone project

```bash
git clone https://github.com/<your-org>/intela-platform.git
cd intela-platform
```

### 2️⃣ Install dependencies

```bash
# frontend
cd client && npm install

# backend
cd ../server && npm install
```

### 3️⃣ Run locally

Frontend:

```bash
cd client
npm run dev
```

Backend:

## 👥 Branch Strategy

* `main` → production ✨
* `dev` → development 🛠
* `feature/*` → yangi funksiyalar 🌱

---## 🐳 Run with Docker

Agar Docker ishlatsang, hamma narsa avtomatik ishlaydi 🔥:


## 🛠 Tech Stack

* **Frontend** → Next.js, React, Tailwind CSS 🎨
* **Backend** → NestJS, Express ⚙️
* **Database** → MongoDB 🍃
* **CI/CD** → GitHub Actions 🤖
* **Container** → Docker 🐳

---

## 🤝 Contributing

1. `feature/*` branch och 🔀
2. Kod yozib test qil ✅
3. Pull Request och 💡
4. Reviewdan o‘tsa `dev` ga merge qilinadi 🚀

---

## 📜 License

MIT License © Intela Platform
