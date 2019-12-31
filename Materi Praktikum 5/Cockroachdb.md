**cockroachdb**
<h1>penjelasan</h1>
<p>Basis data terdistribusi (distributed database) merupakan basis data yang perangkat-perangkat penyimpanannya terhubung dengan prosesor yang berbeda-beda. Salah satu atribut penting dari sebuah sistem basis data terdistribusi adalah meskipun sistem terdiri dari beberapa simpul (node), sistem harus tampak sebagai satu gugus (cluster) dari perspektif pengguna.
Sebuah sistem basis data terdistribusi berusaha menjawab paling sedikit tiga masalah berikut:
skalabilitas
ketersediaan (availability)
kehandalan (reliability)
Skalabilitas berkaitan dengan jumlah data dan transaksi yang mesti diproses oleh sistem. Ketersediaan berkaitan dengan uptime sistem yang idealnya harus selalu tersedia kapan pun pengguna butuh mengakses data dari sistem. Sementara kehandalan berkaitan dengan toleransi terhadap kerusakan (fault tolerance), bagaimana sistem tetap bisa melayani pengguna meski sebagian komponennya mengalami masalah.
Pada tulisan ini saya akan memaparkan pengalaman saya berkesperimen dengan salah satu teknologi basis data terdistribusi bernama CockroachDB. Dalam eksperimen yang akan kita simak bersama, saya akan mendemonstrasikan bagaimana CockroachDB menjawab persoalan skalabilitas, ketersediaan, dan kehandalan sebuah sistem.</p>
