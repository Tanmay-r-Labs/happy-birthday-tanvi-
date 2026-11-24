# 🎂 Romantic Birthday Website For Your Girlfriend 💖

A dreamy, aesthetic, and interactive birthday website customized for your girlfriend. Crafted with soft pastel tones, interactive birthday cake candle blowout, live relationship counter, polaroid scrapbook, 3D love flip cards, handwritten love letter, playful runaway "No" button, and dreamy background music.

---

## 🚀 Quick Start (Instant Preview)

1. **Option A (Instant)**: Simply double-click `index.html` in your file explorer to open it in Chrome, Edge, or Safari!
2. **Option B (Local Web Server)**:
   Open a terminal in this folder and run:
   ```bash
   python -m http.server 8080
   ```
   Then open `http://localhost:8080` in your browser.

---

## 🎨 How to Personalize (Takes 2 Minutes!)

All the personal info is neatly organized in **`js/config.js`**. You don't need to touch any complicated code!

Open `js/config.js` in any text editor and change:
- **`girlfriendName`**: Her real name (e.g. `"Maya"`, `"Emily"`, etc.)
- **`nickname`**: Your pet name for her (e.g. `"Princess"`, `"Honeybun"`, `"Cutie"`)
- **`partnerName`**: Your name for the letter signature
- **`birthdayDate`**: Her birthday (e.g. `"2026-11-22"`)
- **`togetherSince`**: The exact date you met or became official (e.g. `"2024-03-15T00:00:00"`) for the live love counter.
- **`reasons`**: Add or edit the reasons why you love her.
- **`timeline`**: Add your real milestones (First date, road trip, anniversary, etc.).
- **`letter`**: Write your own heartfelt birthday message.

---

## 📸 How to Add Your Real Photos

1. Take your favorite photos of you two (or of her) and save them into the `assets/images/` folder as `.jpg` or `.png`.
2. In `js/config.js`, update the polaroid image paths:
   ```javascript
   polaroids: [
     {
       src: "assets/images/my-photo-1.jpg",
       caption: "Our first trip to the beach 🌊",
       rotation: -3
     },
     {
       src: "assets/images/my-photo-2.jpg",
       caption: "Best anniversary dinner ever 🍝",
       rotation: 2
     }
   ]
   ```

---

## 🎵 Background Music

- **Out-of-the-box**: The site includes a built-in soft music-box lullaby synthesizer using the browser's Web Audio API that plays automatically without needing any audio files!
- **Custom Song**: If you have an mp3 of her favorite song (or "your song"), place it in `assets/audio/song.mp3` and update `audioSrc` in `js/config.js`:
  ```javascript
  audioSrc: "assets/audio/song.mp3"
  ```

---

## 🌐 How to Host for Free (Send Her a Real Link!)

You can easily host this so she can view it on her phone anytime:

### 1. Free Vercel Deployment (Easiest)
1. Go to [vercel.com](https://vercel.com) and log in.
2. Drag and drop this `girlfriend-website` folder directly into Vercel.
3. In 10 seconds, you get a link like `https://for-my-cutie.vercel.app` to text her!

### 2. Free Netlify Drop
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag the `girlfriend-website` folder onto the page.
3. You immediately get a live shareable URL!

### 3. GitHub Pages
1. Push this folder to a GitHub repository.
2. In repository **Settings** > **Pages**, set branch to `main` and root to `/`.
3. Your site will be live at `https://<username>.github.io/<repo-name>`.
