
# 📄 Contoh Format Pengisian Form dalam JSON

Dokumen ini berisi contoh struktur JSON untuk pengisian form undangan pernikahan, terdiri dari dua tipe input:

- **Text Input** (`type: "text"`)
- **File Input** (`type: "file"`)

---

## 📝 Contoh Form Tipe Text

Form ini digunakan untuk mengisi data teks seperti nama pengantin, nama orang tua, dan lain-lain.

```json
{
  "Data Pengantin Pria": [
    {
      "name": "Nama Panggilan Pengantin Pria",
      "param": "nama_panggilan_pengantin_pria",
      "type": "text",
      "placeholder": "Ex : Dimas",
      "value": "Dimas"
    },
    {
      "name": "Nama Pengantin Pria",
      "param": "nama_pengantin_pria",
      "type": "text",
      "placeholder": "Ex : Shafa Dimas",
      "value": "Shafa Dimas Saputra"
    },
    {
      "name": "Nama Bapak Pengantin Pria",
      "param": "nama_bapak_pengantin_pria",
      "type": "text",
      "placeholder": "Ex : Sandy Sena, SE",
      "value": "Sandy Sena, SE"
    },
    {
      "name": "Nama Ibu Pengantin Pria",
      "param": "nama_ibu_pengantin_pria",
      "type": "text",
      "placeholder": "Ex : Fenty, SE",
      "value": "Fenty, SE"
    }
  ]
}
```

---

## 🖼️ Contoh Form Tipe File

Form ini digunakan untuk mengunggah file gambar seperti foto sampul dan galeri.

```json
{
  "Data Gallery": [
    {
      "name": "Foto Sampul depan",
      "param": "foto_sampul_depan",
      "value": "https://undangan.jadimudah.id/public/example/foto-cover-1.jpg",
      "type": "file"
    },
    {
      "name": "Gallery 1",
      "param": "gallery_1",
      "value": "https://undangan.jadimudah.id/public/example/foto-berdua-3.jpg",
      "type": "file"
    },
    {
      "name": "Gallery 2",
      "param": "gallery_2",
      "value": "https://undangan.jadimudah.id/public/example/foto-berdua-2.jpg",
      "type": "file"
    },
    {
      "name": "Gallery 3",
      "param": "gallery_3",
      "value": "https://undangan.jadimudah.id/public/example/foto-dekstop-5.jpg",
      "type": "file"
    }
  ]
}
```
# 📄 Contoh Format Pengisian Form Tipe Textarea dalam JSON

Dokumen ini berisi contoh struktur JSON untuk form yang menggunakan **textarea** sebagai input, cocok digunakan untuk isian teks panjang seperti ucapan, doa, atau deskripsi tambahan.

---

## ✏️ Contoh Form Tipe Textarea

```json
{
  "Ucapan dan Doa": [
    {
      "name": "Ucapan atau Doa",
      "param": "ucapan_doa",
      "type": "textarea",
      "placeholder": "Tuliskan ucapan atau doa Anda untuk kedua mempelai...",
      "value": "Selamat menempuh hidup baru! Semoga menjadi keluarga yang sakinah, mawaddah, warahmah."
    },
    {
      "name": "Pesan untuk Tuan Rumah",
      "param": "pesan_tuan_rumah",
      "type": "textarea",
      "placeholder": "Berikan pesan untuk tuan rumah atau panitia...",
      "value": ""
    }
  ]
}
```

# 📄 Contoh Format Pengisian Form Tipe Checkbox dalam JSON

Checkbox digunakan untuk input **opsional boolean** (ya/tidak, aktif/nonaktif). Biasanya digunakan untuk mengaktifkan fitur tertentu atau memilih opsi.

---

## ☑️ Contoh Form Tipe Checkbox

```json
{
  "Pengaturan Fitur": [
    {
      "name": "Pakai Fitur Gift?",
      "param": "fitur_gift",
      "type": "checkbox",
      "value": true
    },
    {
      "name": "Tampilkan Musik?",
      "param": "fitur_musik",
      "type": "checkbox",
      "value": false
    },
    {
      "name": "Aktifkan Komentar Tamu?",
      "param": "fitur_komentar",
      "type": "checkbox",
      "value": true
    }
  ]
}
