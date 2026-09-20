# ✨ Minimalist Luxury Birthday Experience

> A clean, modern, mobile-friendly screen-to-screen birthday web application designed with fluid animations, accurate candle physics, and progressive audio streaming.

**🔗 Live Website:** [https://cryptodash-stack.github.io/birthday-Wish/](https://cryptodash-stack.github.io/birthday-Wish/)  
**📦 Repository:** [https://github.com/cryptodash-stack/birthday-Wish](https://github.com/cryptodash-stack/birthday-Wish)

---

## 🌟 Highlights

- **📱 Mobile-First Responsive**: Designed to look and feel like a high-end native mobile app on phones, while gracefully centered on desktop screens.
- **⏭️ Screen-to-Screen Navigation (No Scroll Triggers)**: 7 structured, focused chapters with smooth transitions, progress stepper indicators, and back navigation.
- **🕯️ Interactive Candle & Wish Ceremony**: Minimalist candle with realistic flame flicker; tap to blow out the flame with curling smoke and stardust particles.
- **💌 Wax-Sealed Letter**: An elegant envelope with a wax seal that unlocks a heartfelt, handwritten note from Usman to Ambivert.
- **✦ Starry Wish Generator**: Interactive blessing generator revealing curated wishes for the year ahead.
- **🎵 Progressive Audio Streaming**: Streams `birthday_song.mp3` with animated sound wave equalizer and tap-to-unlock audio.
- **⚡ Lightweight (0ms Freeze)**: Pure HTML, Vanilla CSS, and JavaScript (~58 KB). Zero npm install, no bundlers, no heavy frameworks.


---

## 🛠️ How to Customize

All content is conveniently located inside `index.html`:

### 1. Change Names
Open `index.html` and use find & replace:
- Replace `Ambivert` with your friend's name.
- Replace `Usman` with your name.
- Replace the monogram initial `A` in the seal (search for `<div class="orb-initials">A</div>`).

### 2. Change the Song
Replace `birthday_song.mp3` with your own `.mp3` file (keep the name `birthday_song.mp3`, or update the filename inside `<audio id="bday-audio">` in `index.html`).

### 3. Personalize the Letter
Scroll to Screen 5 (`#screen-5`) inside `index.html` and edit the paragraphs inside `<div class="letter-parchment">` to write your own personalized message.

### 4. Direct Screen Preview (Testing)
You can jump directly to any screen by adding `?s=<number>` to the URL:
- `index.html?s=3` (Jumps to the Cake & Candle screen)
- `index.html?s=5` (Jumps to the Letter screen)

---

## 📁 Project Structure

```text
├── index.html          # The entire application (HTML + CSS + JS)
├── birthday_song.mp3   # Background birthday music
├── README.md           # Documentation & setup guide
└── .gitignore          # Git ignore rules
```

---

## 📄 License
MIT License. Feel free to use and share the love for your friends' and loved ones' birthdays!
