# Lab2Web

**Tugas Praktikum 2**

**Instruksi Praktikum**
1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lab2_css_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
5. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/

**Pertanyaan dan Tugas**
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( < p id="paragraf-1" class="text-paragraf" > )

**Laporan Praktikum**
1. Buatlah repository baru dengan nama Lab2Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus

Kali ini ini saya akan membuat kode css pada file html, berikut langkah-langkahnya:

1. Intruksi Praktikum
   a. Persiapkan text editor misalnya VSCode.
   <img width="1920" height="1080" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/37383945-8849-4389-a8cc-958a857cf6e5" />
   berikut vscode yang saya siapkan
   b. Buat file baru dengan nama lab2_css_dasar.html
   <img width="561" height="294" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/f10fe6d0-fc64-475b-85f3-cb6eaf18a4f2" />
   berikut file yang dibuat
   c. Buat struktur dasar dari dokumen HTML.
   <img width="1920" height="1080" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/bbb73a0c-fe14-418a-ba67-d7df713fe159" />
   <img width="1920" height="1080" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/ef2a3c56-c375-4dcc-a719-bd89dda00b24" />
   berikut struktur html dengan hasilnya
   d. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
      1. Membuat Dokumen html
         sudah dibuat di bagian c
      2. Mendekralasikan CSS Internal
         saya akan membuat internal CSS sesuai intruksi dengan sedikit perubahan
         <img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/092dcae0-9852-40fb-aff6-c4b774e63c8a" />
         hasil dari pembuatan internal CSS:
         <img width="1920" height="1080" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/56e04e00-1657-4252-a6cd-12b4bdc65ed3" />
      3. Menambahkan Inline CSS
         saya akan menggunakan inline CSS pada bagian paragraf < p >
         <img width="1920" height="1080" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/22d6217d-a634-4adc-8bb7-ea5e92af94c0" />
         berikut hasilnya:
         <img width="1920" height="1080" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/843f26cb-eb7e-4407-b73c-5997c8df4b83" />
      4. Membuat CSS Eksternal
         Untuk filenya saya akan memberi nama lab.css sebagai eksternal CSS
         <img width="1920" height="1080" alt="Screenshot (119)" src="https://github.com/user-attachments/assets/c2a93e50-5d5e-4c4b-8e24-8c4383d5a762" />
         <img width="1920" height="1080" alt="Screenshot (120)" src="https://github.com/user-attachments/assets/aed21d75-a7db-4f7c-87d3-5d3550aee50a" />
         berikut hasilnya:
         <img width="1920" height="1080" alt="Screenshot (118)" src="https://github.com/user-attachments/assets/da738465-dc83-418f-b6fb-e429c4284d90" />
      5. Menambahkan CSS Selector
         untuk mempercantik web saya menggunakan CSS selector yang diberikan
         <img width="1920" height="1080" alt="Screenshot (121)" src="https://github.com/user-attachments/assets/fb483833-9201-4579-b20c-0ef4bfe573e1" />
         Tampilan:
         <img width="1920" height="1080" alt="Screenshot (122)" src="https://github.com/user-attachments/assets/e467d630-c755-465d-b0df-4b83475347c9" />
   e. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/
      berikut hasilnya:
      <img width="1920" height="1080" alt="Screenshot (123)" src="https://github.com/user-attachments/assets/0fe92d17-7caf-44b4-90f4-502ab7793cdb" />
   
2. Pertanyaan & Tugas
   a. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
      Jawaban: saya sudah sedikit memodifikasi file sekalian membuat html dan CSS tadi
   b. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
      h1 {...}: Menargetkan semua elemen <h1> di seluruh halaman.
      #intro h1 {...}: Hanya menargetkan elemen <h1> yang berada di dalam elemen dengan id="intro".
      Selektor #intro h1 lebih spesifik dan akan menimpa (override) gaya dari h1 jika ada konflik.
   c. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?Berikan penjelasan dan contohnya!
      Dalam situasi tersebut, peramban akan menampilkan inline CSS. Inline CSS memiliki prioritas tertinggi dibandingkan dengan CSS internal dan eksternal, dan akan menimpa deklarasi lainnya untuk properti yang sama pada elemen tersebut. 
      Urutan prioritasnya adalah:
      Inline CSS (tertinggi)
      Internal/Eksternal CSS
      Gaya bawaan peramban (terendah)
      contoh:
      <img width="1920" height="1080" alt="Screenshot (124)" src="https://github.com/user-attachments/assets/c374f9de-81ed-4ae0-a308-51682b9e6808" />
      <img width="1920" height="1080" alt="Screenshot (125)" src="https://github.com/user-attachments/assets/1ca96617-8d1c-4940-9427-47342495f020" />
      <img width="1920" height="1080" alt="Screenshot (126)" src="https://github.com/user-attachments/assets/4e2cbc10-bbbf-4784-8b9b-00e1d5421288" />
   d. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
      Pada sebuah elemen HTML yang memiliki id dan class, deklarasi CSS dari id akan ditampilkan. 
      Ini karena selektor id memiliki tingkat spesifisitas yang lebih tinggi dibandingkan selektor class.
      Peramban selalu menerapkan gaya dari selektor yang paling spesifik.
      <img width="1920" height="1080" alt="Screenshot (129)" src="https://github.com/user-attachments/assets/123db0a1-ccf2-45b8-85fd-6944dd66c549" />
      <img width="1920" height="1080" alt="Screenshot (128)" src="https://github.com/user-attachments/assets/f3d10b36-6f46-4083-b0ca-974dc7c696a1" />
4. Laporan Praktikum
   semua tugas yang terkait sudah dikerjakan
