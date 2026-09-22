# CharacterCap

**A fast, privacy-first word counter and text analytics tool that runs entirely in your browser.**

🔗 **Live site:** [charactercap.com](https://charactercap.com)

<!-- Add a screenshot: drag an image into this file while editing on GitHub, then replace this comment -->

Your text never leaves your device. There's no account to create, and nothing you write is sent to a server. Every calculation happens client-side in vanilla JavaScript, and the site is served from Cloudflare's edge network for near-instant load times worldwide.

---

## ✨ Features

### Real-time text analytics
- Live word, character, sentence, and paragraph counts
- Estimated reading time
- **Keyword density** analysis with stop-word filtering
- **Flesch Reading Ease** score with a custom regex-based syllable counter, supporting both the English formula and the German **Flesch-Amstad** variant

### Social media & SEO limits
- Live progress bars for character limits on **X/Twitter, LinkedIn, Instagram, and TikTok**
- Length checks for **SEO meta titles and descriptions**

### Editing tools
- Undo/redo history manager
- Text cleanup: strip extra spaces and line breaks with one click
- Case converters (UPPERCASE, lowercase, Title Case, and more)
- **Text-to-speech** playback using the Web Speech API

### Experience
- 🌙 Dark mode that follows your system preference and remembers your choice
- 🧘 Distraction-free **Zen Mode**
- 🌍 Full **English and German** versions
- 📱 Fully responsive on desktop, tablet, and mobile

---

## 🛠️ Tech Stack

| Area | Technology |
|---|---|
| Markup | HTML5, schema.org JSON-LD structured data |
| Styling | Tailwind CSS (via CDN) |
| Logic | Vanilla JavaScript (ES6+), no frameworks |
| Browser APIs | Web Speech API (`speechSynthesis`), `localStorage` |
| SEO | XML sitemap, `robots.txt`, hreflang-ready EN/DE pages |
| Hosting | Cloudflare Pages (global edge caching) |

---

## 📁 Project Structure

```
charactercap/
├── index.html                        # Main tool (English)
├── de.html                           # Main tool (German)
├── readability-score-guide.html      # Guide: understanding readability scores
├── social-media-limits-guide.html    # Guide: character limits per platform
├── contact.html
├── privacy.html
├── terms.html
├── sitemap.xml
├── robots.txt
└── favicon.ico
```

---

## 💻 Run Locally

It's a static site, so there's no build step.

```bash
git clone https://github.com/GeorgeTsagg18/charactercap.git
cd charactercap
```

Then open `index.html` in your browser, or serve the folder locally:

```bash
npx serve .
```

---

## 🔒 Privacy

All text processing happens in your browser, and nothing you type is sent to a server. Preferences such as dark mode are saved in your own browser's local storage. The site is supported by Google AdSense, which may use cookies as described in the [privacy policy](https://charactercap.com/privacy.html).

---

## 👤 Author

**George Tsagkarakis**, front-end developer
[GitHub](https://github.com/GeorgeTsagg18) · [Upwork](https://www.upwork.com/freelancers/~0193d0fe5d3fd14798) · [Email](mailto:georgetsag18@gmail.com)
