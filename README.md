# 🎬 MovieVerse

A fast, modern movie search app built with **React + Vite**, leveraging **Appwrite** for backend services and optimized search performance using **debouncing**.

Live Demo: 👉 [movieverse-iyyp.onrender.com](https://movieverse-iyyp.onrender.com)

---

## 🚀 Features

- 🔍 **Search Movies Instantly** – Search is optimized using the `use-debounce` hook to reduce unnecessary API calls while typing.
- 🔥 **Trending Movies Section** – View popular and trending movie data fetched via The Movie Database (TMDb) API.
- ⚡ **Built with Vite** – Super fast development experience and optimized builds.
- 📦 **No Backend Code Required** – All backend services like data storage and analytics are handled by **Appwrite**.
- 🖼️ **Beautiful UI** – Clean, responsive design with helpful visual feedback like spinners and error handling.
- 🔐 **API Integration** – Utilizes TMDb for rich movie data including posters, descriptions, and popularity metrics.

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS
- **Backend-as-a-Service**: Appwrite (for trending data, analytics, etc.)
- **APIs**: The Movie Database (TMDb)
- **Optimizations**: `use-debounce` from [`react-use`](https://github.com/streamich/react-use) to prevent excessive API requests during search input and many more..

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/movieverse.git
cd movieverse

# Install dependencies
npm install

# Run development server
npm run dev
