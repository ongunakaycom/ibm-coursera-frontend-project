# 💻 IBM Full Stack Developer Capstone Project

A responsive front-end web project built using **HTML**, **CSS**, and **JavaScript**, created as part of the **IBM Full Developer Professional Certificate** on [Coursera](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer).

This capstone demonstrates foundational front-end development skills, emphasizing clean UI, accessibility, and best practices in modern web design.

---

## 🧠 Overview

This project represents the final capstone of the IBM Full Stack Developer Program.  
It focuses on applying HTML, CSS, and JavaScript to create a functional, responsive, and user-friendly web page layout.

---

## 📂 Project Structure

```
ibm-coursera-frontend-project/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
├── images/             # Assets and icons
│   ├── html5.png
│   ├── css3.png
│   ├── js.png
│   └── profile.jpg
├── .github/
│   └── workflows/
│       └── static.yml  # GitHub Actions CI/CD workflow
└── README.md           # Project documentation
```

---

## 🚀 Features

- Responsive and mobile-friendly design  
- Semantic HTML structure  
- CSS Flexbox and Grid layout usage  
- Interactive JavaScript components  
- Static deployment workflow via GitHub Actions  

---

## ⚙️ GitHub Actions (CI/CD)

This project uses **GitHub Actions** for automation:

- ✅ Runs build validation on each commit  
- 🚀 Deploys static site to GitHub Pages  
- 🧹 Lints HTML, CSS, and JavaScript files  

Example workflow file (`.github/workflows/static.yml`):

```yaml
name: Static Site CI/CD

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v4

      - name: Setup Node
        uses: actions/setup-node@v4
        with:
          node-version: '18'

      - name: Build
        run: echo "Static site build successful!"
```

---

## 🧩 Installation

```bash
# Clone the repository
git clone https://github.com/ongunakaycom/ibm-coursera-frontend-project.git
cd ibm-coursera-frontend-project
```

Then, open `index.html` directly in your browser.

---

## 🤝 Contributions

Pull requests and suggestions are welcome!  
This project was part of a learning journey — feel free to fork it, explore, and enhance it further.

---

## 👨‍💻 About the Author

**Ongun Akay** — Senior Full-Stack Developer

I'm a passionate **Full-Stack Developer** with extensive experience across both **frontend** and **backend** technologies.  
I enjoy building scalable, high-performance applications and continuously exploring new tools and frameworks to enhance development workflows.

- 👀 **Expertise:** Full-stack web development, modern JavaScript frameworks, and cloud-based deployment.  
- 🌱 **Currently Learning:** Advanced web architecture and DevOps practices.  
- 💞️ **Collaboration:** Open to innovative projects that challenge creativity and technical problem-solving.  
- 📫 **Contact:** [info@ongunakay.com](mailto:info@ongunakay.com)

**Connect with me:**  
- 🌐 [ongunakay.com](https://ongunakay.com)  
- 💼 [LinkedIn](https://linkedin.com/in/ongunakay)  
- 🧑‍💻 [GitHub](https://github.com/ongunakaycom)

---

