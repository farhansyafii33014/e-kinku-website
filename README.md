# Website resmi E-KinKu

Website statis ini berisi:
- `index.html` — homepage E-KinKu
- `privacy-policy.html` — kebijakan privasi
- `styles.css` — tampilan responsif

## Sebelum dipublikasikan
1. Pastikan email kontak `farhansyafii33014@gmail.com` benar dan dapat menerima pesan.
2. Tinjau isi Privacy Policy agar sesuai dengan praktik aplikasi yang sebenarnya.
3. Pastikan khususnya pengaturan berbagi file Google Drive dan prosedur penghapusan data sudah akurat.

## Publikasi Cloudflare Pages melalui GitHub
1. Buat repository GitHub baru, misalnya `e-kinku-website`.
2. Unggah seluruh isi folder ini ke root repository (bukan folder luarnya).
3. Masuk Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
4. Hubungkan GitHub dan pilih repository `e-kinku-website`.
5. Framework preset: `None`.
6. Build command: kosongkan.
7. Build output directory: `/` (atau `.` jika UI meminta path relatif).
8. Klik Save and Deploy.
9. Setelah berhasil, Cloudflare memberikan alamat `https://NAMA-PROYEK.pages.dev`.

## URL untuk Google OAuth Branding
- Homepage: `https://NAMA-PROYEK.pages.dev/`
- Privacy Policy: `https://NAMA-PROYEK.pages.dev/privacy-policy.html`

Catatan: Google dapat meminta domain terverifikasi untuk OAuth branding / authorized domains. Subdomain pages.dev adalah subdomain milik Cloudflare, bukan domain kustom milik Anda. Verifikasi dan penerimaan URL ini oleh Google harus diperiksa pada Google Auth Platform; jangan menganggap publikasi Pages otomatis menyelesaikan verifikasi OAuth.
