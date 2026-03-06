# Pig Popular — Book Website

A one-page website for *Pig Popular* by Sherri Cruz, built for GitHub Pages.

---

## 📁 Folder Structure

Your repo should look like this:

```
your-repo/
├── index.html         ← the website file (rename pig-popular.html → index.html)
├── images/
│   ├── main.jpg       ← main focal photo (large hero image)
│   ├── photo2.jpg     ← second photo (bottom left)
│   └── photo3.jpg     ← third photo (bottom right)
└── README.md
```

---

## 🖼️ Adding Your Photos

1. Create a folder called `images` in your repo
2. Add your three photos and name them exactly:
   - `main.jpg` — your main cover/focal image
   - `photo2.jpg` — second image
   - `photo3.jpg` — third image
3. If your photos are `.png` instead of `.jpg`, just update the `src` in `index.html`:
   ```html
   <img src="images/main.png" .../>
   ```

---

## 🚀 How to Publish on GitHub Pages

1. Create a new repository on GitHub (can be public or private — Pages requires public on free accounts)
2. Upload all your files: `index.html`, `README.md`, and the `images/` folder
3. Go to your repo → **Settings** → **Pages** (left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder → click **Save**
6. Wait ~1 minute, then your site will be live at:
   ```
   https://yourusername.github.io/your-repo-name/
   ```

---

## ✏️ How to Add Character Descriptions

Open `index.html` and find the four character sections. Replace the placeholder text inside each `<div class="char-placeholder">` block with your paragraph. For example:

```html
<div class="char-content">
  <h3>Pig Popular</h3>
  <p>Your character description goes here...</p>
</div>
```

---

## 🔊 Ocean Sounds

The ocean + seagull sounds are generated in-browser — no audio files needed!
Visitors click the **Play Ocean Sounds** button to turn them on.
