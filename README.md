# 📚 BookNexus | The Ultimate Book Review Platform

BookNexus is a book review application that connects readers and authors. Readers can explore thousands of books, leave reviews, and engage with a community of book lovers. Authors can publish books and manage their works, receiving valuable feedback from readers.

## 🌟 Features

- **Explore Books** – Browse thousands of books across various genres.
- **Book Reviews** – Read and share insightful reviews.
- **Publish Books** – Authors can upload and manage their books.
- **User Engagement** – Rate and comment on books.
- **Responsive UI** – Optimized for all devices.

## 🛠 Tech Stack

**Frontend:** React.js, Redux Toolkit, Axios, Tailwind CSS, React Router  
**Backend:** Node.js, Express.js, MongoDB, Cloudinary  
**Authentication:** JWT & Cookies  
**Deployment:** Vite  

## 📥 Installation Guide

```sh
git clone https://github.com/yourusername/booknexus.git
cd booknexus
```

```sh
cd backend
npm install
```
- Create a `config` folder inside `backend/`.
- Add a `config.env` file and include:

```env
MONGO_URL = your_mongodb_connection_string
COOKIES_EXPIRES = 7d
JWT_SECRET_KEY = your_secret_key
JWT_EXPIRES = 7d
CLOUDINARY_NAME = your_cloudinary_name
CLOUDINARY_API_KEY = your_cloudinary_api_key
CLOUDINARY_API_SECRET = your_cloudinary_secret
FRONTEND_URL = http://localhost:5173
```

```sh
npm start
```

```sh
cd ../frontend
npm install
```
- Create a `.env` file in `frontend/` and add:

```env
VITE_APP_NAME = BookNexus
VITE_APP_BASE_URL = your_backend_url
```

```sh
npm run dev
```

## 🚀 Usage

1. Open `http://localhost:5173` in your browser.
2. Sign up or log in.
3. Explore, review, and manage books.
4. Engage with the book-loving community.

## 🤝 Contributing

```sh
git checkout -b feature-name
git commit -m "Added new feature"
git push origin feature-name
```
Open a pull request.

## 💡 Acknowledgments

A special thanks to book lovers and developers who contribute to making **BookNexus** a valuable platform! 🚀

