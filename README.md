# Hugo + Tailwind CSS + Alpine.js Starter Template

[![Hugo](https://img.shields.io/badge/Hugo-%5E0.150-blueviolet?logo=hugo)](https://gohugo.io/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-%5E4.0-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Alpine.js](https://img.shields.io/badge/Alpine.js-%5E3.15-77C1D2?logo=javascript)](https://alpinejs.dev/)

A minimal starter template for quickly building modern, fast, and responsive websites with:

- ⚡ **[Hugo](https://gohugo.io/):** static site generator
- 🎨 **[Tailwind CSS](https://tailwindcss.com/):** utility-first styling
- ✨ **[Alpine.js](https://alpinejs.dev/):** lightweight interactivity

This template is designed to give you a smooth developer experience with **separate configs for development and production**, so you can easily customize and deploy.

---

## 🚀 Features

- Hugo asset pipeline with **Hugo Pipes**
- **Tailwind CSS** for styling
- **Alpine.js** pre-configured for interactivity
- `config/_default` for shared config
- `config/development` and `config/production` overrides
- Fingerprinted and minified assets in production
- Ready-to-use partials for JS and CSS includes

---

## 📂 Config Structure
This template utilizes Hugo's powerful config directory to manage settings for different environments.

```
config/
├── _default/         # Base configuration loaded for all environments
│   ├── hugo.toml
│   ├── markup.toml
│   ├── languages.toml
│   ├── menus.toml
│   └── params.toml
│
├── development/      # Loaded only when running `hugo server` (`npm run dev`)
│   └── hugo.toml     # The port (23001) is set here!
│
└── production/       # Loaded only when running `hugo` (`npm run build`)
    └── hugo.toml
```
---

## 🛠️ Setup
You can either clone this repository or click the "Use this template" button on GitHub.

The following commands will spin up your local environment for development

```bash
npm install # install dependencies
npm run dev # to start the server locally
```

This command will:

- Start the Hugo development server on port 23001.
- Watch for changes in your content, templates, and asset files.
- Use the --ignoreCache flag to prevent issues with stale data.
- Enable buildDrafts so you can preview your draft posts.
- Automatically reload your browser when changes are detected.

---

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
