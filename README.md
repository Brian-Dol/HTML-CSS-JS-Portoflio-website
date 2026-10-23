<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:164e63,100:06b6d4&height=170&section=header&text=Responsive%20Portfolio%20Template&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=A%20static%20portfolio%20site%20built%20with%20HTML%2C%20CSS%2C%20and%20JavaScript&descAlignY=60&descSize=16" alt="Responsive Portfolio Template — static HTML, CSS, and JavaScript site" />

![HTML5](https://img.shields.io/badge/HTML5-Markup-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Styles-1572b6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Interactions-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Layout-Responsive-0891b2?style=flat-square)

</div>

A static, responsive portfolio template with profile, about, experience, projects, and contact sections. It uses plain HTML, CSS, and a small JavaScript function for the mobile navigation menu.

## ✨ Features

- Desktop navigation and a collapsible hamburger menu for smaller screens.
- Profile, about, experience, projects, and contact sections with in-page navigation.
- Example assets for profile imagery, project cards, social links, and a resume PDF.
- Responsive styling split between `style.css` and `mediaqueries.css`.
- No framework, package manager, or build step required.

## 🏗️ Architecture

The browser loads one HTML page, its CSS stylesheets and local assets; `script.js` toggles the mobile menu. There is no backend or API.

## 🧰 Tech stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3, responsive media queries |
| Interaction | Vanilla JavaScript |
| Assets | Local images and sample resume PDF |
| Runtime | Any modern web browser |

## 🚀 Getting started

No installation or compilation is needed. Clone the repository and open `index.html` in a browser. From Windows PowerShell:

```powershell
git clone https://github.com/Brian-Dol/HTML-CSS-JS-Portoflio-website.git
Set-Location HTML-CSS-JS-Portoflio-website
Start-Process .\index.html
```

To preview via a local HTTP server if Python is installed:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## 📁 Project structure

```text
.
├── assets/           # Images, icons, and example resume PDF
├── index.html        # Portfolio page and content
├── style.css         # Main desktop styling
├── mediaqueries.css  # Responsive layout rules
└── script.js         # Hamburger menu toggle
```

## 🗺️ Roadmap/Notes

- The page currently contains template content such as “John Doe,” generic project entries, and placeholder social/contact destinations. Replace them before presenting it as a personal portfolio.
- `assets/resume-example.pdf` is an example document, not a verified personal CV.
- This is a static front-end project with no form-processing backend, automated tests, or build tooling.

## 👤 Author

**Brian Dol**, Senior Full Stack Engineer · [Portfolio](https://portfolio.briandol.workers.dev/) · [LinkedIn](https://linkedin.com/in/brian-dol-31a06115a/)
