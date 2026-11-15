# FLIXPLAY - Free Movies & TV Shows Streaming

<p align="center">
  <img src="https://your-image-link-here.png" alt="Flixplay Banner" width="800">
</p>

🚀 **FLIXPLAY** is an open-source, free movies and TV shows streaming platform built with modern web technologies. It offers a seamless and enjoyable viewing experience, allowing users to discover, search, and enjoy a vast library of content directly from their browser or mobile app.

## 📜 Key Features

* 🆓 **Free and Open-Source:** FLIXPLAY is completely free to use. The source code is available for anyone to explore, contribute, and build upon.
* 🎬 **Discover Content:** Users can browse through various content categories, such as trending movies, popular TV shows, and dedicated Anime collections.
* 🔍 **Powerful Search:** The search functionality utilizes the TMDB API to easily find specific titles, genres, and new releases.
* 🔐 **Secure Authentication:** Integrated with Firebase to allow users to create accounts and log in seamlessly across both the web and mobile apps.
* 🛠️ **Custom Admin Panel:** A fully functional studio dashboard to manage the catalog, auto-import titles from TMDB, and configure streaming servers on the fly.
* 📺 **Multi-Server Support:** Automatically falls back between multiple streaming servers (Vidrift, VidBolt, FilmU, 2Embed, VidSrc, etc.) to ensure high availability.
* 📱 **Progressive Web App & Mobile App:** Designed to be installable on devices, providing a native-like experience on mobile through a custom WebView APK.

## 📝 Other Features

* 🎬 **Movies (Finished)**
* 📺 **TV Shows & Anime (Finished)**
* 👤 **User Accounts & Profiles (Finished)**
* ⚙️ **Dynamic Server Config (Finished)**
* 🏆 **Achievements System (Planned)**
* 📥 **Offline Downloads (Planned)**
* 🌐 **Social Features (Planned)**

## 💻 Technologies Used

FLIXPLAY is built using the following technologies:

* **HTML5 & Vanilla JavaScript:** The core structure and logic for a lightweight, fast-loading frontend.
* **Tailwind CSS:** The user interface is styled using the Tailwind CSS utility-first framework, ensuring a visually appealing and responsive design.
* **Firebase:** Used for Realtime Database management (storing users, catalog, and server configs) and Firebase Authentication for the Admin Panel.
* **The Movie Database (TMDB) API:** Integrated to retrieve movie and TV show data, ensuring access to a vast and up-to-date content library.
* **AniList API:** Utilized to fetch specific IDs required for Anime streaming servers.

## 🚀 Getting Started

To run FLIXPLAY locally or deploy your own version, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/flixplay.git
