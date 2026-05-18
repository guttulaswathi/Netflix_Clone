# Netflix Clone — Homepage UI

A responsive **Netflix-inspired homepage** built with **HTML** and **CSS** only. It includes a fixed navigation bar, full-screen hero banner with overlay, horizontally scrolling movie rows, and hover effects on posters and buttons.

> **Disclaimer:** This is an educational UI clone and is **not affiliated with** or endorsed by Netflix.

---

## Features

- **Fixed navbar** with brand styling, primary navigation links, and profile control
- **Hero section** with backdrop image, dark overlay, title, description, and **Play** / **More Info** actions
- **Content rails:** Trending Now, Popular on Netflix, Action Movies, and Top Rated
- **Movie cards** with rounded corners, scale-on-hover, shadow, and smooth transitions
- **Responsive layout** with breakpoints for tablet and mobile (smaller cards, stacked navigation)
- **Cinematic styling:** Netflix-style palette (`#141414`, `#E50914`, `#FFFFFF`), gradients, and smooth scrolling

---

## Technologies Used

| Tech        | Role                          |
| ----------- | ----------------------------- |
| HTML5       | Semantic structure & content  |
| CSS3        | Layout, theming, animations |
| Google Fonts | Inter + Bebas Neue          |

Movie posters and the hero backdrop load from **The Movie Database (TMDB)** image CDN URLs so the page works without local image files. You can optionally replace them with files under `images/`.

---

## Screenshots

_Add your own screenshots here after you run the project._

1. Save images (for example `docs/screenshot-desktop.png`, `docs/screenshot-mobile.png`) in the repo.
2. Update this section with Markdown, for example:

```markdown
### Desktop
![Desktop view](docs/screenshot-desktop.png)

### Mobile
![Mobile view](docs/screenshot-mobile.png)
```

---

## How to Run the Project

### Option A — Open the file (quickest)

1. Open the project folder.
2. Double-click **`index.html`** to open it in your default browser.

### Option B — Local server (recommended)

Using **Node.js** (from the project folder in **Command Prompt** or **PowerShell**):

```powershell
cd $env:USERPROFILE\OneDrive\Desktop\NetflixClone
npx --yes serve
```

Then visit the URL shown in the terminal (often `http://localhost:3000`).

Using **Python** (if installed):

```powershell
cd $env:USERPROFILE\OneDrive\Desktop\NetflixClone
python -m http.server 8080
```

Then open `http://localhost:8080`.

---

## Folder Structure

```text
NetflixClone/
├── index.html          # Main page markup
├── style.css           # All styles, layout, and responsive rules
├── images/             # Optional local assets (e.g. hero-banner.jpg)
│   └── .gitkeep
├── .gitignore
└── README.md
```

---

## Author

**Chinn**

- GitHub: _[add your profile URL](https://github.com/your-username)_

---

## License

This project is for **learning purposes** only. Netflix is a trademark of Netflix, Inc.
