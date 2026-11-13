# Rushmanth Nalluri — Portfolio

Personal portfolio website for Rushmanth Nalluri, Computer Science student at KL University building AI/ML and low-level concurrent systems.

## Live

- **CloudFront (HTTPS / Production):** [https://d11q7nlxxrnrn0.cloudfront.net/](https://d11q7nlxxrnrn0.cloudfront.net/)
- **GitHub Pages:** [https://rushmanthnalluri.github.io/portfolio/](https://rushmanthnalluri.github.io/portfolio/)
- **S3 Bucket:** `rushmanth-portfolio-site-2026` (ap-south-1)

## Features

- **30-Second Recruiter Visual Hierarchy:** Immediate clarity on technical competencies and systems/ML projects.
- **Featured Projects:** Hand-crafted, hardcoded architecture cards with real benchmarks (PropPulse, CopyFast, TaskForge, Placement Predict).
- **Curated Certifications:** Featured Stanford, UC San Diego, DeepLearning.AI, and AWS credentials.
- **Skills Matrix:** Categorized filters (AI/ML, Systems, Languages, Backend/Cloud, Tools/Testing).
- **Verified GitHub Activity:** Responsive contribution calendar with timeout and graceful offline/error fallback.
- **Single-File Self-Contained:** Fully inlined CSS, JS, and institutional logos as base64 data URIs for instant loading and zero CDN image dependencies.
- **Dark / Light Mode:** Instant theme toggle with local storage persistence.

## Tech Stack

- HTML5, CSS3, JavaScript (vanilla)
- Tailwind CSS
- CloudFront + Amazon S3 / GitHub Pages
- Python (build and sync scripts)

## Local Development

Open `index.html` directly in any web browser or serve locally:

```bash
python server.py
```

Then open `http://127.0.0.1:8081` in your browser.
