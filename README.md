# 💖 Lehigh ColorStack x NSBE: Code 4 Your Crush 💖

Welcome to **Code 4 Your Crush**, a fun event where you can code your own Valentine’s Day card in HTML!  
Choose a template, customize it with your own message or image, and share it with a friend or crush.

---

## 📋 How This Works

Each Valentine card is a small HTML “mini-website” hosted using **GitHub Pages**, which means it works on **phones, tablets, and computers**. You can customize your card without needing any special software — just a browser.

### Templates

| Template Name          | Folder Name             | Description |
|------------------------|------------------------|-------------|
| Just Friends 💖        | `just-friends`         | A friendly Valentine card with an image and animation. |
| The Big Question ❤️    | `the-big-question`     | Ask someone to be your Valentine with a big, bold button. |
| Tap for Love 💘        | `tap-for-love`         | Interactive “surprise message” card using JavaScript. |
| Heartbeat ❤️           | `heartbeat`            | Animated heart with a simple, stylish Valentine message. |
| Sweet Talk 🍬          | `sweet-talk`           | A fun candy-gram style card listing compliments. |
| Valentine Photos 📸    | `valentine-photos`     | Photo-letter card with animated memories. |

---

## 🛠️ How to Customize Your Card

1. **Choose a template folder** you want to use (e.g., `just-friends/`).
2. **Add your image**:
   - Place your image file in the same folder as `index.html`  
   - Or, if using an `images/` folder inside the template, update `<img src="images/photo.jpg">`
3. **Edit the text** in `index.html`:
   - Change headings, messages, or colors
4. **Preview in your browser**:
   - Double-click `index.html` on your computer or open the GitHub Pages link
5. **Test on your phone**:
   - Open the link to make sure the layout looks good

---

## ✨ Things You Can Customize (with Examples)

### Fonts
**Use a built-in font:**

```html
<style>
   body { font-family: "Georgia", serif; }
</style>


**Use a Google Font:**

```html
<head>
   <link rel="preconnect" href="https://fonts.googleapis.com">
   <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
   <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
   <style>
      body { font-family: "Pacifico", cursive; }
   </style>
</head>
```

### Colors
```html
<style>
   body { background: #ffe6f0; color: #d6336c; }
   .card { background: white; }
</style>
```

### Shapes (rounded corners, circles, pills)
```html
<style>
   .card { border-radius: 20px; }
   img { width: 120px; height: 120px; border-radius: 50%; }
   .pill-button { border-radius: 999px; padding: 10px 20px; }
</style>
```

### Shadows & Glow
```html
<style>
   .card { box-shadow: 0 10px 30px rgba(0,0,0,0.15); }
   h1 { text-shadow: 0 2px 10px rgba(214,51,108,0.35); }
</style>
```

### Spacing & Layout
```html
<style>
   .card { padding: 24px; max-width: 360px; margin: 0 auto; }
   p { line-height: 1.6; }
</style>
```

### Animation (simple hover)
```html
<style>
   .card { transition: transform 0.2s ease; }
   .card:hover { transform: scale(1.02); }
</style>
```

---

## 📤 Sharing Your Card

When you’re done, **send only the link to your template**, not the repo itself or the homepage.  

Example:

   https://YOUR-GITHUB-USERNAME.github.io/ColorStackxNSBE-Code4YourCrush/just-friends/

