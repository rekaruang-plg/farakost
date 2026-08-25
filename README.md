# Fara Kost V1 Production

Landing page + sistem operasional Fara Kost yang terhubung ke Supabase.

## Production stack
- Static web app, responsive desktop/mobile
- Supabase Database + Auth + Row Level Security
- Vercel hosting
- Zona waktu operasional: Asia/Jakarta (WIB)

## Fitur
- 3 tipe kamar / 5 unit aktual
- Foto kamar asli AC dan kipas
- Availability berdasarkan tanggal + jam
- Booking publik dengan validasi database
- Login owner/staff
- Walk-in check-in
- Checkout otomatis = check-in aktual + kelipatan 24 jam
- Konfirmasi booking + penguncian unit
- Extend stay dengan pengecekan konflik booking
- Checkout → cleaning → kamar siap kembali
- Maintenance kamar
- Pembayaran cash / transfer / QRIS / belum bayar
- Tamu, transaksi, laporan, dan tarif kamar
- Mobile bottom navigation dan desktop Live Room Board

## Database
Project Supabase: Fara Kost
Schema production menggunakan RLS dan RPC untuk operasi yang sensitif/concurrent.

## Setup owner pertama
Buka `#admin`, buat akun owner pertama, konfirmasi email jika diminta, lalu masukkan kode aktivasi owner yang diberikan pada saat deployment.
