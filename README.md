# aboutme-v2

Personal portfolio built with React + Vite + Tailwind CSS. Fully static and deployable to GitHub Pages.

Deployment (GitHub Pages)

// To deploy using gh-pages package:
// 1. npm run predeploy
// 2. npm run deploy

// Or build and push the dist/ folder to a gh-pages branch or configure GitHub Pages to serve from the 'dist' folder.

Important notes:
- Ensure vite.config.js `base` is set to your repo name (e.g., '/aboutme-v2/') or set BASE_URL env var when building:
  BASE_URL=/your-repo-name/ npm run build
- Assets and images should be placed in the `/public` folder and referenced using `${import.meta.env.BASE_URL}your-image.png` to work on GitHub Pages.
- Theme preference (light/dark) is persisted in localStorage.

TODOs:
- Update src/components/Sidebar.jsx with your profile image, name, title, description, email, location, and social links.
- Update skills and experience data in src/components/Skills.jsx and src/components/Experience.jsx.

Built files are output to `dist/` after `npm run build`.
