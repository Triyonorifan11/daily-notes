# Daily Notes

Catatan pekerjaan harian sebagai rekam jejak aktivitas pengembangan: apa yang dikerjakan, di project mana, dan statusnya.

## Struktur Folder

```
daily-notes/
├── README.md
├── templates/
│   └── daily-template.md
└── YYYY/
    └── MM/
        └── YYYY-MM-DD.md
```

- Satu file per hari kerja, dengan nama `YYYY-MM-DD.md`.
- File dikelompokkan per tahun, lalu per bulan.
- Template catatan ada di [`templates/daily-template.md`](templates/daily-template.md).

## Format Catatan

Setiap catatan harian berisi:

1. **Nama project** yang dikerjakan hari itu.
2. **Ringkasan** satu kalimat.
3. **Daftar pekerjaan** yang dilakukan.
4. **Status/Catatan**: bagian yang belum selesai, kendala, atau rencana lanjutan.

## Cara Menambah Catatan Baru

1. Buat folder tahun/bulan jika belum ada, misalnya `2026/12/`.
2. Salin `templates/daily-template.md` ke `YYYY/MM/YYYY-MM-DD.md`.
3. Isi catatan, lalu commit dengan pesan seperti `notes: 2026-12-01`.

## Indeks

### 2026
- [November 2026](2026/11/)
  - [2026-11-23](2026/11/2026-11-23.md)

## Catatan

- Catatan ditulis dalam Bahasa Indonesia.
- Repo ini publik. Jangan menulis kredensial, token, isi `.env`, data pribadi, atau detail internal yang sensitif.
