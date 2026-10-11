# fae.web.id

Portal resmi dan repositori hosting GitHub Pages untuk domain **fae.web.id**.

## Fitur & Arsitektur
- **Clean Static Web**: HTML5 semantik, CSS responsif murni tanpa runtime berat, zero dependency.
- **Dark/Light Mode**: Mendukung peralihan tema otomatis dan persistensi lokal.
- **Ekosistem Subdomain**: Direktori rujukan simpul jaringan (KSU Lidia ERP, API Gateway, Node Status).
- **Custom Domain & SSL**: Terhubung ke apex `fae.web.id` via GitHub Pages CDN dengan dukungan HTTPS.

## Deployment
Setiap perubahan pada branch `main` secara otomatis dideploy ke GitHub Pages via GitHub Actions workflow (`.github/workflows/deploy.yml`).

---
Part of **WanForge & Docobyte Ecosystem**.
