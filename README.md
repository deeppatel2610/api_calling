
# 📡 API Calling in Flutter using Provider

This Flutter project demonstrates how to fetch and display data from an API using the **Provider** state management approach. It is a beginner-friendly project that focuses on best practices for separating concerns, managing state, and presenting dynamic data.

---

## ✨ Features

- 📦 State management using `provider`
- 🔄 API data loading with loading indicators
- 🧮 Brand-wise filtering using dropdown
- 🔍 Live product search functionality
- 💡 Clean and modern UI
- 🖼 Thumbnail preview for each product

---

## 📸 Screenshots
<img src= "https://github.com/user-attachments/assets/8aeed373-d34c-4804-84d8-87a64abdf800"  height =500px>
<img src= "https://github.com/user-attachments/assets/8730ca59-685a-49e0-89b1-3341c3fda2a8"  height =500px>


https://github.com/user-attachments/assets/88dff67f-4621-4ec3-b57c-ffeea6fdd07d



## 🛠️ Getting Started

### Prerequisites

- ✅ Flutter SDK
- ✅ Android Studio / VS Code
- ✅ Internet connection (for API calls)

### Installation

```bash
git clone https://github.com/deeppatel2610/api_calling.git
cd api_calling
flutter pub get
flutter run
````

---

## 📁 Project Structure

```bash
lib/
├── main.dart
├── provider/
│   └── product_provider.dart
├── screens/
│   ├── home_page.dart
│   └── search_page.dart
└── model/
    └── product_model.dart
```

---

## 🔗 API Used

This app fetches product data from a public API like:

```
https://dummyjson.com/products
```

> You can update this to your actual API endpoint in `ProductProvider`.

---

## 📦 Packages Used

| Package               | Description      |
| --------------------- | ---------------- |
| provider              | State management |
| http                  | For API requests |
| flutter/material.dart | UI toolkit       |

---

## 📌 Todo

* [ ] Add product detail screen
* [ ] Add cart functionality
* [ ] Pull to refresh
* [ ] Error handling UI

---

## 🙌 Author

**Deep Patel**
🔗 [@deeppatel2610 on GitHub](https://github.com/deeppatel2610)

---
