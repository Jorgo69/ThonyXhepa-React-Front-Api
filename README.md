# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


git config --global core.autocrlf true

This error message is Git's way of warning you that it's going to automatically change line endings in your files to match the expected format for your operating system. It's important to have consistent line endings in a project to avoid conflicts and unexpected behavior.

Configure Git to handle line endings correctly for your operating system by setting the core.autocrlf configuration option.
For Windows:
git config --global core.autocrlf true
For macOS/Linux:
git config --global core.autocrlf input
The "true" setting instructs Git to convert line endings to CRLF when checking out files and to LF when committing files.
In contrast, the "input" setting directs Git to convert line endings to LF during commits while preserving them as is during checkouts.

Hope this can help you!