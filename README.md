# 🤖 n8n Chatbot Aspirasi Mahasiswa

**AspirasiBot** adalah chatbot berbasis **n8n** yang membantu mahasiswa menyampaikan aspirasi, keluhan, dan saran terkait kampus.

## 🔄 Workflow

```text
Chat Trigger → AI Agent → Response
                  ↕
             Simple Memory
                  ↓
          Google Gemini Model
```

### Fitur

* Menampung aspirasi dan keluhan mahasiswa.
* Mengumpulkan nama, NIM, program studi, kategori, dan uraian aspirasi.
* Mendukung kategori:

  * Fasilitas Kampus
  * Akademik & Perkuliahan
  * Beasiswa & Keuangan
  * Ormawa & Kegiatan Mahasiswa
* Mengonfirmasi aspirasi sebelum diteruskan ke Tim Aspirasi Kampus.
* Menggunakan Simple Memory untuk menjaga konteks percakapan.

## 🛠️ Teknologi

* **n8n**
* **AI Agent**
* **Google Gemini**
* **Simple Memory**

## 📁 File

```text
n8n-chatbot-aspirasi/
├── README.md
└── My workflow 5.json
```

## 🚀 Cara Menggunakan

1. Import `My workflow 5.json` ke n8n.
2. Konfigurasikan credential Google Gemini.
3. Pastikan seluruh node sudah terhubung.
4. Jalankan chatbot melalui Chat Trigger.

> Project ini dibuat untuk keperluan pembelajaran dan pengembangan workflow chatbot menggunakan n8n.
