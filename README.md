# 🚀 Frontend API Hub

A curated collection of real-world APIs for Front-End developers to build powerful and dynamic applications.

---

## 📌 Project Goal

This project is designed to help Front-End developers move from:

> Static UI ❌ → Real Applications ✅

---

## 📚 Table of Contents

- 📖 Quran API
- 🌦️ Weather API
- 🛒 E-commerce API
- 🔐 Authentication API
- 🤖 AI API
- 💬 Chat API

---

# 📖 Quran API

## 🔥 API: AlQuran Cloud

### 📌 Description

An API to fetch Quran surahs and verses with detailed metadata such as verse number and text.

### 🔗 Docs

https://alquran.cloud/api

### ⚙️ Features

- Fetch full surahs  
- Retrieve verses  
- Multiple editions and translations  

### 💻 Example

```js
fetch('https://api.alquran.cloud/v1/surah/2')
  .then(res => res.json())
  .then(data => console.log(data));
```
