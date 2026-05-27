# Trinh Ngoc Huynh — Academic Homepage

Personal academic website hosted on GitHub Pages at [huynhspm.github.io](https://huynhspm.github.io).

## About

I am a Master's student and research member at the Institute for Artificial Intelligence, VNU University of Engineering and Technology (VNU-UET). My research focuses on medical image analysis leveraging generative methods (e.g., VAE, diffusion model, and flow matching).

## Website Structure

```
├── index.html              # Homepage (profile, education, selected publications)
├── index-style.css         # Shared stylesheet for all pages
├── publications/
│   └── index.html          # Full publication list
├── projects/
│   └── index.html          # Research and student projects
└── assets/
    ├── avatar.jpg          # Profile photo
    └── cv.pdf              # Curriculum Vitae
```

## Pages

- **Home** — Brief profile, education, and selected publications
- **Publications** — Complete list of publications with links to papers
- **Projects** — Research projects, ongoing work, and award-winning student research

## Local Development

To preview locally:

```bash
# Using Python
python3 -m http.server 8000

# Or using Node.js
npx serve .
```

Then open `http://localhost:8000` in your browser.

## License

This website is for personal academic use.