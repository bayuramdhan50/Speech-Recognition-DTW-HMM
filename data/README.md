# Struktur Dataset Speech Recognition

## Cara Penggunaan

Masukkan file audio .wav Anda sesuai dengan struktur folder yang sudah disediakan:

```
data/
├── training/
│   ├── Dataset Bayu/
│   │   ├── gas/           ← Masukkan file audio "gas" di sini
│   │   ├── rem/           ← Masukkan file audio "rem" di sini
│   │   ├── belok/         ← Masukkan file audio "belok" di sini
│   │   ├── mundur/        ← Masukkan file audio "mundur" di sini
│   │   ├── nyalakan/      ← Masukkan file audio "nyalakan" di sini
│   │   └── matikan/       ← Masukkan file audio "matikan" di sini
│   └── Dataset Davney/
│       ├── gas/
│       ├── rem/
│       ├── belok/
│       ├── mundur/
│       ├── nyalakan/
│       └── matikan/
└── testing/
    ├── Dataset Bayu/
    │   ├── gas/
    │   ├── rem/
    │   ├── belok/
    │   ├── mundur/
    │   ├── nyalakan/
    │   └── matikan/
    └── Dataset Davney/
        ├── gas/
        ├── rem/
        ├── belok/
        ├── mundur/
        ├── nyalakan/
        └── matikan/
```

## Contoh Penamaan File

- `gas_001.wav`, `gas_002.wav`, dll.
- `rem_001.wav`, `rem_002.wav`, dll.
- Dan seterusnya untuk kata kunci lainnya

## Catatan

- File `.gitkeep` hanya untuk mempertahankan struktur folder di Git
- File audio tidak akan di-upload ke GitHub karena ukurannya besar
- Struktur folder sudah siap, tinggal masukkan file audio saja
