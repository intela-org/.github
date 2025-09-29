🎓 Intela Platform
Udemy kabi o‘quv platforma – kurslar yaratish, sotish va o‘qitish uchun. Bu repo ichida client (frontend) va server (backend) kodlari jamlangan 🖥️📱.

📂 Project Structure
intela-platform/
 ├── client/   # 🎨 Frontend (Next.js / React)
 ├── server/   # ⚙️ Backend (NestJS / Express)
 ├── shared/   # 📦 Shared code (models, types, utils)
 ├── docker/   # 🐳 Docker configs
 ├── .github/  # 🤖 CI/CD workflows
 └── README.md
🚀 Getting Started
1️⃣ Clone project
git clone https://github.com/<your-org>/intela-platform.git
cd intela-platform
2️⃣ Install dependencies
# frontend
cd client && npm install

# backend
cd ../server && npm install
3️⃣ Run locally
Frontend:

cd client
npm run dev
Backend:

cd server
npm run start:dev
🐳 Run with Docker
Agar Docker ishlatsang, hamma narsa avtomatik ishlaydi 🔥:

docker-compose up -d
Frontend → http://localhost:3000
Backend → http://localhost:5000
Database (MongoDB) → mongodb://localhost:27017/intela-db
👥 Branch Strategy
main → production ✨
dev → development 🛠
feature/* → yangi funksiyalar 🌱
🛠 Tech Stack
Frontend → Next.js, React, Tailwind CSS 🎨
Backend → NestJS, Express ⚙️
Database → MongoDB 🍃
CI/CD → GitHub Actions 🤖
Container → Docker 🐳
🤝 Contributing
feature/* branch och 🔀
Kod yozib test qil ✅
Pull Request och 💡
Reviewdan o‘tsa dev ga merge qilinadi 🚀
📜 License
MIT License © Intela Platform
