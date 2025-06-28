# 🎬 Cinereact

A sleek, responsive movie app built with **React** and **Next.js** — designed as both a showcase of modern frontend development and a boilerplate for future streaming-style projects.

> “Because building a Netflix clone shouldn’t feel like a clone.”

---

## 🔍 Overview

**Cinereact** lets users explore movies, view details, watch trailers, and manage a watchlist — all with clean UI, performant React components, and modern development tools.

This project serves as:
- A **portfolio piece** to demonstrate full-stack skills using React and Next.js
- A **template** for future media-based apps
- A **learning tool** for developers interested in building interactive UIs with React

---

## 🚀 Features

- 🎥 **Movie Listings** — Fetches real movie data from [TMDb](https://www.themoviedb.org/)
- 🔍 **Search & Filter** — Find your favorite movies fast
- ❤️ **Watchlist** — Add and manage your personal collection
- 📱 **Fully Responsive** — Mobile-first, built with Flex/Grid and media queries
- 🌙 **Dark Mode** — Because… it’s a movie app 😉
- ⚛️ **Built with Next.js + React** — Fast routing, SSR/ISR, API integration
- 🧱 **Component-based architecture** — Easy to reuse and extend
- 🌐 **Deploy-ready** — Works great on Vercel or any Node host

---

## 🛠️ Tech Stack

| Frontend        | Styling           | Data/API       | Tooling           |
|-----------------|-------------------|----------------|-------------------|
| React (via Next.js) | Tailwind CSS (or Styled Components) | TMDb API (or mock JSON) | ESLint, Prettier |
| Next.js Routing | Dark mode support | React Query / SWR | Husky + Git hooks |
| Custom Hooks    | Modular components | Axios / Fetch  | Vercel CLI ready  |

---

## 📦 Installation

```bash
git clone https://github.com/your-username/cinereact.git
cd cinereact
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

---

## ⚙️ Environment Variables

Create a `.env.local` file in the root:

```env
NEXT_PUBLIC_TMDB_API_KEY=your_api_key_here
```

You can get a free API key at [TMDb Developer Portal](https://developer.themoviedb.org/).

---

## 📸 Screenshots

*(Add screenshots or a short demo GIF here)*  
Example:  
![Cinereact Screenshot](./public/demo.png)

---

## 🧱 Project Structure

```
/components      → Reusable UI components (MovieCard, Header, etc.)
/pages           → Next.js pages
/styles          → Global styles or Tailwind config
/utils           → Helper functions
/hooks           → Custom React hooks
```

---

## 📚 What I Learned

- Deepened knowledge of **Next.js routing, SSR/ISR**
- Improved use of **React hooks** and component organization
- Hands-on experience with **responsive UI & user interaction**
- API integration and **environment-based configuration**

---

## 📈 Future Plans

- ✅ Add login & user profiles
- 🎞️ Trailer modal with embedded YouTube players
- 💬 User reviews and comments (mock or Firebase)
- 🌍 Multi-language support (i18n)
- 📦 Turn it into an npm package starter (`cinereact-template`)

---

## 🧑‍💻 About the Creator

Hi, I’m **Ermin Muratovic**, a software engineer and freelancer passionate about clean design and real-world applications.  
This app is part of my developer portfolio. Want to work together?

👉 [Portfolio Website](https://muratovic.at)  
👉 [LinkedIn](https://www.linkedin.com/in/ermin-muratovic)  
👉 [Email](mailto:ermin@muratovic.at)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
