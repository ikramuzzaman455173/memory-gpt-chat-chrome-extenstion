![MemoryGpt Chat Chrome extenstion](https://github.com/user-attachments/assets/ab8544c1-d5bf-4a1d-9820-c75780a44d19)

# 🧠 Memory GPT Chat – Chrome Extension

> Save, search, organize, and manage your ChatGPT conversations with ease.
> A lightweight, professional Chrome extension for bookmarking and managing ChatGPT chats.

---

## 📑 Table of Contents
- [✨ Features](#-features)
- [📦 Installation](#-installation)
  - [Chrome Setup](#chrome-setup)
  - [Android Setup](#android-setup)
- [🚀 Usage](#-usage)
- [🔐 Privacy & Permissions](#-privacy--permissions)
- [⚡ Storage Details](#-storage-details)
- [🛠 Development](#-development)
- [🧪 Testing](#-testing)
- [🎥 Video Overview](#-video-overview)
  - [Chrome Setup Video](#chrome-setup-video)
  - [Android Setup Video](#android-setup-video)
- [❓ Troubleshooting](#-troubleshooting)
- [📜 Changelog](#-changelog)
- [📄 License](#-license)

---

## ✨ Features
- **Save any ChatGPT conversation** (`https://chatgpt.com/c/...`).
- **Prevent duplicates**: already-saved chats are highlighted.
- **Search, Sort, Pagination**:
  - Instant search (title/note).
  - Sort by *Newest* or *Title A–Z*.
  - Page sizes: 5, 10, 20, 50, 100.
- **Actions per chat**:
  - Copy link 📋
  - Open in new tab 🔗
  - Edit title/note ✏️
  - Delete 🗑️
- **Clear All chats**:
  - Type `yes clear all` to confirm.
  - Auto-downloads backup `.json`.
- **Import / Export**:
  - Export all chats to `.json`.
  - Import chats (duplicate-safe).
- **Storage Meter**:
  - Shows count + bytes used out of 10 MB.
  - Progress bar (yellow ≥70%, red ≥90%).
- **Dark / Light mode** 🌙
- **First-time Info popup** with "Don’t show again".
- **Responsive UI** (desktop & mobile-friendly).

---

## 📦 Installation

### Chrome Setup
1. Clone this repo or [Download ZIP](https://github.com/ikramuzzaman455173/memory-gpt-chat-chrome-extenstion/raw/main/memory-gpt-chat-chrome-extenstion.zip).
2. Open **Chrome** → `chrome://extensions/`.
3. Enable **Developer mode** (top-right).
4. Click **Load unpacked** → select the project folder.
5. Pin 📌 the extension from the toolbar.

### Android Setup
Chrome mobile doesn’t support extensions. Use:
- [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser)
- [Yandex Browser](https://play.google.com/store/apps/details?id=com.yandex.browser)

Steps:
1. Install Kiwi/Yandex.
2. Open Extensions → Enable **Developer mode**.
3. **Load Unpacked** → choose project folder.
4. Extension works the same as desktop.

---

## 🚀 Usage
1. Open a ChatGPT conversation (`/c/...`).
2. Click **Memory GPT Chat** toolbar icon.
3. Press **Save** → chat is added.
4. Use **Search**, **Sort**, **Pagination** to manage.
5. Export, Import, or Clear All as needed.

---

---

## 🔐 Privacy & Permissions
- **Permissions used**:
  - `storage` → store saved chats (`chrome.storage.local`, ~10 MB).
  - `tabs` → detect current tab URL/title.
  - `downloads` → auto-export backups.
  - `host_permissions` → access `chatgpt.com/*` and `chat.openai.com/*`.
- **Privacy**:
  - Data stored **locally in your browser**.
  - No external servers.
  - Full control: Export or Delete anytime.

---

## ⚡ Storage Details
- Uses **`chrome.storage.local`** → ~10 MB.
- Progress bar:
  - Gray = low usage
  - Yellow ≥70%
  - Red ≥90%
- Duplicates prevented.

---

## 🛠 Development
1. Clone this repo.
2. Open Chrome → `chrome://extensions/`.
3. Enable **Developer mode** → Load unpacked.
4. Edit code → Reload → Test.
5. Debug logs in popup’s DevTools (right-click popup → Inspect).

---

## 🧪 Testing
Sample JSON test files:
- [demo_chats.json](sandbox:/mnt/data/demo_chats.json) (50 chats)
- [demo_chats_5000.json](sandbox:/mnt/data/demo_chats_5000.json) (5000 chats)

Import via **Import** button.

---

## 🎥 Video Overview

### Chrome Setup Video
👉 [Watch Chrome setup overview](https://example.com/chrome-setup-video) *(replace with your YouTube/GDrive link)*

### Android Setup Video
👉 [Watch Android setup overview](https://example.com/android-setup-video) *(replace with your YouTube/GDrive link)*

---

## ❓ Troubleshooting
- **Save not working** → must be on `chatgpt.com/c/...`.
- **Storage full** → Export then Clear All.
- **Progress bar empty** → with few chats (<400) usage is <1%.
- **Android** → use Kiwi/Yandex, not Chrome.

---

## 📜 Changelog
**v4.0.0** (current):
- Migrated to `chrome.storage.local` (10 MB).
- Storage meter added.
- Clear All with backup confirm.
- Import/export with duplicate prevention.
- Responsive UI + Dark Mode.

---

## 📄 License
MIT License © 2025 [Md.Ikramuzzaman]

