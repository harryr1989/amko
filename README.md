# AMKO Pages Starter

Tiga halaman aktif: `login.html`, `dashboard.html`, `master-saldo-akun.html`.
Dites untuk deploy di **GitHub Pages**.

## Struktur
```
/amko-pages-starter
  login.html
  dashboard.html
  master-saldo-akun.html
  index.html        (redirect ke login)
  404.html          (fallback ke login)
  .nojekyll
```

## Publikasi ke GitHub Pages (ringkas)
1. Buat repo baru di GitHub, misal `amko-pages`.
2. Unggah semua file/folder ini ke root repo.
3. Settings → Pages → Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)`.
4. Buka `https://<username>.github.io/amko-pages/`.
5. Pastikan URL ini ditambahkan di **Supabase → Authentication → URL configuration** (Site URL / Redirect URLs).

Dibuat otomatis: 2025-09-16T12:34:23.841107
