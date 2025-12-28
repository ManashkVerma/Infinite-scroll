# 📸 Infinite Scroll Image Gallery (Vanilla JavaScript)

This project implements a **production-style infinite scroll image gallery** using **pure JavaScript** and the **Unsplash API**, without relying on frameworks or libraries.

The goal was to understand **how real-world applications handle infinite scrolling, image loading, and API batching under the hood**.

---

## 🚀 Features

* Infinite scrolling based on user scroll position
* Dynamic image loading from the **Unsplash API**
* Image load tracking to prevent race conditions
* Controlled API fetching to avoid over-fetching
* Smooth user experience with a loading indicator
* Built entirely with **vanilla JavaScript**

---

## 🧠 Key Concepts Implemented

* **Async/Await** for API calls
* **Scroll position detection** for pagination
* **Image load event tracking** to ensure all images load before fetching more
* **State management** using flags (`ready`, `imagesLoaded`, `totalImages`)
* Dynamic DOM manipulation using `createElement` and `setAttribute`

---

## 🛠 Tech Stack

* JavaScript (ES6+)
* Unsplash REST API
* HTML5
* CSS3

---

## 📂 Project Structure

```
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ⚙️ How It Works

1. Fetches a batch of images from the Unsplash API
2. Dynamically creates `<img>` and `<a>` elements
3. Tracks when **all images finish loading**
4. Enables fetching the next batch only after loading completes
5. Detects when the user scrolls near the bottom of the page
6. Repeats the process for infinite scrolling

---

## 🔑 Unsplash API Setup

1. Create an account at [https://unsplash.com/developers](https://unsplash.com/developers)
2. Generate an API key
3. Replace the API key in the code:

```js
const apiKey = "YOUR_API_KEY";
```

---

## ▶️ How to Run Locally

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Open `index.html` in your browser
   (No build step required)

---

## 📈 Why This Project Matters

This project mirrors **real frontend engineering patterns** used in applications like:

* Instagram
* Pinterest
* Image-heavy dashboards

It focuses on:

* performance
* correct async handling
* scalable UI logic

---

## 🤝 Contribution & Opportunities

I’m **actively looking for opportunities to contribute**, collaborate, and grow as a frontend / JavaScript developer.
Open to internships, junior roles, and open-source contributions.

If you have feedback or ideas for improvement, feel free to reach out or open an issue.

---

## 📌 Future Improvements

* Intersection Observer for scroll detection
* Lazy loading images
* Error handling UI
* Responsive performance optimizations
* React / Next.js version

---
