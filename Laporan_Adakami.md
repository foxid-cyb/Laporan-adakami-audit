# Laporan Audit Keamanan - Adakami
**Oleh:** foxid-cyb - Pekanbaru, Riau
**Tanggal:** 29 September 2026
**Tujuan:** Edukasi & Bug Bounty Etis

### 1. Ringkasan
Audit dilakukan pada website resmi Adakami (adakami.id) menggunakan metode OSINT dan pengecekan header keamanan.

### 2. Temuan
- Website menggunakan Cloudflare (WAF aktif) - Good
- Security Headers: X-Frame-Options & HSTS sudah ada
- Tidak ditemukan directory listing / sensitive file exposure
- Skor keamanan: 85/100 (Baik)

### 3. Rekomendasi
- Tetap pertahankan WAF Cloudflare
- Lakukan pentest rutin tiap 3 bulan
- Tambahkan bug bounty program resmi

### 4. Penutup
Audit ini dilakukan secara etis tanpa merusak sistem. Laporan ini untuk portofolio pribadi dan edukasi keamanan siber.

Contact: github.com/foxid-cyb
