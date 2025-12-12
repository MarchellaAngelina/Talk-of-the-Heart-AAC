# Talk of the Heart AAC
Talk of The Heart AAC adalah aplikasi berbasis seluler (*mobile*) yang dirancang untuk menjembatani kesenjangan komunikasi antara anak autisme (dengan hambatan wicara) dan mitra komunikasinya. 

### Tentang Aplikasi dan Pengguna

Petunjuk penggunaan ini secara spesifik ditujukan untuk **pendamping anak** dengan spektrum autisme, seperti guru atau orang tua. Pengguna anak diwajibkan telah memiliki kemampuan baca dan tulis, seperti pada kategori *high-functioning autism* atau *Asperger syndrome* yang umumnya berusia mulai dari 6-8 tahun.

## 🌟 Fitur Utama

Aplikasi ini memiliki dua fungsi inti untuk memfasilitasi komunikasi:

1.  **Alat Wicara (Speech Output):**
    * Memungkinkan anak memilih satu atau lebih kartu bergambar (*picture cards*).
    * Setiap kartu yang dipilih akan menghasilkan keluaran suara (*speech*) yang sesuai dengan teks pada kartu, membantu anak untuk berekspresi secara verbal.

2.  **Platform Komunikasi Dua Arah:**
    * Hasil susunan kartu yang dipilih oleh anak akan diproses dan **diterjemahkan** menjadi kalimat Bahasa Indonesia yang lengkap, natural, dan sesuai kaidah kebahasaan.
    * Pesan terjemahan ini kemudian dapat dikirimkan ke berbagai kontak melalui fitur percakapan dalam aplikasi, memungkinkan komunikasi dua arah yang efektif.

### 🧠 Teknologi di Balik Penerjemahan

Aplikasi ini memanfaatkan teknologi Kecerdasan Buatan (AI) untuk menghasilkan terjemahan kalimat yang akurat. Model yang diimplementasikan adalah:

* **Model:** *Sequence-to-Sequence (Seq2Seq)*
* **Arsitektur:** GRU (*Gated Recurrent Unit*) dengan Mekanisme Atensi (*Attention Mechanism*).
* **Fungsi:** Menerjemahkan susunan kartu bergambar menjadi kalimat Bahasa Indonesia yang lengkap.

## 🛠️ Persyaratan Sistem Minimum

Untuk menjalankan aplikasi ini dengan lancar, sistem operasi *mobile* dan perangkat Anda harus memenuhi spesifikasi berikut:

| Komponen | Spesifikasi Minimum Aplikasi |
| :--- | :--- |
| **Sistem Operasi** | Android 8.0 (Oreo) |
| **RAM** | 2 GB |
| **CPU** | Quad-core 1.4 Ghz |
| **Penyimpanan** | Internal >= 8 GB |
| **Koneksi** | Diperlukan koneksi internet (data/WI-FI) |

## 🚀 Cara Instalasi untuk Developer

Bagian ini memandu Anda untuk menjalankan proyek *source code* Kotlin ini di lingkungan pengembangan Anda.

### Pra-syarat

* **Android Studio:** Versi terbaru direkomendasikan.
* **JDK (Java Development Kit):** Terintegrasi dengan Android Studio.
* **Koneksi Internet:** Untuk mengunduh dependensi Gradle.

### Langkah-Langkah Instalasi

#### 1. Kloning Repositori

Buka Terminal atau *Command Prompt*, lalu kloning repositori dari GitHub:

```bash
git clone [https://github.com/USERNAME/Talk-of-the-Heart-AAC.git](https://github.com/USERNAME/Talk-of-the-Heart-AAC.git)
cd Talk-of-the-Heart-AAC
