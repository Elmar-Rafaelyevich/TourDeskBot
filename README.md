# 🌍 Salaam Travel Bot

A Telegram bot for a travel agency that helps users submit travel requests, view travel packages, and access essential travel information.

The bot allows users to interact via a structured menu, submit their personal information, and receive media files or location data. Admins can manage content, update prices, and monitor submissions.

⚠️ Intended for educational, research, and operational purposes only.

## 🧠 Architecture
- **Telegram Bot (pyTelegramBotAPI)** — handles user interactions and menu navigation
- **File Storage** — stores uploaded images, documents, and package details
- **Admin Functions** — allows updating travel packages, prices, and schedule files

## 🚀 Features
- Interactive menu with travel options, pricing, hotels, videos, location, and contact
- Upload and manage travel package media (images, videos)
- Submit personal information for bookings (name, phone)
- Admin panel for updating prices, uploading images, and managing namoz schedules
- Automatically sends requested files to users

## 📄 Data Storage
- Directories for different packages and media:
  - `documents/` — flight info
  - `luks_paket/`, `standart_paket/`, `ekanom_paket/` — package prices
  - `hotel/` — hotel videos
  - `namoz/` — namoz schedules
- User submissions (name, phone) sent to admin Telegram channel

## ⚠️ Important Notes
- Phone numbers are collected with user consent
- Use responsibly and comply with privacy regulations

## 🛠 Technologies
- Python 3.9+
- pyTelegramBotAPI (telebot)
- Inline keyboards for menu navigation
- File handling for images, videos, PDFs
