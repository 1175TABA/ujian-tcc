<p>Mengidentifikasi nama Gambar Docker yang dikonfigurasi untuk menjalankan Redis. Dengan Docker, semua wadah dimulai berdasarkan Gambar Docker. Gambar-gambar ini berisi semua yang diperlukan untuk memulai proses; host tidak memerlukan konfigurasi atau dependensi.</p>
<p>CLI Docker memiliki perintah yang disebut run yang akan memulai wadah berdasarkan Gambar Docker. Strukturnya adalah buruh pelabuhan yang menjalankan <options> <image-name></p>
<p>Secara default, Docker akan menjalankan perintah di latar depan. Untuk berjalan di latar belakang, opsi -d harus ditentukan.

docker run -d redis</p>
<p>Secara default, Docker akan menjalankan versi terbaru yang tersedia. Jika versi tertentu diperlukan, itu dapat ditentukan sebagai tag, misalnya, versi 3.2 akan menjadi buruh pelabuhan run -d redis: 3.2.</p>
