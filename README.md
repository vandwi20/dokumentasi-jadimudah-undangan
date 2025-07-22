
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

---

## 📌 Keterangan

| Property     | Deskripsi                                                |
|--------------|----------------------------------------------------------|
| `name`       | Label yang ditampilkan di form                           |
| `param`      | Nama parameter yang digunakan di backend                 |
| `type`       | Jenis input (`text` atau `file`)                         |
| `placeholder`| Teks petunjuk (khusus untuk input `text`)               |
| `value`      | Nilai awal yang akan diisi ke dalam input                |

---

> 💡 Anda bisa mengembangkan struktur ini untuk data lainnya seperti pengantin wanita, lokasi acara, video gallery, dll.
