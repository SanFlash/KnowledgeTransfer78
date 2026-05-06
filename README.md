# 🚀 KT78 – For Project Understanding

A lightweight **web-based dashboard** to organize and view multiple HTML files in one place.
It acts as a **central hub** where users can quickly navigate between different project modules without opening files manually.

---

## 📌 Features

* 📂 Centralized view of multiple HTML files
* 🧭 Sidebar navigation for easy access
* ⚡ Instant loading using iframe (no page reload)
* 🧩 Simple and extensible structure
* 🎯 Beginner-friendly and easy to customize

---

## 🖼️ Preview

> Sidebar → Click → Page loads instantly in viewer

---

## 📁 Project Structure

```
KT78/
│
├── index.html        # Main dashboard UI
├── style.css         # Styling
├── script.js         # Logic for loading pages
│
├── pages/            # All project HTML files
│   ├── page1.html
│   ├── page2.html
│   ├── page3.html
```

---

## ⚙️ How It Works

* The sidebar contains a list of HTML files
* Clicking an item loads the file into an **iframe viewer**
* Everything runs on a single page → smooth navigation

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/KT78.git
```

### 2. Navigate to project

```bash
cd KT78
```

### 3. Open in browser

Just open:

```bash
index.html
```

---

## 🧩 Adding New Pages

1. Add your HTML file inside `/pages`
2. Update sidebar in `index.html`

Example:

```html
<li onclick="loadPage('pages/newpage.html')">📄 New Page</li>
```

---

## 🔥 Future Enhancements

* 🔍 Search functionality
* 📌 Bookmark favorite pages
* 🌙 Dark mode
* 📊 Dynamic page loading (JSON/API)
* 🔐 Authentication system

---

## 🧠 Use Cases

* Project documentation hub
* QA test scenario viewer
* Learning modules dashboard
* Internal knowledge base

---

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## ✨ Author

Developed as a simple and effective **project understanding tool**.

---
