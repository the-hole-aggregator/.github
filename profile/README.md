# THE HOLE - personal content platform

## 🌌 Overview

This organization contains the repositories that power my personal content.

The platform combines a blog, Telegram channels, and automation tools into a single ecosystem where content from different sources is collected, processed, and published in one place.

The blog acts as the central hub of the platform.

The ecosystem currently consists of three main components:
* Blog application
* Blog backend service
* Telegram meme bot

---

## 📂 Repositories

### Blog Mobile/Web Application
Flutter application used to browse and read content from the platform.

Tech stack:
* Flutter
* Dart

Repository: blog-app

---

### Blog Backend
Backend service responsible for managing the platform's content and APIs.

The backend handles:
* blog posts
* content aggregation
* integration with Telegram channels
* API used by the mobile application

Tech stack:
* Go
* PostgreSQL
* REST API
* modular service architecture

Repository: blog-backend

---

### Meme Telegram Bot

Telegram bot that aggregates memes from different sources and publishes them to a Telegram channel.
Memes from the channel are also available in a dedicated section of the blog platform.

Tech stack:
* Go
* Telegram Bot API
* cron
* RSS

Repository: meme-telegram-bot
