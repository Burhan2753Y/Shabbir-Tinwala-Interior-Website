# Shabbir Tinwala Interior Design Portfolio

A professional, high-impact freelance interior design portfolio website built for Shabbir Tinwala. The site features a modern, conversion-oriented design tailored to showcase expertise, design processes, and aesthetic vision.

## 🚀 About the Project

This website is designed with a focus on visual excellence, performance, and user experience. It serves as a digital storefront for interior design services, structured across core pages:
- **Home**: A visually engaging landing page designed for conversion and strong first impressions.
- **Spaces (Portfolio)**: A project-agnostic gallery to highlight distinct design styles and completed spaces. Includes a global lightbox feature for full-screen image viewing.
- **Work With Me**: A streamlined process and contact page to facilitate client inquiries and outline available services.

## 💻 Tech Stack

- **Framework**: [Astro](https://astro.build/) (v6) - for blazing-fast performance and component-based architecture.
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (v4) - for rapid, utility-first UI development and responsive layouts.

## 📦 Dependencies

Ensure you have the following installed on your system:
- **Node.js**: Version `>=22.12.0`
- **npm** (or your preferred package manager)

Key project dependencies (refer to `package.json` for details):
- `astro`
- `tailwindcss`
- `@tailwindcss/vite`

## 🛠️ How to Get Started

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd Shabbir-Tinwala-Interior-Website
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   ```

4. **Preview the site:**
   Open your browser and navigate to `http://localhost:4321`.

## 🧞 Available Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## 📁 Project Structure

```text
/
├── public/           # Static assets (images, icons, etc.)
├── src/
│   ├── layouts/      # Global layouts (e.g., Layout.astro)
│   ├── pages/        # Route pages (index.astro, spaces.astro, work-with-me.astro)
│   └── styles/       # Global CSS (e.g., global.css)
├── astro.config.mjs  # Astro configuration
├── package.json      # Project metadata and scripts
└── tsconfig.json     # TypeScript configuration
```
