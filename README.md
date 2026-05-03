# Srinivas Kookutla Real Estate Portfolio

A premium, modern, and fully responsive real estate consultancy portfolio website built with pure HTML, CSS, and JavaScript. 

## 🌟 Features
- **Responsive Design**: Mobile-first architecture ensures the site looks perfect on phones, tablets, and desktops.
- **Premium UI/UX**: Designed with a professional dark blue and gold color scheme (`#0f172a`, `#d4af37`).
- **No Heavy Frameworks**: Built using vanilla HTML, CSS, and JS. Lightweight and blazing fast.
- **Scroll Animations**: Smooth reveal animations as the user scrolls down the page.
- **Property Filtering**: Simple and elegant property filtering logic (All, For Sale, For Rent).
- **Floating Action Buttons**: Persistent quick-access buttons for WhatsApp and Phone Calls.
- **SEO Optimized**: Includes meta descriptions, keywords, Open Graph tags, and semantic HTML for search engine discoverability.

## 📁 Project Structure

```
/
├── index.html       # Main HTML file (Semantic structure, meta tags)
├── style.css        # Pure CSS (Custom variables, animations, responsiveness)
├── script.js        # Vanilla JS (Mobile menu, scroll animations, filtering)
├── README.md        # Project documentation
└── /assets          # Folder for images (portrait, logos, etc.)
```

## 🚀 How to Deploy on GitHub Pages

1. **Commit and Push your changes:**
   ```bash
   git add .
   git commit -m "Update portfolio with new HTML/CSS/JS design"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub: `https://github.com/YOUR_USERNAME/YOUR_REPO`
   - Click on **Settings** (the gear icon).
   - In the left sidebar, click on **Pages**.
   - Under the "Build and deployment" section, set **Source** to **Deploy from a branch**.
   - Under **Branch**, select `main` from the dropdown and leave the folder as `/ (root)`.
   - Click **Save**.

3. **View Your Site:**
   - Wait about 1-2 minutes.
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## 🖼️ Updating Images
To display your own images (like the trademark logo and portrait), place them into the `assets` folder with the following exact filenames:
- `srinivas-father-portrait.jpg`
- `srinivas-trademark-logo.png`

*(Fallback dummy images from Unsplash and UI-Avatars will show automatically if these files are not found).*

## 📞 Contact Integration
The contact forms, call links (`tel:+919848406691`), and WhatsApp links (`https://wa.me/919848406691`) are already hardcoded with the provided contact information. Clicking them on a mobile device will instantly open the respective dialer or chat app.
