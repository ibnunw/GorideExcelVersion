# Peta Pelanggan Kurir

Aplikasi web untuk penandaan lokasi pelanggan kurir di wilayah Tigaraksa Hub 2 dengan akurasi tinggi. Memungkinkan rider untuk menandai, mengelola, dan menganalisis lokasi pelanggan secara efisien.

[Tampilan Desktop](GorideExcellVersion.PNG)
[Tampilan Mobile](GorideExcellVersionMobile.PNG)

## Fitur Utama

✅ **Penandaan Lokasi Akurat**  
- Klik di peta untuk menempatkan marker sementara
- Drag marker untuk penempatan presisi
- Zoom maksimal untuk akurasi tinggi

🗺️ **Manajemen Data Pelanggan**  
- Tambah/edit/hapus data pelanggan
- Kategorikan berdasarkan jenis lokasi (rumah, kantor, toko)
- Simpan catatan penting untuk setiap pelanggan

📊 **Analisis Kawasan**  
- Deteksi otomatis pelanggan dalam/luar kawasan Hub 2
- Statistik real-time jumlah pelanggan
- Visualisasi area layanan dengan radius 1.5km

📥 **Import/Export Data**  
- Export data ke format Excel (.xlsx)
- Import data dari file Excel
- Backup data secara berkala

📍 **Fitur Peta Canggih**  
- Pencarian alamat dengan Nominatim OSM
- Mode layar penuh
- Kontrol zoom khusus
- Legenda visual

## Cara Penggunaan

1. **Pilih lokasi** di peta dengan mengklik area dekat pelanggan
2. **Drag marker ungu** untuk penempatan presisi
3. **Isi form** dengan detail pelanggan:
   - Nama pelanggan
   - Alamat lengkap
   - Jenis lokasi (rumah/kantor/toko)
   - Catatan penting
4. Klik **"Tambah Penanda"** untuk menyimpan
5. Gunakan fitur **Export Data** untuk backup berkala

Tips Akurasi:
- Gunakan zoom maksimal saat menandai lokasi
- Manfaatkan fitur drag marker untuk presisi
- Verifikasi lokasi dengan fitur pencarian alamat

## Teknologi

- **Leaflet JS** - Library peta interaktif
- **OpenStreetMap** - Data peta dasar
- **SheetJS (xlsx)** - Export/import data Excel
- **Font Awesome** - Ikon antarmuka
- **LocalStorage** - Penyimpanan data browser

## Instalasi

Tidak diperlukan instalasi! Aplikasi ini berjalan langsung di browser:

1. Clone repositori ini:
```bash
git clone https://github.com/ibnunw/GorideExcelVersion.git
```

2. Buka file `index.html` di browser modern

Atau gunakan langsung di:  
[Netlify](https://gorideexcellversion.netlify.app/)

## Kontribusi

Kontribusi diterima! Ikuti langkah berikut:

1. Fork proyek ini
2. Buat branch fitur baru (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -am 'Tambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](License).

---

**Catatan Penting**:  
Data disimpan secara lokal di browser pengguna. Lakukan export data secara berkala untuk mencegah kehilangan data saat cache browser dibersihkan.

Dikembangkan untuk mendukung operasional para kurir - © 2025
