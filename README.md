# Portfolio Website 
## Rebecca Cervasi, Machine Learning Engineer (PhD)

Personal portfolio website, showcasing experience in deep learning, computer vision, 3D reconstruction, and large-scale ML systems.

🌐 **Live site**: [cervasio.tech](https://cervasio.tech)

---

## About

This portfolio presents my background, projects, and skills as a Machine Learning Engineer with a PhD in Engineering Physics. It covers my work across computer vision, document AI, 3D reconstruction, and cloud-based ML infrastructure.

---

## Built With

- **Template**: [Strata by HTML5 UP](https://html5up.net/strata) — free for personal and commercial use under the [CCA 3.0 license](https://html5up.net/license)
- **Hosting**: GitHub Pages
- **CI/CD**: GitHub Actions (automated deployment on PR and push to `main`)

---

## Project Structure

```
.
├── index.html                  # Main page
├── images/                     # Background and portfolio images
│   └── fulls/
│   │   └── 01.jpg  
│   │   └── ...  
│   └── thumbs/
│   │   └── 01.jpg  
│   │   └── ...  
│   └── bg.jpg
│   └── avatar.jpg
├── assets/
│   ├── css/
│   │   └── main.css            # Main stylesheet
│   ├── js/                     # JavaScript
│   └── webfonts/               # Font Awesome icons
└── .github/
    └── workflows/
        └── static.yml          # GitHub Actions deployment workflow
```

---

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions on every push to `main`.

A **preview environment** is triggered on pull requests targeting `main`, so changes can be reviewed before going live.

To deploy manually, go to the **Actions** tab and run the workflow manually via `workflow_dispatch`.

---

## Local Development

No build step required (static website). Just open `index.html` in your browser, or use a simple local server:

```bash
# Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## Contact

- 📧 [rebecca@cervasio.tech](mailto:rebecca@cervasio.tech)
- 💼 [LinkedIn](https://linkedin.com/in/rebecca-cervasio-20208560)
- 🐙 [GitHub](https://github.com/rebcervasio)

---

## License

Site content © Rebecca Cervasio. Template by [HTML5 UP](https://html5up.net), released under the [Creative Commons Attribution 3.0 license](https://html5up.net/license).
