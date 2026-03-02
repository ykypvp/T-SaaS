# T-SaaS Panel

A dynamic dashboard driven by Markdown. No compilation or complex setup required.

Currently, T-SaaS is in ALPHA version, so it MAY contain errors.

Test the project in english: https://ykypvp.github.io/T-SaaS/

Teste o projeto em português: https://tsaasproject.vercel.app/
---

## Overview

T-SaaS is a lightweight administrative interface designed for efficiency. It operates by loading configurations and layouts directly from a `config.md` file.

### Key Features
* Direct Editing: Modifications to `config.md` update the dashboard immediately.
* Zero Setup: No requirement for Node.js, NPM, or external installers.
* Flexible Hosting: Compatible with GitHub Pages, Vercel, or local environments.

---
## Getting Started

To deploy the dashboard locally, follow these steps:

1. Clone the repository:
   `git clone https://github.com/ykypvp/T-SaaS.git`

2. Launch the dashboard:
   Open the `index.html` file in any modern web browser.

3. Customization:
   Edit the `config.md` file to modify menus, content, and interactive elements.

---
## Deployment via Vercel (optional)

If you prefer to host your dashboard online using Vercel, follow these instructions:

1. Push your repository to GitHub.
2. Connect your GitHub account to the Vercel Dashboard.
3. Import the `T-SaaS` repository.
4. Vercel will automatically detect the `index.html` and deploy it as a static site.

Alternatively, using Vercel CLI:`
<p>Install dependencies</p>

`npm install`

`npx vercel`
<p>If you've already uploaded to Vercel and want to perform a full project deployment, run:</p>

`npx vercel --prod`

---

## Project Structure

* index.html: The core engine that renders the interface.
* config.md: The primary configuration file for defining the SaaS structure.

---
## Support the Project

If you find T-SaaS useful, consider supporting its continuous development through GitHub Sponsors.

[BECOME A SPONSOR ON GITHUB](https://github.com/sponsors/ykypvp)

---

## License

Please refer to the LICENSE.txt file for detailed terms of use.

---
Developed by [ykypvp](https://github.com/ykypvp)
