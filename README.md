# Movie App menggunakan MERN Stack
<p>Link demo: https://sylphie-movie-app.vercel.app/</p>

### Deskripsi
Movie App adalah aplikasi web yang memungkinkan pengguna untuk mencari, menilai, dan menyimpan film favorit mereka. Aplikasi ini dibangun menggunakan teknologi MERN Stack, yaitu MongoDB sebagai database, Express.js sebagai backend framework, React.js sebagai frontend library, dan Node.js sebagai runtime environment.

### Fitur Utama
Pencarian Film: Pengguna dapat mencari film berdasarkan judul, genre, atau tahun rilis. <br>
Daftar Film Favorit: Pengguna dapat menyimpan film-film favorit mereka ke dalam daftar pribadi. <br>
Penilaian Film: Pengguna dapat memberikan penilaian atau ulasan untuk film yang mereka tonton. <br>
Informasi Detail Film: Halaman detail film menampilkan informasi lengkap, termasuk sinopsis, pemeran, dan ulasan pengguna. <br>
Otentikasi Pengguna: Fitur otentikasi untuk membuat akun pengguna dan login. <br>
### Teknologi yang Digunakan
MongoDB: Database untuk menyimpan data film, ulasan pengguna, dan informasi akun. <br>
Express.js: Backend framework untuk mengelola permintaan dan respons HTTP. <br>
React.js: Frontend library untuk membangun antarmuka pengguna yang responsif dan dinamis. <br>
Node.js: Runtime environment untuk menjalankan server backend. <br>

### instalasi
#### instalasi dependensi
cd server <br>
npm install <br>

cd client <br>
npm install <br>

#### konfigurasi database && API key TMDB
Buat file .env di dalam direktori backend dan atur variabel MONGODB_URI untuk koneksi ke MongoDB. <br>
pergi ke website TMDB API dan dapatkan API keynya, lalu masukkan dalam file .env <br>

#### jalankan server backend
cd server <br>
npm start <br>

#### jalankan server frontend
cd client <br>
npm start <br>

