# 🎓 MACET Patna — Student Feedback Portal

A clean and modern student feedback portal for **Maulana Azad College of Engineering & Technology, Patna**. Students can submit their feedback which is delivered directly to the college Gmail via EmailJS — no backend required.

<img width="100%" height="100%" alt="macet-building" src="https://github.com/user-attachments/assets/e736bea6-196d-4445-a8f4-2dd54ba66035" />


---

## ✨ Features

- 📱 Fully responsive — mobile & desktop
- ✅ Real-time form validation
- ⭐ Interactive 1–5 rating system
- 📧 Email delivery via EmailJS (no backend)
- 🎨 Dark glassmorphism UI with gold accents

---

## 🛠️ Tech Used

- HTML5, CSS3, Vanilla JavaScript
- [EmailJS](https://www.emailjs.com/) — for sending emails client-side
- Google Fonts — Playfair Display + DM Sans

---

## ⚙️ EmailJS Setup

1. Create account at [emailjs.com](https://www.emailjs.com/)
2. Add a Gmail service
3. Create a template using these variables:
   `{{student_name}}`, `{{roll_number}}`, `{{mobile}}`, `{{branch}}`, `{{college}}`, `{{year}}`, `{{rating}}`, `{{feedback}}`, `{{submitted_at}}`
4. Update credentials in `index.html`:

```js
const EMAILJS_PUBLIC_KEY  = "your_public_key";
const EMAILJS_SERVICE_ID  = "your_service_id";
const EMAILJS_TEMPLATE_ID = "your_template_id";
```

---

## 🚀 Usage

Just open `index.html` in any browser. No build step needed.

---

## 👨‍💻 Developer

Built by **MD KAMRAN**  · @MACET Patna · 2026
