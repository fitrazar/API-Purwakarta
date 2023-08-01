# API Data Kecamatan, Desa/Kelurahan di Purwakarta

#### API gratis untuk Data Kecamatan, Desa/Kelurahan di Purwakarta. Baru ada sekitar 74 data dari total 209 data kecamatan, desa/kelurahan.

<div align="center">
<a href="https://laravel.com"><img alt="Laravel" src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg"/></a>
</div>

# Penggunaan

BASE URL:
```bash
https://fitrazar.my.id/purwakarta/api
```
## Menampilkan seluruh kecamatan

```bash
/api/kecamatan
```

Contoh Response: 
```bash
[
  {
    "id": 13,
    "kode_wilayah": 321401,
    "nama": "Purwakarta",
    "slug": "purwakarta",
    "tentang": "Purwakarta adalah ibu kota Kabupaten Purwakarta yang sekaligus menjadi pusat pemerintahan dan perekonomian dari Kabupaten Purwakarta. Purwakarta juga merupakan sebuah wilayah kecamatan yang terletak di Kabupaten Purwakarta, Provinsi Jawa Barat, Indonesia.",
    "jumlah_kel": 9,
    "jumlah_des": 1,
    "lokasi": "https://goo.gl/maps/YoezGMoW515KbfuD9",
    "luas": "24,45 km2",
    "desas": [
        {
            "id": 48,
            "kecamatan_id": 13,
            "kode_wilayah": 3214012010,
            "nama": "Citalang",
            "slug": "citalang",
            "tentang": "Citalang adalah sebuah desa di kecamatan Purwakarta, Purwakarta, Jawa Barat, Indonesia.",
            "kode_pos": 41111,
            "lokasi": "https://goo.gl/maps/pRr83cnz47FjGkpTA",
        },
	....
    ],
    "kelurahans": []
  },
  {
    "id": 14,
    "kode_wilayah": 321415,
    "nama": "Sukasari",
    "slug": "sukasari",
    "tentang": "Sukasari adalah sebuah kecamatan di Kabupaten Purwakarta, Provinsi Jawa Barat, Indonesia. Kecamatan Sukasari merupakan kecamatan dengan jumlah penduduk paling sedikit di Kabupaten Purwakarta dan letaknya berada di ujung Barat dari Kabupaten Purwakarta tepatnya sepanjang pesisir Barat Waduk Jatiluhur. Kecamatan Sukasari berbatasan langsung dengan 3 Kabupaten yaitu di bagian barat adalah Kawasan Jonggol yang masuk Kabupaten Bogor, sebelah utara adalah kabupaten Karawang dan Kabupaten Cianjur di sisi selatan, sedangkan sebelah timur adalah Kecamatan Jatiluhur, Purwakarta.",
    "jumlah_kel": null,
    "jumlah_des": 5,
    "lokasi": "https://goo.gl/maps/zMDvA7YmTSwL6nwa6",
    "luas": "92.01 km",
    "desas": [],
    "kelurahans": []
  },
  ....
]
```

## Menampilkan kecamatan berdasarkan nama

```bash
/api/kecamatan/{kecamatan}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `{kecamatan}`      | `string` | nama kecamatan yang ingin dicari |

Contoh Response: 
```bash
[
  {
    "id": 13,
    "kode_wilayah": 321401,
    "nama": "Purwakarta",
    "slug": "purwakarta",
    "tentang": "Purwakarta adalah ibu kota Kabupaten Purwakarta yang sekaligus menjadi pusat pemerintahan dan perekonomian dari Kabupaten Purwakarta. Purwakarta juga merupakan sebuah wilayah kecamatan yang terletak di Kabupaten Purwakarta, Provinsi Jawa Barat, Indonesia.",
    "jumlah_kel": 9,
    "jumlah_des": 1,
    "lokasi": "https://goo.gl/maps/YoezGMoW515KbfuD9",
    "luas": "24,45 km2",
    "desas": [
        {
            "id": 48,
            "kecamatan_id": 13,
            "kode_wilayah": 3214012010,
            "nama": "Citalang",
            "slug": "citalang",
            "tentang": "Citalang adalah sebuah desa di kecamatan Purwakarta, Purwakarta, Jawa Barat, Indonesia.",
            "kode_pos": 41111,
            "lokasi": "https://goo.gl/maps/pRr83cnz47FjGkpTA",
        },
	....
    ],
   "kelurahans": []
  }
]
```

## Endpoint lainnya

| Endpoint  | Usage     | Example   |
| :-------- | :-------- | :-------- |
| menampilkan semua desa | `/api/desa` | - |
| menampilkan desa berdasarkan nama | `/api/desa/{desa}` | `/api/desa/ciawi` |
| menampilkan semua kelurahan | `/api/kelurahan` | - |
| menampilkan kelurahan berdasarkan nama | `/api/kelurahan/{kelurahan}` | `/api/kelurahan/nagri-kaler` |

### Gunakan free API ini dengan Bijak dan Benar ya :)
### Jika ada kesalahan pada API atau ingin meminta saran bisa hubungi email: fitra6751@gmail.com atau lewat issues pada repo ini.

Build With 💙
