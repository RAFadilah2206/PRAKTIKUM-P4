Anita (312310244)

# PHP Framework
# Mengaktfikan Ekstensi PHP
Berikut beberapa ekstensi yang perlu diaktifkan:
• php-json ekstension untuk bekerja dengan JSON;
• php-mysqlnd native driver untuk MySQL;
• php-xml ekstension untuk bekerja dengan XML;
• php-intl ekstensi untuk membuat aplikasi multibahasa;
• libcurl (opsional), jika ingin pakai Curl.
Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini

![Screenshot 2025-06-10 182110](https://github.com/user-attachments/assets/dac4c523-9016-4e8d-92de-7125e0921a98)


# Instalasi Codeigniter 4
• Unduh Codeigniter dari website https://codeigniter.com/download
• Extrak file zip Codeigniter ke direktori htdocs/lab11_ci.
• Ubah nama direktory framework-4.x.xx menjadi ci4.
• Buka browser dengan alamat http://localhost/lab11_ci/ci4/public/

![Screenshot 2025-04-21 213850](https://github.com/user-attachments/assets/a4027cce-de68-432d-85d9-a04697ff6b13)

# Menjalankan CLI (Command Line Interface)
Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah: 
php spark
![Screenshot 2025-04-19 135344](https://github.com/user-attachments/assets/79a5ad72-02b6-4dd7-b0a4-200fad2f3e9b)

# Mengaktifkan Mode Debugging
Secara default fitur ini belum aktif. Ketika terjadi error pada aplikasi akan ditampilkan pesan kesalahan, Semua jenis error akan ditampilkan sama. Untuk memudahkan mengetahui jenis errornya,maka perlu diaktifkan mode debugging dengan mengubah nilai konfigurasi pada environment
variable CI_ENVIRINMENT menjadi development.

# Membuat Route Baru
Untuk mengetahui route yang ditambahkan sudah benar, buka CLI dan jalankan perintah berikut.
php spark routes
![Screenshot 2025-04-19 135757](https://github.com/user-attachments/assets/1cd657bf-51d2-47e0-8936-88de8186eb84)

# Membuat Controller
Selanjutnya adalah membuat Controller Page. Buat file baru dengan nama page.php pada direktori Controller kemudian isi kodenya seperti berikut.
![Screenshot 2025-04-19 140454](https://github.com/user-attachments/assets/c54ee357-bf07-418f-80dd-2364a3e97270)

Selanjutnya refresh Kembali browser, maka akan ditampilkan hasilnya yaotu halaman sudah dapat diakses.
![Screenshot 2025-04-19 140332](https://github.com/user-attachments/assets/51b7f364-4bee-4026-a970-c73327a23b89)

# Auto Routing
![Screenshot 2025-04-19 140901](https://github.com/user-attachments/assets/46320100-4876-4aa6-ad23-5a086c83a645)

# Membuat View 
![Screenshot 2025-04-19 141212](https://github.com/user-attachments/assets/32be86c9-6276-4a4f-ab6f-5ffba35cc19c)

# Membuat Layout Web dengan CSS
![Screenshot 2025-04-21 213138](https://github.com/user-attachments/assets/5ebe12b7-1d81-45d8-a98f-f8585449d139)

![Screenshot 2025-04-19 145623](https://github.com/user-attachments/assets/a5864c6c-9738-486b-8015-84eb5bf22876)

# LatihanWeb4
# 1. Membuat Box Element
Kemudian tambahkan kode untuk membuat box element dengan tag div,Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element,
Kemudian buka browser untuk melihat hasilnya.

![Screenshot (204)](https://github.com/user-attachments/assets/1db9fd8a-9aff-470c-8806-aa957219e4ad)
# Mengatur Clearfix Element
Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk
mengaturnya. Kemudian tambahkan element div lainnya seteleah div3,atur property clear pada CSS,
Selanjutnya buka browser dan refresh kembali.

![Screenshot (205)](https://github.com/user-attachments/assets/6b8af866-fd91-4612-8d88-f1eef7d55f2a)
# 2. Membuat Layout Sederhana
Buat folder baru dengan nama lab4_layout, kemudian buatlah file baru didalamnya dengan nama home.html, dan file css dengan nama style.css.
Kemudian tuliskan kode dan buka browser dan lihat hasilnya.

![Screenshot (208)](https://github.com/user-attachments/assets/3677d130-27e3-418a-a3fc-17c8884660a7)
Kemudian tambahkan kode CSS untuk membuat layoutnya.

![Screenshot (210)](https://github.com/user-attachments/assets/4783f387-6eea-46d0-8e99-089ddec89fa7)
# Membuat Navigasi
Kemudian selanjutnya mengatur navigasi lalu hasilnya seperti berikut

![Screenshot (211)](https://github.com/user-attachments/assets/ef133b91-6a01-45cd-9582-105d8e57cfad)
# Membuat Hero Panel.
Selanjutnya membuat hero panel.Tambahkan kode HTML dan CSS lalu hasilnya seperti berikut 

![Screenshot (212)](https://github.com/user-attachments/assets/bf77dc2b-1116-4143-a389-d4d3275b6b30)
# Mengatur Layout Main dan Sidebar
Selanjutnya mengatur main content dan sidebar, tambahkan CSS float.Kemudian selanjutnya menambahkan element lain dalam sidebar. dan tambahkan elemen lainnya pada main content
kemudian hasilnya seperti berikut

![Screenshot (213)](https://github.com/user-attachments/assets/02501a66-4b07-450f-a944-3a4dd937c20a)

![Screenshot (214)](https://github.com/user-attachments/assets/d33b8158-8e8b-47a0-9d80-ebde60c6ab58)

![Screenshot (215)](https://github.com/user-attachments/assets/25928830-cef1-4b1b-8745-51b42cec47ad)

# Menambahkan Content Artikel
![Screenshot (216)](https://github.com/user-attachments/assets/2ebf2325-9f54-445c-85ae-52a67614aae7)

