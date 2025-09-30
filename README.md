# lab2web
# Praktikum 2 - CSS Dasar
### NAMA : M.Rizqy Al Rasyd
### NIM : 312410424
### KELAS : TI.24.A3

## STRUKTUR REPOSITORY
```
Lab2Web/
│── first.html
│── cso.css
│── README.md
```

### 1. EKSPERIMEN MENGUBAH PROPERTI PADA NILAI KODE CSS
```css
h1 {
    font-size: 30px;
    color: darkblue;
    text-align: center;
}
h1:hover {
    color: red;
}
```
### 2. PERBEDAAN h1 {} DENGAN #intro h1{}
- h1 {} berlaku untuk semua elemen <h1> di halamannya.
- #inteo h1 {} hanya berlaku pada elemen <h1> yang berada di dalam tag dengan id intro.

```html
<h1>CSS Dasar</h1>
<div id="intro">
   <h1>HTML Dasar</h1>
</div>
```
- CSS Dasar pakai aturan global h1.
- HTML Dasar pakai khusus #intro h1.

### 3. DEKLARASI PADA CSS
Urutan prioritas CSS adalah:
1. Inline CSS
2. Internal CSS
3. Eksternal CSS

Kesimpulannya Inline akan selalu ditampilkan duluan.

### 4. ID dan CLASS
- ID(#id) hanya boleh dipakai sekali perhalaman.
- CLASS(.class) bisa dipakai berkali-kali.
Jika elemen punya ID dan CLASS dalam satu, maka ID akan didahulukan.

```css
#paragraf-1 { color: blue; }
.text-paragraf { color: green; }
```
```html
<p id="paragraf-1" class="text-paragraf">Halo CSS</p>
```
Hasik: Teks yang ditampikan akan berwarna biru karena id="paragraf-1" lebih spesifik.
