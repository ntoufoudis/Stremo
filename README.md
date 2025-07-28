# 🎧 Stremo

**Stremo** is an open-source, self-hosted multimedia streaming platform. It supports music, podcasts, videos, movies, web radio, and photo galleries—all on your own server.

[//]: # (![Logo]&#40;docs/logo-light.png&#41;)

## 🚀 Features

- 🎵 Personal audio streaming (Koel-style)
- 🎙️ Podcast manager with RSS feed support
- 🎬 Video/movie library with subtitles
- 📻 Web radio stream support
- 🖼️ Photo gallery with albums
- 🧠 Metadata editing and cover art
- 🔒 Fully self-hosted and open-source

## 📦 Tech Stack

| Part        | Tech                         |
|-------------|------------------------------|
| Backend     | Laravel API                  |
| Frontend    | Nuxt 3                       |
| Styling     | Tailwind CSS v4              |

## 🛠️ Getting Started

### Requirements

- PHP 8.3+
- Composer
- Node.js 20+
- MySQL or PostgreSQL
- Redis (for queue/cache)
- FFmpeg (media processing)

### Clone the repo

```
git clone https://github.com/yourusername/stremo.git
cd stremo
```

#### Backend (Laravel)

```
cd backend
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate
php artisan serve
```

#### Frontend (Nuxt)
```
cd ../frontend
npm instapp
npm run dev
```

## 🧑‍💻 Contributing
We welcome contributors! Please read [CONTRIBUTING.md](/CONTRIBUTING.md) to get started.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE.md](/LICENSE.md) file for details.

## 💬 Community & Support
* [Discussions](https://github.com/ntoufoudis/Stremo/discussions)
* [Issues](https://github.com/ntoufoudis/Stremo/issues)
