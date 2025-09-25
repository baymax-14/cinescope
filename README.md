Perfect 👌 — having a polished **README.md** will make your GitHub repo look professional and help recruiters or collaborators try out CineScope easily.

Here’s a ready-to-use **README.md** for your CineScope project 🚀

````markdown
# 🎬 CineScope

CineScope is a **movie & TV discovery web app** built with **AngularJS** and the **TMDB API**.  
It lets you search, filter, and explore movies/TV shows, view detailed info, and maintain your personal watchlist — all in a sleek Netflix-style UI.

---

## ✨ Features

- 🔍 **Search** for movies and TV shows in real-time.
- 🎭 **Filters** for type, genre, year, rating, and sorting.
- 📊 **Trending & Popular** sections.
- 📌 **Watchlist** (add/remove movies & shows).
- 🎥 **Details Page** with:
  - Poster + title + year
  - Tagline & overview
  - Genres & ratings
  - Add to Watchlist button
  - Recommendations ("You may also like...")
- 🌙 **Modern UI/UX** with smooth animations, hover effects, and styled badges.

---

## 🛠️ Tech Stack

- **Frontend:** AngularJS (1.8), HTML5, CSS3, Bootstrap
- **API:** [The Movie Database (TMDB)](https://www.themoviedb.org/documentation/api)
- **Icons:** Font Awesome

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/YOUR-USERNAME/cinescope.git
cd cinescope
````

### 2. Install dependencies

Since this is a frontend-only AngularJS app, you don’t need a build step.
Just ensure you have **npm http-server** or any static server installed.

```bash
npm install -g http-server
```

### 3. Run the project

Start the server:

```bash
http-server
```

By default it will run at:
👉 `http://127.0.0.1:8080`

---

## 🔑 API Key Setup

1. Go to [TMDB](https://www.themoviedb.org/settings/api) and create a free account.
2. Get your **API key**.
3. Open `app.js` (or your Angular config) and replace:

```js
app.constant('API_KEY', 'YOUR_TMDB_API_KEY');
```

with your actual key.

---

## 📸 Screenshots

### Home / Search + Filters

![Search Page](screenshots/search.png)

### Movie Details

![Details Page](screenshots/details.png)

### Watchlist

![Watchlist](screenshots/watchlist.png)

---

## 📂 Project Structure

```
cinescope/
│── index.html
│── app.js
│── controllers/
│    ├── searchController.js
│    ├── detailsController.js
│    ├── watchlistController.js
│    └── trendingController.js
│── services/
│    └── tmdbService.js
│── views/
│    ├── search.html
│    ├── details.html
│    ├── watchlist.html
│    └── trending.html
│── assets/
│    ├── css/style.css
│    ├── js/
│    └── images/
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a PR.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

* [TMDB API](https://www.themoviedb.org/documentation/api)
* [AngularJS](https://angularjs.org/)
* [Bootstrap](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/)

```

---

👉 You can just copy this into a `README.md` file and place it in your project root.  
I also added placeholders for **screenshots** — you can take 2–3 key screenshots (like you already shared here), save them in a `screenshots/` folder inside your repo, and update the file paths.  

Do you want me to also **make a `.gitignore` and LICENSE file** so your repo looks even more professional?
```
