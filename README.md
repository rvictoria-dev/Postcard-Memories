# Postcard Memories

### ₊⊹ About

A double-sided digital memory card. On the front, a grid of photos brings together memories of places, loved ones, a favorite pet, and a personal portrait, capturing special moments. Below are the location and year when those memories were made. The back is meant to illustrate something that evokes nostalgia and memories of that cherished day.

<img width="1308" height="764" alt="image" src="https://github.com/user-attachments/assets/d8889727-4c09-4c70-baa0-94d9e375e0cb" />

---

### ★ Features

***Visual***
- Clean layout (3x2) with 12px spacing, evoking the aesthetic of a modern scrapbook.
- Location and year identified with an intimate, handwritten-style font.
- Bottom section featuring serif typography, high readability, and comfortable spacing for the quote.
- Dark background (#353535) with off-white cards (#f4f3f1), drawing the eye to the memories.


***Code***
- Matrix created with `display: grid` and `repeat(3, 1fr)` on the `.container`, using `object-fit: cover` on images to prevent distortion.
- Use of the Homemade Apple font in the `<figcaption>`, centered end-to-end using `grid-column: 1 / -1`.
- Built using the semantic tags `<blockquote>`, `<p>`, and `<footer>`, styled with EB Garamond and `line-height: 1.5`.
- Absolute alignment applied to the `body` with `display: flex` and `min-height: 100vh`, ensuring consistency on any monitor.

---

### ⚙️ Tech Stack

- **HTML5**
- **CSS3**

---

### 🖿 Project structure

```
Postcard-Memories/
├── Assets/
├── index.html
├── style.css
└── README.md
```

---

### .ᐟ.ᐟ How It Works

- **Unified Structure:** The postcard is divided into two independent blocks within a single <article> tag.
- **Grid Layout (3x2):** The .container uses `display: grid` with `repeat(3, 1fr)` and `gap: 12px` to arrange the six photos symmetrically.
- **Figure Caption Alignment:** The <figcaption> caption spans the full width of the grid using `grid-column: 1 / -1`, ensuring it is perfectly centered below the photos.
- **Quote Block:** The `<blockquote>` tag manages the text and author, using `<br />` for manual line breaks while maintaining HTML5 semantics.
- **Width Symmetry:** Both the photo block and the citation block share exactly the same width (width: 500px) and padding, simulating the front and back of a postcard.
- **Typographic Combination:** Selective use of Google Fonts: Homemade Apple for the calligraphy and EB Garamond with varying font weights to establish hierarchy within the quote.
- **Centered Layout:** The `body` uses Flexbox (`display: flex`) combined with `min-height: 100vh` to lock and center the entire design precisely on the screen.
