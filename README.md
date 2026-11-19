# Portofolio Tri Jaya Prasetya

Portofolio ini adalah satu halaman HTML statis dengan tema terang sebagai default dan tombol untuk beralih ke tema gelap. Pilihan tema disimpan di browser. Tailwind CSS 4 dimuat dari CDN di `index.html`; tidak perlu memasang Node.js, npm, atau menjalankan proses build.

## Pratinjau

Buka `index.html` di browser. Koneksi internet diperlukan agar Tailwind CSS dimuat dari CDN.

## Publikasi ke GitHub Pages

Workflow `.github/workflows/pages.yml` menerbitkan `index.html` ketika ada push ke branch `main` atau `master`. Di pengaturan repository, pilih **Settings → Pages → Build and deployment → GitHub Actions**.

Untuk memperbarui profil, edit konten langsung di `index.html`.
