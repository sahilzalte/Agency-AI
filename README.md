# 🚀 Agency-AI

A modern, responsive digital agency website showcasing services, portfolio, team, and client logos.  
Features include **dark mode toggle**, **custom cursor effects**, and **smooth animations**.

---

## 📌 High-Level Summary

| **Aspect** | **Details** |
|------------|-------------|
| **Purpose** | A modern, responsive website for a digital agency (*Agency.AI*). It highlights the agency's services, portfolio, team, and client logos, featuring a sleek **dark mode toggle** and **custom cursor effects**. |
| **Tech Stack** | • **React 19** (via Vite) <br>• **Vite** for fast bundling and development server <br>• **Tailwind CSS 4** for utility-first styling <br>• **motion** (Framer Motion–style) for animations <br>• **react-hot-toast** for notifications <br>• **ESLint** with recommended React configs |
| **Key Features** | • **Dark mode toggle** persisted in `localStorage` and synced with system preference <br>• **Custom cursor** (dot + outer ring) with easing <br>• **Animated entrances** of sections using `motion` (opacity & slide-in) <br>• **Hover-activated gradient glow** on service cards <br>• **Responsive layout** with Tailwind breakpoints (`sm`, `md`, `lg`, `xl`) |
| **Assets** | Collection of SVG icons (ads, arrows, social, logos, theme icons, etc.) and PNG screenshots of the agency's work. Assets are imported via an `assets.js` helper. |
| **Scripts** | • `npm run dev` – start Vite dev server <br>• `npm run build` – production build <br>• `npm run lint` – run ESLint <br>• `npm run preview` – preview the built site |
| **Potential Extensions** | • Add a real contact form backend (Formspree, Nodemailer, or serverless function) <br>• Replace placeholder `ContactUs.jsx` with a styled form <br>• Integrate analytics (Google Analytics, Plausible, etc.) <br>• Add internationalisation (i18n) for multilingual support |
| **Overall Impression** | A clean, well-structured starter for a digital agency landing page. Built with **React 19**, **Vite**, and **Tailwind**, it delivers a polished UI with minimal custom CSS. Smooth animations (`motion`), dark mode, and custom cursor effects provide a distinctive modern feel. |
| **How to Run** | 1. Clone the repository <br>2. Run `npm install` to install dependencies <br>3. Start the dev server with `npm run dev` and open the URL (usually `http://localhost:5173`) |
| **License / Docs** | • Minimal `README.md` (this file) <br>• A Word document (`Digital_Agency_Website_Overview.docx`) with design/feature notes <br>• ⚠️ No explicit license file is included |

## 📂 Project Layout

```bash
agency-ai/
├─ .gitattributes
├─ .gitignore
├─ README.md
├─ eslint.config.js
├─ vite.config.js
├─ index.html               # Entry HTML file
├─ package.json             # Project dependencies & scripts
├─ package-lock.json
├─ public/
│   └─ favicon.ico
└─ src/
  ├─ main.jsx             # React root mount
  ├─ App.jsx              # Top-level component (theme handling, custom cursor)
  ├─ index.css            # Global Tailwind + custom CSS variables
  ├─ assets/              # Icons, images, logo files (SVG/PNG)
  └─ components/
    ├─ Navbar.jsx       # Responsive navigation with dark mode toggle
    ├─ Hero.jsx         # Hero section with animated background
    ├─ TrustedBy.jsx    # Client logo carousel
    ├─ Services.jsx     # Services list wrapper
    ├─ ServiceCard.jsx  # Service cards with hover glow effect
    ├─ OurWork.jsx      # Portfolio grid
    ├─ Teams.jsx        # Team member cards
    ├─ ContactUs.jsx    # Contact form placeholder
    ├─ Footer.jsx       # Site footer
    └─ Title.jsx        # Reusable animated heading/description component
```

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to modify.

---

## 👨‍💻 Author

**Sahil Zalte**  
🔗 [Portfolio](https://codebysahil.vercel.app)  
📧 contactcodebysahil@gmail.com
