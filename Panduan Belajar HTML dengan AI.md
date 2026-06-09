# Panduan-Belajar-HTML-dari-AI
### 1. Apa itu HTML?

Bayangkan sebuah rumah:

* **HTML** adalah **kerangka/struktur** rumah (dinding, pintu, jendela).
* **CSS** adalah **cat dan dekorasi** rumah (membuatnya cantik).
* **JavaScript** adalah **sistem kelistrikan/mekanik** (membuatnya berfungsi, seperti tombol yang bisa ditekan).

---

### 2. Struktur Dasar HTML

Setiap file HTML harus memiliki struktur dasar seperti ini:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Judul Halaman Kamu</title>
</head>
<body>
    <h1>Ini adalah Judul Utama</h1>
    <p>Ini adalah paragraf pertama di web saya.</p>
</body>
</html>

```

* `<html>`: Wadah utama seluruh elemen.
* `<head>`: Berisi informasi yang tidak terlihat langsung di halaman (seperti judul tab).
* `<body>`: Semua konten yang akan muncul di layar (teks, gambar, tombol).
* `<h1>` sampai `<h6>`: Untuk judul (heading).
* `<p>`: Untuk paragraf.

---

### 3. Persiapan Lingkungan Belajar

Kamu tidak butuh aplikasi rumit. Kamu hanya butuh dua hal ini:

1. **Text Editor:** Saya sarankan mengunduh **Visual Studio Code (VS Code)**. Ini standar industri yang gratis dan sangat membantu.
2. **Browser:** Gunakan Google Chrome atau Firefox untuk melihat hasil kerjamu.

---

### 4. Langkah Belajar yang Direkomendasikan

Untuk menjadi mahir, ikuti alur ini:

1. **Pelajari Tag Dasar:** Pahami bagaimana membuat judul (`h1-h6`), paragraf (`p`), daftar (`ul`, `ol`, `li`), link (`a`), dan gambar (`img`).
2. **Latihan Membuat Formulir:** Pelajari `<form>`, `<input>`, dan `<button>` (sangat penting untuk interaksi pengguna).
3. **Memahami Tabel & Div:** Gunakan `<table>` untuk data dan `<div>` untuk membagi-bagi bagian halaman.
4. **Lanjut ke CSS:** Setelah kamu paham struktur, segera pelajari CSS agar tampilan web kamu tidak membosankan.

---

### 5. Sumber Belajar Gratis Terbaik

* [W3Schools HTML](https://www.w3schools.com/html/): Sangat ramah pemula, banyak contoh latihan langsung.
* [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web): Sumber dokumentasi paling lengkap dan akurat dari Mozilla.
* [FreeCodeCamp](https://www.freecodecamp.org/): Bagus jika kamu suka belajar sambil praktik langsung.

---

> **Tips:** Cara tercepat belajar coding adalah dengan **praktik langsung**. Jangan hanya membaca, cobalah buat file `.html` sendiri di komputer, ketik kodenya, dan buka di browser.

### 6. Latihan kecil untuk mencoba membuat halaman web pertamamu
Ikuti langkah-langkah ini:

1. Buka **Notepad** (di Windows) atau **TextEdit** (di Mac), atau lebih baik lagi gunakan **VS Code**.
2. Salin dan tempel kode di bawah ini:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Halaman Profil Saya</title>
</head>
<body>
    <h1>Halo, nama saya [Nama Kamu]</h1>
    <p>Ini adalah website pertama yang saya buat sendiri menggunakan HTML.</p>
    
    <h2>Hobi Saya</h2>
    <ul>
        <li>Mendesain Produk</li>
        <li>Fotografi Mobile</li>
        <li>Eksplorasi Website Unik</li>
    </ul>

    <p>Kamu bisa menghubungi saya melalui <a href="mailto:email@kamu.com">email</a>.</p>
</body>
</html>

```

3. **Simpan File:**
* Klik **Save As**.
* Beri nama file dengan akhiran `.html`, contoh: `profil.html`.
* Pastikan *Save as type* diubah menjadi **All Files** (jika pakai Notepad).


4. **Buka di Browser:**
* Cari file `profil.html` yang tadi kamu simpan.
* Klik dua kali (atau klik kanan > *Open with* > pilih Google Chrome/Browser favoritmu).



---

### Apa yang baru saja kamu lakukan?

* Kamu telah membuat **Elemen Struktur** (`h1`, `h2`, `p`).
* Kamu telah membuat **Daftar** (`ul` dan `li`).
* Kamu telah membuat **Link/Tautan** (`a`) yang bisa diklik.

### Tantangan untukmu:

Setelah kamu berhasil melihat hasilnya di browser, coba lakukan perubahan ini agar kamu lebih paham:

1. Ganti teks "Halo, nama saya..." dengan namamu sendiri.
2. Tambahkan satu hobi lagi di dalam daftar `<li>...</li>`.
3. Simpan perubahan tersebut, lalu **Refresh** (tekan F5) halaman browser kamu untuk melihat perubahannya.
   
