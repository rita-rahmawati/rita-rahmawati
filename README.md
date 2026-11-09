# Hai, saya Rita 👋

Saya mahasiswa S1 Informatika semester akhir di Universitas AMIKOM Yogyakarta. Dua bidang yang paling saya tekuni adalah **data** (pengolahan data, machine learning, dan big data) dan **web development**. Sejak September 2025 saya juga menjadi asisten praktikum untuk Sistem Basis Data, Sistem Operasi, serta Hardware & Software, jadi saya terbiasa menjelaskan konsep teknis ke puluhan mahasiswa sekaligus.

Saat ini saya mengarah ke karir sebagai **Data Engineer**, dan terbuka untuk posisi magang maupun junior di bidang data atau web development.

## Tentang saya
- 🎓 S1 Informatika, Universitas AMIKOM Yogyakarta (2023 – 2027)
- 👩‍🏫 Asisten Praktikum: Sistem Basis Data, Sistem Operasi, Hardware & Software
- 📍 Yogyakarta, Indonesia
- 🎯 Fokus: Data Engineering & Web Development

## Keahlian
- **Data & AI:** Python, SQL, PySpark, LightGBM, Optuna, SHAP, LangGraph, RAG
- **Database:** MySQL, Oracle
- **Web:** PHP, Laravel, Blade, Tailwind CSS, REST API
- **Tools:** Google Colab, VS Code, Laragon, Git & GitHub

## Proyek pilihan

### 1. ServiceMate: [`servicemate`](https://github.com/rita-rahmawati/servicemate)
- **Masalah:** pemilik kendaraan sering lupa jadwal servis dan tidak punya catatan riwayat perawatan.
- **Yang saya buat:** aplikasi web berbasis Laravel dengan dashboard untuk menambah kendaraan dan jadwal servis, pengingat, riwayat servis, serta peta bengkel terdekat. Ada juga dashboard admin/CMS supaya situs bisa diubah tanpa menulis kode.
- **Demo:** [servicemate.online](https://servicemate.online/)
- **Stack:** PHP, Laravel, Blade, MySQL

### 2. Deteksi URL Phishing: [`project-phishing`](https://github.com/rita-rahmawati/project-phishing)
- **Masalah:** link phishing susah dibedakan dari link asli, apalagi kalau hanya dilihat sekilas.
- **Yang saya buat:** pipeline lengkap dari data mentah sampai layanan yang bisa dipakai. Model LightGBM dilatih pada dataset PhiUSIIL (235.795 URL, 21 fitur), hyperparameter-nya dituning dengan Optuna, dan keputusannya dijelaskan dengan SHAP. Modelnya disajikan lewat FastAPI dalam container Docker di Hugging Face Space, dengan pelacakan eksperimen memakai MLflow di DagsHub.
- **Hasil:** akurasi 99,76%, F1-score 99,79%, MCC 99,50%. Fitur yang paling berpengaruh: `IsHTTPS`, `DomainLength`, dan `LetterRatioInURL`.
- **Demo:** [phishing-detection di Hugging Face](https://huggingface.co/spaces/Rita1712/phishing-detection)
- **Stack:** Python, LightGBM, Optuna, SHAP, FastAPI, Docker, MLflow

### 3. Analisis dan Prediksi Big Data: [`UAS-BDL`](https://github.com/rita-rahmawati/23.11.5641_Rita-Rahmawati_UAS-BDL)
- **Deskripsi:** proyek analisis dan prediksi menggunakan PySpark dan algoritma machine learning berbasis big data. Proyek ini melatih saya memproses data berskala besar secara terdistribusi, bukan hanya dengan pandas di satu mesin.
- **Stack:** PySpark, Machine Learning, Jupyter Notebook

### 4. Perencana Ruangan Multi-Agent: [`UAS-PDM-Room-Planner`](https://github.com/rita-rahmawati/UAS-PDM-Room-Planner)
- **Masalah:** merancang tata letak ruangan butuh banyak pertimbangan sekaligus.
- **Yang kami buat:** proyek kelompok berupa sistem multi-agent dengan LangGraph dan Groq, memakai arsitektur fan-out/fan-in antar agen. Hasilnya divisualisasikan sebagai denah isometrik, dan sistemnya dievaluasi lewat metrik akurasi, efektivitas, tingkat halusinasi, dan explainability.
- **Peran saya:** membangun seluruh kode di Google Colab dari awal sampai selesai, mulai dari pipeline multi-agent sampai visualisasi dan evaluasi. Proses deploy ke publik dikerjakan oleh anggota tim lain.
- **Demo:** [roomify di Hugging Face](https://huggingface.co/spaces/tanzz15/roomify) (di-deploy oleh anggota tim)
- **Stack:** Python, LangGraph, Groq, Gradio, Pillow

### 5. Tiketmu: [`project_Tiketmu_Semester4`](https://github.com/rita-rahmawati/project_Tiketmu_Semester4)
- **Deskripsi:** proyek web pemesanan tiket online yang saya buat di semester 4 dengan PHP. Proyek ini jadi fondasi awal saya di backend web sebelum pindah ke Laravel.
- **Stack:** PHP

## Eksperimen lain
- [`obesity-classification-ml`](https://github.com/rita-rahmawati/obesity-classification-ml): klasifikasi obesitas menggunakan model Random Forest
- [`tinygpt-sejarah-indonesia`](https://github.com/rita-rahmawati/tinygpt-sejarah-indonesia): korpus Sejarah Indonesia untuk melatih model TinyGPT

## Sertifikasi
- Dicoding: Belajar Dasar AI
- Dicoding: Memulai Pemrograman dengan Python
- Sertifikat Asisten Praktikum, Sistem Basis Data

## Sedang saya pelajari
Pipeline ETL terjadwal, PostgreSQL, dan Linux untuk pengelolaan server. Gap ini saya temukan setelah membandingkan skill saya dengan lowongan data engineer.

## Hubungi saya
- 💼 LinkedIn: [linkedin.com/in/ritarahmawati](https://www.linkedin.com/in/ritarahmawati)
- ✉️ ritarahmawatirita23@gmail.com
