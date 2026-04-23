# 🚦 Yo'lnoma — Yo'l Harakati Qoidalari

**Yo'lnoma** is an Android quiz application designed to help drivers and learners master Uzbekistan's **road traffic rules**. The app features categorized tests, real-time progress tracking, and detailed result breakdowns — all built with a clean, modern UI.

📲 **[Download Latest APK](#)** *(https://github.com/uzbedeveloper/yolnoma-resume/releases/download/first/app-debug.apk)*

---

### 📸 Screenshots

| | | | |
|---|---|---|---|
| ![Home](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/1.jpg) | ![Quiz](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/2.jpg) | ![Question](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/3.jpg) | ![Answer](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/4.jpg) |
| ![Result](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/5.jpg) | ![Correct](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/6.jpg) | ![Summary](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/7.jpg) | ![Categories](https://raw.githubusercontent.com/uzbedeveloper/yolnoma-resume/main/images_yolnoma/8.jpg) |
---

### 🔍 About

Yo'lnoma bundles **70 test questions** across 7+ topic categories covering everything from intersection rules and road signs to emergency situations and vehicle physics. Each category tracks your best score independently, so you always know exactly where to improve.

**Key Features:**

* **Categorized Tests** — Topics include intersections, speed & maneuvers, warnings, special cases, braking, and more.
* **Progress Tracking** — Each category shows live score (`X tadan Y tasi to'g'ri`) with a circular progress indicator.
* **Image-Based Questions** — Many questions feature real traffic scenario illustrations for visual learning.
* **Detailed Result Screen** — After each test, see every question with your answer vs. the correct answer in a clear red/green breakdown.
* **"Qiziqarli Mashqlar" Section** — Highlighted exercise packs for focused practice on common weak points.
* **Offline Ready** — All questions bundled locally; no internet required to take tests.

---

### 🛠️ Tech Stack

* **Kotlin** — Primary language for all app logic
* **Jetpack Compose / XML Layouts** — Modern declarative UI with custom components
* **ViewModel + StateFlow** — Lifecycle-aware state management for quiz session and score persistence
* **RecyclerView + Adapters** — Efficient rendering of question lists and category cards
* **Navigation Component** — Fragment-based navigation with back-stack management
* **Local JSON / Hardcoded Data Layer** — Lightweight question storage without requiring a backend
* **Custom CircularProgressView** — Canvas-based component for per-category score visualization
* **Material Design 3** — Theming, typography, and component guidelines throughout

---

### 🗂️ App Structure

```
Yo'lnoma
├── Home Screen         → Category cards + test list with scores
├── Quiz Screen         → Question + answer options (A/B/C/D)
│   ├── Image questions → Traffic scenario illustrations
│   └── Text questions  → Rule-based multiple choice
├── Result Screen       → Full breakdown: score, wrong vs. correct per question
└── About Dialog        → Version info + author contact
```

---

### 📊 Test Categories

| Category | Questions |
|---|---|
| Umumiy qoidalar va chorrahalar | 10 |
| Yo'l chiziqlari ishoralari | 10 |
| To'xtash, turish va piyodalar | 10 |
| Tezlik, burilish va manyovrlar | 10 |
| Ogohlantirishlar va maxsus cheklovlar | 10 |
| Maxsus holatlar va transport turlari | 10 |
| Quvib o'tish va tormozlanish | 10 |
| Texnik holat va harakat fizikasi | 9 |
| Favqulodda vaziyatlar va majburiyatlar | 10 |

---

### 💾 Installation

1. Download the `app-debug.apk` from the releases section.
2. Open the APK on your Android device.
3. Allow installation from unknown sources if prompted.
4. Launch the app and start practicing!

---

### 👤 Author

Built by **Umarkhon Murodkhonov** — Android Developer from Tashkent, Uzbekistan.

* **GitHub:** [@uzbedeveloper](https://github.com/uzbedeveloper)
