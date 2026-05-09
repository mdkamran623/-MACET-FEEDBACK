# 🎓 MACET Patna — Student Feedback Portal

A clean and modern student feedback portal for **Maulana Azad College of Engineering & Technology, Patna**. Students can submit their feedback which is delivered directly to the college Gmail via EmailJS — no backend required.

https://scontent.fpat11-3.fna.fbcdn.net/v/t39.30808-6/476165148_1065662765574942_4570227068706752640_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=13d280&_nc_ohc=LAGbpGM5UM8Q7kNvwGCzoEp&_nc_oc=AdqGii5jQqqlICdCJT_IoM2iDLRjDwqaFTLkwQk0EVxI3h6COlh_VjvU5P1qJxjY1SfUMBoH7LlGMk0xuPclrfQ-&_nc_zt=23&_nc_ht=scontent.fpat11-3.fna&_nc_gid=YunZTfEMquuOcZeKnLzBjg&_nc_ss=7b289&oh=00_Af509fOqfw5rjAZdHNXwEJk6x4tJk7BeDFw4py9qfE-flQ&oe=6A053945

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
