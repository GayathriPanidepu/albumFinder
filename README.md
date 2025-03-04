
# 🎵 Spotify Album Finder

## 🚀 Overview
The **Spotify Album Finder** is a sleek and interactive React-based web app that lets you search for your favorite artists and explore their albums using the **Spotify Web API**. With a smooth UI powered by **React-Bootstrap**, this project is an excellent way to enhance your web development skills while working with APIs!

## ✨ Features
✅ Search for any artist using the Spotify API
✅ Retrieve and display albums with cover images & release dates
✅ Click on an album to open it directly on Spotify
✅ Modern and responsive UI using **React-Bootstrap**
✅ Fast performance with **Vite**

---

## 📌 Prerequisites
Before diving in, make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or later)
- A [Spotify Developer Account](https://developer.spotify.com/)
- A [GitHub account](https://github.com/)

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone  https://github.com/GayathriPanidepu/albumFinder.git
cd album_finder
```

### 2️⃣ Install Dependencies
```bash
npm install
```

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


### 3️⃣ Set Up Spotify API Credentials
1. Go to [Spotify for Developers](https://developer.spotify.com/)
2. Log in and navigate to the **Dashboard**
3. Click **Create App**, provide the required details, and get your API keys
4. Create a `.env` file in the root of your project and add:
   ```plaintext
   VITE_CLIENT_ID=YOUR_CLIENT_ID
   VITE_CLIENT_SECRET=YOUR_CLIENT_SECRET
   ```
5. Ensure `.env` is in your `.gitignore` file to keep your credentials safe.

### 4️⃣ Start the Development Server
```bash
npm run dev
```
Your app will be available at: **`http://localhost:3000/`** 🎉

---

## 🎨 Usage Guide
1️⃣ **Enter an artist’s name** in the search bar
2️⃣ **Click "Search"** to fetch the artist’s albums
3️⃣ **Browse through albums**, including cover images & release dates
4️⃣ **Click an album** to open it on **Spotify**

---

## 💻 Tech Stack
🔹 **React** – For building the UI  
🔹 **Vite** – For fast development  
🔹 **React-Bootstrap** – For stylish and responsive UI  
🔹 **Spotify Web API** – For fetching album data  

---

## 📂 Project Structure
```
spotify-album-finder/
├── public/
├── src/
│   ├── components/
│   ├── App.jsx
│   ├── main.jsx
│   ├── styles/
│   ├── hooks/
├── .env
├── .gitignore
├── package.json
├── README.md
```

---

## 🚀 Deployment
To deploy the project:
1. **Build the project:**
   ```bash
   npm run build
   ```
2. **Deploy using platforms like Vercel or Netlify**

---

## 🎶 Acknowledgments
Special thanks to **Spotify API documentation** for making music data accessible to developers! 

Enjoy building & discovering music with the **Spotify Album Finder**! 🎧🚀

