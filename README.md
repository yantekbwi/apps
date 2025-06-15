Video preview : https://youtu.be/5pKtFrxjyzI

Aplikasi Web Apps ini dibuat dengan :
A. Google Apps Script
B. Google Sheet (database)

A. Google Apps Script
Dikarenakan keterbatasan pada Google Apps Script yang tidak bisa menangani reload page (terbatas), maka aplikasi prototype ini dibangun dengan metode  Single Page Apps (SPA) sehingga page yang saya sebut sebagai module (multipage) dan tentunya seluruh proses terhadap interaksi user tanpa reload page ini mampu ditangani.

B. Google Sheet
Saya menggunakan Google Sheet sebagai database, dari video dapat dipastikan saya menggunakan banyak file (16) untuk menghandle tiap module.

Library Eksternal
Library yang saya gunakan : 
Tailwind CSS : Layout
sweetAlert : Loading, popup
Lucide icons : Icon
Leaflet (JS+CSS) : OpenStreetMap+marker
Chart.js : Chart
html2canvas : Camera & Compress image
jspdf : save to Pdf

Module : 
1. SMPT : Sistem Manajemen Pesan (berkirim pesan antar user)
2. SMAP : Sistem Absensi Pegawai (Absensi Selfi, koordinat, tolerance)
3. SMPP : Sistem Manajemen Performa Pegawai (KPI)
4. SIGar : Sistem Informasi Gardu (Asset & Pemeliharaan, masih plan)
5. SiTM : Sistem Tegangan Menengah (sama dengan SIGar, masih plan)
6. SiHarJar : Sistem Pemeliharaan Jaringan (khusus, masih plan)
7. SIMAK : Sistem Manajemen Kepegawaian (Asset, Payroll)
8. SMS : Sistem Manajemen Surat (Templating, masih plan)
9. SIAK : Sistem Inventaris Alat Kerja (Kondisi, Umur)
10. SIAJar : Sistem Asset Jaringan (Asset Jaringan)
11. SiOpJar : Sistem Operasi Jaringan (RPT/RCT, Anomali, SE004)
12. SIMAT : Sistem Materi Baca (Perpustakaan)
13. SiLapOr : Sistem Laporan Operasional (Keuangan, Petty cash)
14. SIVA : Sistem Visitor Analytic (Logging)
15. FGTM : Frekuensi Gangguan TM (Logbook, Recap, Graph)
16. MODAR : Monitoring Kendaraan (Asset, Surat, Service)
 
User Role 
1. Superadmin (all page master, read, upload, edit, add, delete )
2. Admin (all page, read, upload, edit)
3. SPV, Koordinator (unit page, read, add)
4. Petugas (unit page, read, add)

~salam Hariyo

google.script.run, init()
====================================
#google #googleappscript #googlesheets #googlesearch #webapp #tailwindcss #lucide #icon  #sweetalert #leaflet #jspdf #html #javascript #chart #analytics #programming #app #upload #printing #yantek
