# CVE-2025 - Classroombookings Stored Cross Site Scripting (XSS) pada halaman sesi pembuatan dan pengeditan melalui Dasbor Administrator

**Proyek yang Terkena Dampak**: classroombookings

**Situs web resmi**:  https://www.classroombookings.com/

**Versi**: 2.9.8

**Versi tetap**: 

**Titik Akhir yang Terpengaruh**:  https://site/sessions

**Paramete yang terpengaruhr**: N/A

## Demonstrasi

Step 1: Tempatkan muatan XSS pada bidang nama sesi dan simpan (Administrator)
![image](https://github.com/user-attachments/assets/0584886d-cb13-4090-8873-1fa05635d2b9)


Step 2: Memicu XSS dengan mengunjungi halaman pemesanan sebagai pengguna biasa atau administrator
![image](https://github.com/user-attachments/assets/713c9586-d4a8-4709-a42b-06daafeb9e31)



Disclaimer:  Pengembang atau pengelola proyek ini telah diberitahu tentang kerentanan ini melalui laporan ini.
