# DevBlog Angular ✨

[![GitHub Pages](https://img.shields.io/badge/View-Live%20Demo-brightgreen?style=flat-square)](https://bsmart-123.github.io/devblog-angular)
[![image](https://github.com/user-attachments/assets/2cf5476f-923e-4adc-926a-a816133e1b9a)


A personal developer blog built with **Angular 19**, designed to share coding insights, tutorials, and tech adventures with the world.

<p align="center">
  <img src="https://placehold.co/600x400?text=Blog+Screenshot" alt="Preview" width="70%">
</p>

## 🌟 Features

- **Modern Angular architecture** (v19 with SSR support)
- **Responsive design** - Looks great on phones, tablets, and desktops
- **Easy content updates** - Just modify and redeploy
- **Blazing fast** - Optimized static site delivery via GitHub Pages

## 🚀 Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/Bsmart-123/devblog-angular.git
   cd devblog-angular
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run locally**
   ```bash
   ng serve
   ```
   Open `http://localhost:4200` in your browser

4. **Deploy to GitHub Pages**
   ```bash
   ng build --configuration production
   npx angular-cli-ghpages --dir=dist/codecrafters-blog/browser
   ```

## 🛠️ Project Structure

```
src/
├── app/               # Angular components
├── assets/            # Images, styles
├── environments/      # Build configs
dist/
└── codecrafters-blog/ # Production build
    └── browser/       # Static files for GitHub Pages
```

## 🤔 Why I Built This

As a developer:
- To document my learning journey
- To experiment with Angular's latest features
- To create a personalized space for sharing knowledge
- To understand CI/CD with GitHub Pages

## 📜 License

MIT © [Benaiah Smart](https://github.com/Bsmart-123)

---

**Like this project?** ⭐ Star it on GitHub — and share your thoughts in the issues!
