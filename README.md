<a name="readme-top"></a>

[![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/azizulabedin/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/azizulabedinazmi)

<!-- After your first Netlify deploy, add your status badge here:
[![Netlify Status](https://api.netlify.com/api/v1/badges/<SITE_ID>/deploy-status)](https://app.netlify.com/projects/<SITE_NAME>/deploys)
-->

<div align="center">
  <h3>Personal Website</h3>
  <p>
    A single-page personal website for Azizul Abedin Azmi: machine learning, computer vision, and data science.
    Plain HTML and CSS, no build step, hosted on Netlify.
    <br /><br />
    <a href="https://azizulabedinazmi.netlify.app/">View Live Site</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#repository-structure">Repository Structure</a></li>
    <li><a href="#quick-start">Quick Start</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#customising">Customising</a></li>
    <li><a href="#deployment-checklist">Deployment Checklist</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## 📋 About The Project <a name="about-the-project"></a>

This is the personal website built for FlyRank assignment PF-04. It covers who I am, what I am building, publications, selected projects, links to my profiles, and a placeholder section for future posts and capstone work.

Design choices:

- **One file for the page.** `index.html` holds the markup and the CSS, so every deployed file is easy to explain.
- **No JavaScript, no dependencies.** Nothing to install, nothing to break.
- **Light and dark mode** through the `prefers-color-scheme` media query.
- **Responsive.** A single centred column that works on phones.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🛠️ Built With <a name="built-with"></a>

- HTML5
- CSS3 (custom properties, flexbox, media queries)
- [Netlify](https://www.netlify.com/) for hosting and automatic HTTPS

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🗂️ Repository Structure <a name="repository-structure"></a>

| File | Purpose |
|---|---|
| `index.html` | The whole site: content and styles. |
| `netlify.toml` | Tells Netlify to publish the repo root and sets basic security headers. |
| `robots.txt` | Lets search engines crawl the site. |
| `.gitignore` | Keeps OS and editor files out of Git. |
| `LICENSE` | MIT License. |
| `README.md` | This file. |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🚀 Quick Start <a name="quick-start"></a>

Create your own copy on Netlify with one click:

[<img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" />](https://app.netlify.com/start/deploy?repository=https://github.com/azizulabedinazmi/FlyRank_PF-04)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎯 Getting Started <a name="getting-started"></a>

1. Clone the repo

```sh
git clone https://github.com/azizulabedinazmi/FlyRank_PF-04.git
cd FlyRank_PF-04
```

2. Open `index.html` in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ✏️ Customising <a name="customising"></a>

- Replace the contact link in `index.html` with a real booking URL when you have one.
- Add a public CV link to the `.links` list when you have a hosted copy (for example a public Drive or GitHub link). The PF-04 rubric asks for working LinkedIn, GitHub, CV, and booking links.
- Colours live in the `:root` block at the top of the `<style>` tag.
- At capstone approval, add the FlyRank badge inside the "Posts & capstone" section. Instructions are provided then.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🌐 DNS walkthrough <a name="dns-walkthrough"></a>

The assignment DNS explanation is in [dns-walkthrough.md](dns-walkthrough.md).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ✅ Deployment Checklist <a name="deployment-checklist"></a>

- [ ] Booking link added (the current button links to Facebook for contact)
- [ ] CV link added
- [x] Site renamed in Netlify (Site configuration → Change site name)
- [ ] Opened in a private window; padlock shows; every link works after the latest deploy
- [ ] Site URL added to LinkedIn and CV
- [x] Live site URL: https://azizulabedinazmi.netlify.app/
- [ ] DNS walkthrough submitted in the portal

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📜 License <a name="license"></a>

Distributed under the MIT License. See `LICENSE` for more information. Publications and project descriptions remain the property of their respective authors and publishers.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📧 Contact <a name="contact"></a>

Azizul Abedin Azmi, [LinkedIn](https://www.linkedin.com/in/azizulabedin/)

Project Link: [https://github.com/azizulabedinazmi/FlyRank_PF-04](https://github.com/azizulabedinazmi/FlyRank_PF-04)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
