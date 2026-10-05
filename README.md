# 💻 Praktikum 3 — CSS Dasar

Repository ini berisi hasil pengerjaan **Praktikum 3: CSS Dasar** pada mata kuliah **Pemrograman Web**.

## 📌 Identitas

| Keterangan  | Detail                    |
| ----------- | ------------------------- |
| Nama        | **Chaya Aulia**           |
| Mata Kuliah | Pemrograman Web           |
| Praktikum   | Praktikum 3 — CSS Dasar   |
| Repository  | **Lab3Web**               |
| Universitas | Universitas Pelita Bangsa |

---

## 🎯 Tujuan Praktikum

Praktikum ini bertujuan untuk:

1. Memahami konsep dasar CSS.
2. Memahami aturan penulisan CSS.
3. Memahami penggunaan selector sebagai pengontrol CSS.
4. Membuat pengaturan CSS pada dokumen HTML.

---

## 📚 Materi yang Dipelajari

Pada praktikum ini dipelajari beberapa konsep dasar CSS, yaitu:

* CSS Internal
* CSS Inline
* CSS Eksternal
* Element Selector
* Class Selector
* ID Selector
* Property dan Value CSS
* Penerapan CSS pada dokumen HTML

---

# 🛠️ Langkah-Langkah Praktikum

## 1. Membuat Dokumen HTML

Pertama, dibuat dokumen HTML dengan nama:

```text
lab2_css_dasar.html
```

Dokumen berisi struktur dasar HTML seperti `header`, `nav`, `div`, heading, paragraf, serta link.

Pada tahap ini juga digunakan **ID Selector** dan **Class Selector** pada beberapa elemen HTML.

### 📸 Hasil Praktikum

![Membuat Dokumen HTML](screenshot/01-membuat-dokumen-html.png)
![Tampilan Dokumen HTML](screenshot/01-tampilan-dokumen-html.png)

---

## 2. Mendeklarasikan CSS Internal

Pada tahap kedua, CSS ditambahkan langsung ke dalam dokumen HTML menggunakan tag:

```html
<style>
```

yang diletakkan pada bagian `<head>`.

CSS digunakan untuk mengatur beberapa bagian seperti:

* jenis font
* tinggi header
* border
* ukuran heading
* warna teks
* posisi teks

Contoh:

```css
body {
    font-family: 'Open Sans', sans-serif;
}

header {
    min-height: 80px;
    border-bottom: 1px solid #77CCEF;
}

h1 {
    font-size: 24px;
    color: #0F189F;
    text-align: center;
}
```

### 📸 Hasil Praktikum

![Mendeklarasikan CSS Internal](screenshot/02-mendeklarasikan-css-internal.png)
![Tampilan Penambahan CSS pada HTML](screenshot/02-tampilan-penambahan-css-pada-html.png)

---

## 3. Menambahkan Inline CSS

Selanjutnya, diterapkan **Inline CSS** secara langsung pada elemen HTML menggunakan atribut `style`.

Contoh:

```html
<p style="text-align: center; color: #ccd8e4;">
```

Inline CSS digunakan untuk memberikan pengaturan style secara langsung pada elemen tertentu.

### 📸 Hasil Praktikum

![Menambahkan Inline CSS](screenshot/03-menambahkan-inline-css.png)
![Tampilan Menambahkan Inline CSS](screenshot/03-tampilan-menambahkan-inline-css.png)

---

## 4. Membuat CSS Eksternal

Pada tahap ini dibuat file CSS terpisah dengan nama:

```text
style_eksternal.css
```

Kemudian file CSS tersebut dihubungkan ke dokumen HTML menggunakan tag:

```html
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
```

Penggunaan CSS eksternal membuat aturan style dapat dipisahkan dari dokumen HTML sehingga kode menjadi lebih terstruktur.

### 📸 Hasil Praktikum
![Membuat CSS Eksternal](screenshot/04-membuat-css-eksternal.png)
![Menambahkan Tag Link](screenshot/04-tambahkan-tag-link.png)
![Tampilan Eksternal CSS](screenshot/04-tampilan-eksternal-css.png)

---

## 5. Menambahkan CSS Selector

Pada tahap terakhir, digunakan **ID Selector** dan **Class Selector**.

### 🔹 Navigation

CSS digunakan untuk mengatur tampilan navigasi:

```css
nav {
    background: #20A759;
    color: #fff;
    padding: 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
    padding: 10px 20px;
}

nav .active,
nav a:hover {
    background: #0B6B3A;
}
```

### 🔹 ID Selector

ID Selector digunakan untuk memberikan style khusus pada elemen dengan ID tertentu.

```css
#intro {
    background: #418fb1;
    border: 1px solid #099249;
    min-height: 100px;
    padding: 10px;
}

#intro h1 {
    text-align: left;
    border: 0;
    color: #fff;
}
```

### 🔹 Class Selector

Class Selector digunakan pada elemen yang memiliki class tertentu.

```css
.button {
    padding: 15px 20px;
    background: #bebcbd;
    color: #fff;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
}

.btn-primary {
    background: #E42A42;
}
```

### 📸 Hasil Praktikum

![Menambahkan CSS Selector](screenshot/05-menambahkan-css-selector.png)
![Tampilan CSS ID dan Class Selector](screenshot/05-tampilan-css-id-class-selector.png)
---

### ✅ Kesimpulan

Pada Praktikum 3 ini telah dipelajari dasar-dasar CSS, mulai dari CSS Internal, Inline, dan Eksternal hingga penggunaan Element Selector, Class Selector, dan ID Selector.

Melalui praktikum ini, CSS dapat digunakan untuk mengatur tampilan halaman HTML agar lebih terstruktur, menarik, dan mudah dikelola.
