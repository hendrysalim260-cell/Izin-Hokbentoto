Dashboard Izin HOKBENTOTO

Isi file sudah disesuaikan untuk situs HOKBENTOTO:
- Branding BANDAR80 diganti menjadi HOKBENTOTO
- Logo utama memakai attached_assets/hokbentoto_logo.png
- Favicon memakai client/public/favicon.png
- Perbaikan durasi izin dan permission ikut dibawa dari versi fixed

Render deploy setting:
Build Command: npm install --include=dev && npm run build
Start Command: npm start

Environment Variables contoh:
MONGODB_URI=mongodb+srv://USER:PASSWORD@cluster0.xxxxx.mongodb.net/hokbentoto?retryWrites=true&w=majority&appName=Cluster0
SESSION_SECRET=dashboard-hokbentoto-secret-2026
NODE_ENV=production
