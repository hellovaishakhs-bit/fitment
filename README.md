# FitMent — Your Fitness. Your Trainer. One App.

FitMent is a premium, modern landing page for a fitness connection platform that links fitness enthusiasts with expert trainers and associations in India (currently live in Bengaluru & Kochi).

It provides an end-to-end showcase of features designed for three core audiences: **Users**, **Trainers**, and **Associations**.

---

## 🌟 Key Features

- **For Users**: Easily search for and book verified local trainers who match your goals, schedule, and budget.
- **For Trainers**: Grow your practice, manage calendar scheduling, track sessions/attendance, and retain 87% of session fees.
- **For Associations**: Coordinate trainers, manage community programs, and handle member engagement from a unified dashboard.
- **App Preview**: A realistic interactive mock preview showing in-app session booking (e.g. Badminton, Yoga).
- **Interactive Contact Form**: A premium clean form for leads, partnership requests, and trainer onboarding.

---

## 🛠️ Tech Stack & Design Aesthetics

- **HTML5**: Structured semantic markup.
- **Vanilla CSS3**: 
  - Responsive layout built using CSS Grid and Flexbox.
  - Premium design system (custom variables, HSL-tailored accents, custom dark/light sections).
  - Modern glassmorphism overlays and sticky/blur navigation.
  - Skewed line indicators and custom SVGs.
- **Typography**: Google Fonts - Archivo (highly readable, geometric sans-serif).
- **Animations**: Inbound scroll transitions via custom `IntersectionObserver` reveal animations.
- **Images**: Beautiful, high-resolution photography curated from Unsplash.

---

## 🚀 How to Run Locally

Since this is built with pure, lightweight vanilla HTML and CSS, you can run it instantly without any local compilation step:

1. Simply double-click **`index.html`** to open it in your browser.
2. Alternatively, run a lightweight static server from this directory:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (npx)
   npx serve .
   ```
3. Open `http://localhost:8000` (or the port specified) in your browser.

---

## 📦 Deployment

To host this website on GitHub Pages:
1. Push this repository to GitHub.
2. Go to your repository settings page on GitHub.
3. Under the **Pages** tab, select the `main` branch and `/root` directory, then click **Save**.
