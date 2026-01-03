🎨 Creative Showcase – Art Gallery Platform

A full-stack art gallery platform where users can upload, manage, and showcase creative artworks.
Built using React (Vite) on the frontend and Node.js + Express + MongoDB on the backend.

hosted project link:- https://creative-showcase-image.onrender.com

🚀 Features
👤 User Features

User authentication (Register / Login)

Secure access using JWT

Upload artwork images

View personal uploaded artworks

Public gallery view

🖼️ Gallery Features

Responsive masonry-style layout

Image storage & retrieval

Optimized frontend using Vite

Tailwind CSS for modern UI

🛠️ Tech Stack
Frontend (Client)

React (Vite)

Tailwind CSS

JavaScript (ES6+)

Axios

ESLint

Backend (Server)

Node.js

Express.js

MongoDB

Mongoose

JWT Authentication

Multer (Image uploads)

📁 Project Structure
Creative_Showcase-art_gallery/
│
├── client/
│   └── creative-showcase/
│       ├── public/
│       │   └── vite.svg
│       ├── src/
│       │   ├── assets/
│       │   ├── components/
│       │   ├── Pages/
│       │   ├── App.jsx
│       │   ├── main.jsx
│       │   ├── App.css
│       │   └── index.css
│       ├── index.html
│       ├── tailwind.config.js
│       ├── vite.config.js
│       ├── package.json
│       └── README.md
│
├── models/
│   ├── Image.js
│   └── User.js
│
├── routes/
│   ├── auth.js
│   └── images.js
│
├── uploads/
│   └── .gitkeep
│
├── server.js
├── package.json
├── .gitignore
├── MONGODB_SETUP.md
├── QUICK_START.md
├── SETUP.md
└── README.md

⚙️ Environment Variables

Create a .env file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

🧑‍💻 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Ranjan20Das/Creative_Showcase-art_gallery.git
cd Creative_Showcase-art_gallery

2️⃣ Backend Setup
npm install
npm start


Backend runs at:

http://localhost:5000

3️⃣ Frontend Setup
cd client/creative-showcase
npm install
npm run dev


Frontend runs at:

http://localhost:5173

📸 Image Upload Handling

Uploaded images are stored in the /uploads directory

.gitkeep ensures the folder remains tracked by Git

Multer is used for handling multipart/form-data

🔐 Authentication Flow

User registers / logs in

JWT token generated on login

Protected routes validate JWT

User-specific image access

🧪 API Routes Overview
Auth Routes
POST   /api/auth/register
POST   /api/auth/login

Image Routes
POST   /api/images/upload
GET    /api/images
GET    /api/images/user

📈 Future Improvements

Image likes & comments

Search & filter by categories

User public profile pages

Cloud image storage (Cloudinary / S3)

Admin dashboard

🤝 Contribution

Contributions are welcome!

Fork the repository

Create a new branch

Commit your changes

Push and open a Pull Request

📝 Author

Manotosh Maity
GitHub: @manotoshmaity

⭐ Support

If you like this project, don’t forget to ⭐ star the repo!
