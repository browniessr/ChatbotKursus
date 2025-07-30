CHATBOT KURSUS

Chatbot Kursus adalah chatbot berbasis Python yang dirancang untuk menjawab pertanyaan seputar kursus atau pelatihan IT. 
Chatbot ini menggunakan pendekatan klasifikasi intent dan fallback response untuk menangani input dari pengguna.

Fitur Utama
- Klasifikasi intent menggunakan model IndoBERT
- Respon fallback jika intent tidak dikenali
- Dukungan multi-intent (via DST - Dialog State Tracking)
- Konfigurasi jawaban berbasis file JSON

Struktur Proyek
├── data/ # Dataset pelatihan dan testing
├── answer.json # File respons berdasarkan intent
├── indobert_newest_label.json # Label intent untuk model IndoBERT
├── main.py # Script utama chatbot
├── main_w_dst.py # Versi dengan dialog state tracking
├── dst.py # Modul dialog state tracking
├── fallback.py # Modul untuk menangani fallback intent
├── normalizer.py # Modul preprocessing teks
├── requirements.txt # Daftar dependensi Python
└── README.md # Dokumentasi proyek
