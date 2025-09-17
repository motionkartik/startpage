# **Startup Bookmarks** – A Sleek, Modern Bookmark Manager

> *Minimal. Fast. Beautiful.*  
> The perfect startup page for developers, founders, and digital minimalists.

![Preview](iamge.png)  
*Clean interface with dynamic folder support and smart search*

---

## ✨ Features That Make It Shine

### 🔽 **Dead-Simple CSV Setup**
No database. No backend. Just a single `bookmarks.csv` file:
```csv
Name,URL
GitHub,https://github.com
Qwen Chat,https://chat.qwen.ai/new
Design Inspiration,https://dribbble.com,https://a16z.com
```
- First column = folder or bookmark name
- Multiple URLs in one row = automatic **folder creation**
- Edit it anywhere — GitHub, Notion, Excel — it just works!

✅ Perfect for version control, sharing, or syncing across devices.

---

### 📱↔️ **Auto-Adaptive Layout**
Smart design that adjusts based on your device:

- **Mobile**: Full-screen immersive experience, bottom-aligned for thumb-friendly access
- **Desktop**: Clean top alignment with more breathing room
- Responsive grid scales smoothly from phones to 4K monitors


---

### 📁 **Folder Support (with Modal UI)**
Organize bookmarks into folders without clutter:
- Click any folder to open a sleek overlay modal
- Backdrop blur effect + smooth animations = modern feel
- Escape key or click outside to close — intuitive UX

---

### 🔍 **Built-In Search Bar**
Type once, search everywhere:
- Press Enter → instantly search via Google
- Customizable search engine (`CONFIG.SEARCH_ENGINE`)

⚡ No need to navigate away. Your flow stays uninterrupted.

---

### 🎨 **Clean & Minimal Design**
Crafted for focus, not distraction:
- Dark mode by default (easy on the eyes)
- Subtle hover effects and shadows
- Rounded corners, generous spacing, elegant transitions
- Typography optimized for readability

---

### 💨 **Lightweight & Blazing Fast**
- **No frameworks**, no dependencies
- Under 10KB (minified) — loads instantly
- Works offline if hosted locally
- Zero tracking, zero bloat

🎯 Ideal for self-hosting on GitHub Pages, Vercel, Netlify, or even local file system.

---

### 🔧 **Easy Customization**
Just edit the config at the top of the script:
```js
const CONFIG = {
  CSV_URL: 'bookmarks.csv', // Change path or use raw GitHub link
  SEARCH_ENGINE: 'https://www.google.com/search?q='  // Swap to DuckDuckGo, Bing, etc.
};
```

🎨 Tweak colors, fonts, or layout in CSS — everything is readable and maintainable.

---

### ⌨️ **Keyboard Friendly**
- `Enter` to search
- `Escape` to close folder modals
- Tab through bookmarks seamlessly

---

## 🛠️ How to Use

### 1. Clone or Download
```bash
git clone https://github.com/yourname/startup-bookmarks.git
```

### 2. Edit `bookmarks.csv`
Add your favorite sites and folders:
```csv
Social,https://twitter.com,https://linkedin.com
Learning,https://coursera.org,https://youtube.com
Notion,https://notion.so
```

### 3. Host It
Deploy in seconds:
- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)
- Or open `index.html` directly in your browser!

🌐 No server needed. Runs entirely client-side.

---

## 🌟 Why You’ll Love It

| Benefit | Why It Matters |
|-------|----------------|
| ✅ Zero setup complexity | Just edit a CSV and go |
| ✅ Organized & scalable | Folders keep things tidy as your list grows |
| ✅ Instant loading | Faster than your browser’s new tab page |
| ✅ Mobile-first elegance | Designed for touch, looks great everywhere |
| ✅ Open source & free | Fully customizable, forever |

---

## 📸 Screenshot
![App Preview](image.png)  


---

## 🙌 Made With Love
Created for people who value speed, simplicity, and style.

💡 Inspired by dashboards like Start.me, Raindrop, and Speed Dial — but lighter, faster, and fully open.

---

## 📬 Feedback? Ideas?
Open an issue, fork it, or tag me [@motionkartik](https://twitter.com/motionkartik) — I’d love to see how you use it!

---

✨ Turn your chaotic tabs into a beautiful, organized launchpad.  
**Download, deploy, and delight in simplicity.**