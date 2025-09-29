# 🎓 Intela — Next-Gen Learning Platform

**Intela** — zamonaviy onlayn ta’lim platformasi, bu yerda **o‘qituvchilar kurs yaratadi, sotadi**, va **o‘quvchilar bilim oladi**.
Ma’lumot yetkazish va bilim olishni **interaktiv, shaffof va global** qilish bizning maqsadimiz 🌍.

---

## ✨ Features

* 👩‍🏫 **Instructor Dashboard** — kurs yaratish, video yuklash, narx belgilash
* 🎥 **Interactive Courses** — video, test va topshiriqlarni qo‘llab-quvvatlaydi
* 💳 **Secure Payments** — xavfsiz va tez to‘lov tizimi
* 📈 **Analytics** — o‘qituvchilar uchun o‘quvchilar faolligini kuzatish
* 🌐 **Multi-language Support** — turli tillarda o‘qish imkoniyati
* 📱 **Responsive Design** — web va mobil qurilmalarda ishlaydi

---

## 🛠 Tech Stack

**Frontend (Client)**

* Next.js + React ⚛️
* Tailwind CSS 🎨

**Backend (Server)**

* NestJS + Express ⚙️
* MongoDB 🍃 (asosiy database)

**DevOps & Infra**

* Docker 🐳 (deploy & local env)
* GitHub Actions 🤖 (CI/CD)

---

## 📂 Project Structure

```
intela/
 ├── client/    # 🎨 Frontend (Next.js)
 ├── server/    # ⚙️ Backend (NestJS)
 ├── shared/    # 📦 Common models & utils
 ├── docker/    # 🐳 Docker configs
 └── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the project

```bash
git clone https://github.com/intela-org/intela.git
cd intela
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

```bash
cd server
npm run start:dev
```

## 👥 Branch Strategy

* `main` → production ✨
* `dev` → development 🛠
* `feature/*` → yangi funksiyalar 🌱

---

## 🤝 Contributing

1. `feature/*` branch och 🔀
2. Kod yozib test qil ✅
3. Pull Request och 💡
4. Review’dan o‘tgach `dev` ga merge qil 🚀

---

## 📜 License

MIT License © [Intela](https://github.com/intela-org)
