Application Containerization and Microservice Orchestration

1. Stage Setup
Mari kita mulai dengan mengkloning repositori kode demo, mengubah direktori kerja, dan memeriksa cabang demo terlebih dahulu.

https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar1.jpeg

2. Step 0: Basic Link Extractor Script
Periksa cabang step0 dan daftarkan file di dalamnya.

https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar2.jpeg

File linkextractor.py adalah yang menarik di sini, jadi mari kita lihat isinya:

https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar3.jpeg

Namun, skrip yang tampaknya sederhana ini mungkin bukan yang paling mudah dijalankan pada mesin yang tidak memenuhi persyaratannya. File README.md menyarankan cara menjalankannya, jadi mari kita coba:
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar4.jpeg

Ketika kami mencoba menjalankannya sebagai skrip, kami mendapatkan izin ditolak kesalahan. Mari kita periksa izin saat ini pada file ini:
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar5.jpeg

3. Step 1: Containerized Link Extractor Script
Periksa cabang step1 dan daftarkan file di dalamnya.
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar6.jpeg

Kami telah menambahkan satu file baru (mis., Dockerfile) pada langkah ini. Mari kita lihat isinya:
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar7.jpeg

Sejauh ini, kami baru saja menggambarkan bagaimana kami ingin seperti gambar Docker kami, tetapi tidak benar-benar membangun satu. Jadi mari kita lakukan itu:
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar8.jpeg

https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar9.jpeg

Kami telah membuat gambar Docker bernama linkextractor: step1 berdasarkan Dockerfile yang diilustrasikan di atas. Jika build berhasil, kita harus dapat melihatnya di daftar gambar:
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar10.jpeg

Gambar ini harus memiliki semua bahan yang diperlukan yang dikemas di dalamnya untuk menjalankan skrip di mana saja pada mesin yang mendukung Docker. Sekarang, mari kita jalankan wadah satu kali dengan gambar ini dan ekstrak tautan dari beberapa halaman web langsung:
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar11.jpeg

4. Step 2: Link Extractor Module with Full URI and Anchor Text
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar12.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar13.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar14.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar15.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar16.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar17.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar18.jpeg



5. Step 3: Link Extractor API Service
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar19.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar20.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar21.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar22.jpeg


6. Step 4: Link Extractor API and Web Front End Services
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar23.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar24.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar25.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar26.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar27.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar28.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar29.jpeg


7. Step 5: Redis Service for Caching
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar30.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar31.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar32.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar33.jpeg
https://github.com/pujumuslimah/UAS-TCC/blob/master/materi-03/gambar34.jpeg