# 🚀 Front-end API Hub

## 📌 Project Goal

This project is designed to help Front-End developers move from:

**Static UI ❌ → Real Applications ✅**

Instead of building only UI screens, this repo helps developers practice using real APIs to build dynamic, production-like applications.

---

## 📚 Table of Contents

- 🕌 Prayer Times API  
- 📖 Quran API (Text)  
- 🎧 Quran Audio API  
- 🌦️ Weather API  
- 🛒 DummyJSON Ecommerce API  
- 🌍 REST Countries API  
- 🧪 JSONPlaceholder API  

---

# 📡 APIs Overview

---

## 🕌 Prayer Times API

### Description
Provides daily prayer times based on city, country, or coordinates.

### Base URL
```js
https://api.aladhan.com/v1
```

### Example Request
```js
https://api.aladhan.com/v1/timingsByCity?city=Cairo&country=Egypt
```

### Simple Fetch
```js
fetch("https://api.aladhan.com/v1/timingsByCity?city=Cairo&country=Egypt")
  .then(res => res.json())
  .then(data => console.log(data.data.timings));
```
<br />

## 📖 Quran API (Text)

### Description
Returns Quran surahs, verses, translations, and metadata.

### Base URL
```js
https://api.alquran.cloud/v1/surah/{surahNumber}
```

### Example Request
```js
https://api.alquran.cloud/v1/surah/1
```

### Simple Fetch
```js
fetch("https://api.alquran.cloud/v1/surah/1")
  .then(res => res.json())
  .then(data => console.log(data.data.ayahs));
```
<br />

## 🎧 Quran API (Audio)
### Description

Provides recitations of the Quran by different reciters.

### Base URL
https://download.quranicaudio.com/qdc/abdul_baset/mujawwad/{surahNumber}.mp3

### Example Usage
```js
https://download.quranicaudio.com/qdc/abdul_baset/mujawwad/1.mp3
```

### HTML Example
```js
<audio controls>
  <source src="https://download.quranicaudio.com/qdc/abdul_baset/mujawwad/1.mp3" type="audio/mpeg" />
</audio>
```
<br />

## 🌦️ Weather API
### Description

Provides real-time weather data including temperature, humidity, and forecast.

### Base URL
```js
https://api.openweathermap.org/data/2.5/weather
```

### Example Request
```js
https://api.openweathermap.org/data/2.5/weather?q=Cairo&appid=YOUR_API_KEY
```

### Simple Fetch
```js
fetch("https://api.openweathermap.org/data/2.5/weather?q=Cairo&appid=YOUR_API_KEY")
  .then(res => res.json())
  .then(data => console.log(data));
```
<br />

## 🛒 DummyJSON Ecommerce API
### Description

Fake ecommerce API for products, carts, users, and authentication.

### Base URL
```js
https://dummyjson.com/products
```

### Example Request
```js
https://dummyjson.com/products
```

### Simple Fetch
```js
fetch("https://dummyjson.com/products")
  .then(res => res.json())
  .then(data => console.log(data.products));
```
<br />

## 🌍 REST Countries API
### Description

Provides information about countries including population, flags, languages, and currencies.

### Base URL
```js
https://restcountries.com/v3.1
```

### Example Request
```js
https://restcountries.com/v3.1/name/egypt
```

### Simple Fetch
```js
fetch("https://restcountries.com/v3.1/name/egypt")
  .then(res => res.json())
  .then(data => console.log(data[0]));
```
<br />

## 🧪 JSONPlaceholder API
### Description

Fake REST API for testing and prototyping.

### Base URL
```js
https://jsonplaceholder.typicode.com
```

### Example Request
```js
https://jsonplaceholder.typicode.com/posts
```

### Simple Fetch
```js
fetch("https://jsonplaceholder.typicode.com/posts")
  .then(res => res.json())
  .then(data => console.log(data));
```

---

## 🚀 How to Use This Repo

1. Clone the repository
2. Pick any API from the list
3. Try building a small project using it
4. Combine multiple APIs for advanced projects

---

## 💡 Project Ideas

- 🕌 Prayer App (Prayer Times API)
- 🌦️ Weather Dashboard (Weather API)
- 🛒 Ecommerce Store (DummyJSON)
- 🌍 Country Explorer (REST Countries API)
- 📖 Quran Reader App (Quran APIs)

---

## 👨‍💻 Author

**Ahmed Talaat**  
Front-End Developer (React | Next.js | JavaScript | TypeScript)

- GitHub: https://github.com/ahmedtalaat-dev
- LinkedIn: www.linkedin.com/in/ahmedtalaat-dev 
- Portfolio: https://at-portfolio-35.vercel.app/
