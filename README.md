# data-mahasiswa
Latihan2

DASAR DATA LAPORAN PRAKTIKUM
Serius Ndruru 312210508 TI.22.A.5

BAB I PENDAHULUAN

1.1. Latar Belakang

    MySQL yang dibaca “MY-ES-KYOO-EL" merupakan sistem manajemen database yang bersifat open-source yang menggunakan perintah dasar atau bahasa pemrograman yang berupa structured query language (SQL) yang cukup populer di dunia teknologi. MySQL berguna sebagai database.

1.2. Tujuan

    Tujuan praktikum membuat tabel basis data MySQL adalah untuk mengajar peserta cara membuat dan mengelola tabel dalam sistem basis data MySQL serta meningkatkan keterampilan teknis dalam pengelolaan basis data. Praktikum ini juga mempersiapkan peserta untuk bekerja dengan sistem basis data MySQL dalam pengembangan aplikasi web dalam dekstop

BAB II DASAR TEORI

    Dasar teori praktikum membuat tabel basis data MySQL meliputi sistem basis data MySQL, tabel, field, record, primary key, foreign key, dan normalisasi. Hal ini penting untuk dipahami agar peserta memahami konsep-konsep dasar dalam memuat dan mengelola tabel dalam sistem basis data MySQL.

2.1. Perintah yang Dipakai

    1. TAMPILKAN
    2. BUAT
    3. JATUHKAN
    4. GUNAKAN
    5. DESKRIPSI/DESKRIPSI
    6. MENGUBAH

2.2. Contoh Perintah Pemakaian Diatas

    1. Membuat Database

       BUAT DATABASE [nama database];

    2. Memakai meja yang baru

       GUNAKAN [nama database];

    3. Membuat tabel

       CREATE TABLE [nama tabel] (nama VARCHAR(100) alamat TEXT);

BAB III LANGKAH-LANGKAH PEMBUATAN

3.1. LANGKAH-LANGKAH

     BUAT DATABASE latihan2;
     GUNAKAN latihan2;
     CREATE TABLE biodata (nama VARCHAR(100),alamat TEXT);
     ALTER TABLE biodata ADD COLUMN keterangan VARCHAR(15);
     ALTER TABLE biodata ADD COLUMN id int(11) first;
     ALTER TABLE biodata ADD COLUMN phone VARCHAR(15) SETELAH alamat;
     ALTER TABLE biodata MODIFY COLUMN id Char(11);
     ALTER TABLE biodata GANTI telepon hp VARCHAR(20);
     ALTER TABLE biodata ADD COLUMN email INT SETELAH hp;
     ALTER TABLE biodata DROP COLUMN keterangan;
     ALTER TABLE biodata RENAME data_mahasiswa;
     ALTER TABLE data_mahasiswa GANTI id nim varchar(11);
     ALTER TABLE data_mahasiswa ADD PRIMARY KEY(nim);
     ALTER TABLE data_mahasiswa ADD UNIQUE(email);

3.2. OUTPUT CREENSHOT

BAB IV PENUTUP

4.1. KESIMPULAN

    Praktikum membuat tabel dalam MySQL menggunakan command line client dan git merupakan salah satu cara untuk memperolah pemahaman dasar tentang cara membuat tabel dalm database MySQL dalam praktikum ini, peserta mempelajari bahwa MySQL adalah salah satu database management system (DBMS) yang paling populer dan banyak digunakan di seluruh dunia.

    Selama praktikum, peserta belajar bagaimana membuat tabel dalam MySQL menggunakan perintah CREATE TABLE. Namun, sebelum membuat tabel, pengguna harus terlebih dahulu membuat database. Setelah database dibuat, pengguna dapat memulai membuat tabel dengan mengidentifikasi kolom atau field yang dibutuhkan dan jenis data yang cocok untuk setiap kolom tersebut.

    peserta juga mengajarkan konsepdasar database tantang, seperti primary key, foreign key, indeks, Primary key adalah kolom yang unik dan dapat di jadikan sebagai identitas untuk setiap baris atau record dalam tabel. foreign key digunakan untuk menghubungkan dua tabel dalm database, sedangkan indeks adalah tabel pencarian khusu yang digunakan mesin pencari basis data untuk memperepat pengambilan data.
