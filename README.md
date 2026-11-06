# MusicStream — React + Vite

## Run locally
1. Install Node.js 20.19+ (or 22.12+).
2. Open this folder in VS Code.
3. In terminal run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the localhost URL Vite prints.

## Deploy to Vercel
1. Push this project to a GitHub repository.
2. In Vercel choose **Add New → Project** and import the repository.
3. Framework preset: **Vite**; Build command: `npm run build`; Output directory: `dist`.
4. Click Deploy.

## Demo Admin
Email: `admin@music.com`
Password: `admin123`

## Notes
This React + Vite wrapper preserves the original app's existing DOM-driven interface and JavaScript behavior. Login/signup, admin/user screens and app data use the existing Local Storage implementation. Audio requires valid audio file URLs/paths. Download behavior in the original app is a simulation, not cloud/offline streaming.
