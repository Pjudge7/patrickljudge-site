import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

// For GitHub Pages project URLs, set VITE_BASE_PATH to /repo-name/ in repository Actions variables.
// For a custom domain or Netlify, leave it as '/'.
export default defineConfig({
  plugins: [react()],
  base: process.env.VITE_BASE_PATH || '/',
});
