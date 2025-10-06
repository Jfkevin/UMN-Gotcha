# 🐾 UMN Gotcha  
Sebuah aplikasi permainan simulasi kehidupan hewan piaraan berbasis web yang dibangun menggunakan **HTML**, **CSS**, dan **JavaScript**.  

---

## 🖼️ Dokumentasi Project
Tampilan antarmuka utama dan gameplay:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/29a72292-9819-4dfa-9fe2-72b2e6ccc83f" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d6a3f0b-d83c-4e23-96d4-df0ccd1d725a" />

---

## 🎥 Link Video Presentasi Demo
  
[https://www.youtube.com/watch?v=BMhFSkem_F4](https://www.youtube.com/watch?v=BMhFSkem_F4)

---

## 🧩 Penjelasan Project

**UMNGotcha** merupakan permainan simulasi kehidupan hewan piaraan (*virtual pet simulation*) yang diawali dengan pemilihan avatar hewan dan pengisian nama.  
Setelah menekan tombol **PLAY**, pemain akan diarahkan ke tampilan utama permainan.

### 🎮 Fitur dan Mekanisme Permainan
1. **Status / Kondisi Pemain**  
   Ditampilkan dalam bentuk *status bar* yang merepresentasikan empat kondisi utama:
   - 🍖 Makan  
   - 💤 Tidur  
   - 🎮 Bermain  
   - 💊 Kesehatan  

2. **Level Pemain**  
   Pemain memulai dari **Level 1 (Bayi)** dengan kondisi awal *50%* pada setiap status. Level dapat meningkat seiring waktu dan aktivitas.

3. **Waktu dan Sapaan Dinamis**  
   - Terdapat **jam permainan** yang berjalan lebih cepat dari waktu nyata.  
     Contoh: `1 detik dunia nyata = 1 menit dalam permainan`.  
   - Tulisan sapaan seperti **Good Morning**, **Good Afternoon**, dan **Good Night** akan berubah menyesuaikan jam permainan.

4. **Avatar Hewan Interaktif**  
   - Avatar hewan akan **berubah animasi / pose** sesuai aktivitas yang dilakukan.  
     Contoh: saat makan, avatar menampilkan animasi “makan” selama 15 detik.

5. **Tombol Aktivitas**  
   Pemain dapat memilih salah satu aktivitas berikut:
   - 🍽️ **Makan**
   - 💤 **Tidur**
   - 🎯 **Main**
   - 💊 **Obat**

6. **Latar Belakang Dinamis**  
   Background permainan akan **berubah sesuai waktu**, menampilkan suasana:
   - 🌅 Pagi  
   - 🌞 Siang  
   - 🌙 Malam

---

### ⚙️ Mekanisme Status
- Setiap aktivitas akan **meningkatkan satu status utama**, namun **menurunkan status lain**.  
  Contoh: bermain meningkatkan status *Main*, tetapi menurunkan status *Tidur*.
- Saat pemain **idle** (tidak melakukan aktivitas), seluruh status akan **berkurang perlahan**.
- Efek aktivitas juga dipengaruhi status lain:  
  Misalnya, jika pemain **bermain dalam kondisi lapar**, maka peningkatan status bermain menjadi lebih kecil.

---

### ⭐ Mini-Game (Mode Bermain)
Ketika memilih aktivitas **Main**, layar akan berubah ke mode permainan:
- 🌟 Bintang akan muncul secara acak di area permainan.  
- Pemain menggerakkan hewan piaraannya dengan **keyboard (arrow keys)** atau tombol panah di layar.  
- Setiap bintang yang didapatkan akan **meningkatkan status bermain**.  
- Setiap bintang yang terlewat akan **mengurangi status bermain**.

---

## 🛠️ Teknologi & Tools

| Kategori | Teknologi / Tools |
|-----------|------------------|
| 💻 **Bahasa Pemrograman** | HTML, CSS, JavaScript |
| 🧰 **Editor** | Visual Studio Code (VSCode) |
| 🧩 **Library / Framework** | Native JavaScript (tanpa framework) |
| ☁️ **Version Control** | Git & GitHub |

---

## 👨‍💻 Tim Pengembang

| No | Nama Lengkap | NIM |
|----|---------------|-----|
| 1 | **Marcellus Eugene Kaparang** | 00000082420 |
| 2 | **Merhandes Gunawan** | 00000081070 |
| 3 | **Muhammad Fikri Rouzan Ash Shidik** | 00000081083 |
| 4 | **Farrelius Kevin** | 00000081783 |

---

## 📚 Mata Kuliah
**Pengenalan Teknologi Internet** – `IF231` – *Semester 2*  
**Program Studi Informatika**  
**Fakultas Teknik dan Informatika**  
🏫 *Universitas Multimedia Nusantara (UMN)*
