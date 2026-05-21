# The Stable Manager Clean Repo

Clean Vite/React/Supabase deployment package.

Important:
- Do not upload package-lock.json.
- Add these Vercel environment variables:
  - VITE_SUPABASE_URL
  - VITE_SUPABASE_ANON_KEY
- Vercel settings:
  - Framework: Vite
  - Install Command: npm install
  - Build Command: npm run build
  - Output Directory: dist
  - Node.js: 20.x
