# ⚡ SkillSpark – Learn. Build. Launch.

> Pakistan's fastest-growing tech education platform for university students.

---

## 📌 Project Description

SkillSpark is a fully responsive promotional website for an online tech education startup. The platform helps university students learn real-world skills in Web Development, App Development, UI/UX Design, and AI & Data Science — through project-based, hands-on courses.

This project was built as **Assignment 01 – Web Technologies (CLO-01)** using HTML5, CSS3, and Bootstrap 5.

---

## 🗂️ Project Structure

```
skillspark/
│
├── index.html          → Home Page
├── courses.html        → Courses Page
├── about.html          → About Us Page
├── register.html       → Registration Page
├── contact.html        → Contact Page
│
├── css/
│   └── style.css       → Custom styles & theme
│
├── assets/
│   └── images/         
│
└── README.md
```

---

## ✨ Features

### 🏠 Home Page (`index.html`)
- Responsive sticky navbar with dropdown menu
- Hero section with animated code block and floating cards
- 3 feature cards with hover animations
- "Why Choose Us?" section with grid layout
- Testimonials carousel (Bootstrap 5)
- Email newsletter subscription
- Gradient CTA banner
- Footer with social links

### 📚 Courses Page (`courses.html`)
- 6 course cards with category filter
- Price badges (paid + free)
- Hover animations (translateY + shadow)
- Modal popup with full course details on click
- Enroll Now buttons

### 👥 About Us Page (`about.html`)
- Company mission & founding story
- Statistics grid (5,200+ students, 89% placement)
- Animated progress bars (scroll-triggered)
- 4-person team grid with social links
- Timeline / milestones section

### 📝 Register Page (`register.html`)
- 2-column responsive layout
- Name, email, phone, university fields
- Course selection dropdown
- Learning goal radio buttons (custom UI)
- Experience level radio buttons
- Checkboxes for optional features
- File upload (CV/Portfolio)
- Live validation (`is-valid` / `is-invalid`)
- Success alert on submit

### 📞 Contact Page (`contact.html`)
- Full contact form with validation
- Google Maps iframe
- Contact info cards (address, phone, email, hours)
- Priority level radio buttons
- "How did you hear?" checkboxes
- Character counter for message
- FAQ accordion section
- Success alert on submit

---

## 🎨 Design System

| Variable | Value |
|----------|-------|
| Primary | `#7C3AED` (Purple) |
| Secondary | `#06B6D4` (Cyan) |
| Accent | `#F59E0B` (Amber) |
| Dark BG | `#0F0A1E` |
| Card BG | `#1E1540` |

- **Fonts:** Syne (headings) + DM Sans (body) via Google Fonts
- **Gradient:** `linear-gradient(135deg, #7C3AED 0%, #06B6D4 100%)`
- **Border radius:** 16px (cards), 50px (buttons/pills)
- **Transitions:** `cubic-bezier(0.4, 0, 0.2, 1)` — 0.3s

---

## 🌟 Bonus Features

- [x] 🌙 **Dark/Light mode toggle** (persisted in localStorage)
- [x] ⬆️ **Scroll to top button** (appears after 300px scroll)
- [x] 🎞️ **Custom scroll animations** (IntersectionObserver)
- [x] 💫 **Floating hero cards** (CSS keyframe animations)
- [x] 📊 **Progress bars** (animated on scroll)
- [x] 🗃️ **FAQ accordion** on Contact page

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, flexbox, grid, keyframes
- **Bootstrap 5.3.3** — Grid, navbar, carousel, modal, accordion
- **Font Awesome 6.5** — Icons
- **Google Fonts** — Syne + DM Sans
- **Vanilla JavaScript** — Validation, animations, dark mode

---

## 📸 Screenshots

> Add screenshots to `assets/images/` folder and link here:

| Page | Preview |
|------|---------|
| Home | `assets/images/screenshot-home.png` |
| Courses | `assets/images/screenshot-courses.png` |
| About | `assets/images/screenshot-about.png` |
| Register | `assets/images/screenshot-register.png` |
| Contact | `assets/images/screenshot-contact.png` |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/skillspark.git
   ```

2. Open `index.html` in your browser — no server required!

3. Or deploy to GitHub Pages:
   - Go to repo Settings → Pages
   - Select `main` branch, root folder
   - Your site will be live at `https://yourusername.github.io/skillspark`

---

## 📝 Git Commit History

Meaningful commits in this project:

1. `Initial project setup — folder structure & base HTML`
2. `Added navbar with dropdown and responsive toggle`
3. `Implemented hero section with animated code block`
4. `Added feature cards with hover animations`
5. `Implemented Why Choose Us section`
6. `Added testimonials carousel`
7. `Implemented course cards with price badges`
8. `Added modal popup for course details`
9. `Built About Us page with team grid`
10. `Added progress bars and timeline milestones`
11. `Implemented registration form with validation`
12. `Added contact form with Google Map iframe`
13. `Added dark mode toggle and scroll-to-top`
14. `Fixed responsiveness for mobile and tablet`
15. `Final CSS polish and README update`

---

## 👨‍💻 Author

**Your Name** — Web Technologies Assignment 01  
University: Your University Name  
Course: Web Technologies  
Submitted: March 2026

---

## 📄 License

This project is submitted as academic coursework for SkillSpark — Learn. Build. Launch.
