#Pengertian Vue-CLI

Vue-CLI adalah tools standar untuk memudahkan penyetelan/pembuatan aplikasi vue baru

#Main tool bels pada vue cli:

-CLI adalah paket npm yang dipasang secara global, yang menyediakan fungsionalitas inti melalui perintah vue. Hal ini memungkinkan kita untuk men-scaffold proyek baru dengan mudah (vue create), atau hanya dengan cepat membuat prototipe ide mentah (vue serve). Jika kita menginginkan kontrol yang lebih konkret dan visual atas proyek-proyek kita, kita dapat membuka versi GUI dari CLI dengan menjalankan perintah vue ui.

-CLI Service adalah ketergantungan pengembangan (file biner vue-cli-service), diinstal secara lokal ke dalam setiap proyek yang dibuat dengan CLI. Hal ini memungkinkan kita untuk mengembangkan proyek kita (vue-cli-service serve), mengemasnya untuk produksi (vue-cli-service build), dan juga untuk memeriksa konfigurasi proyek webpack internal (vue-cli-service inspect).

-CLI Plugins adalah paket npm yang menyediakan fitur tambahan untuk proyek kita. Nama itu dimulai dengan @vue/cli-plugin- (untuk plugin built-in) atau vue-cli-plugin- (untuk plugin community). Kita dapat menambahkannya setiap saat dari proses pengembangan melalui perintah vue add.

#Fitur-fitur pada Vue-CLI

-Plugin-based architecture. Vue CLI benar-benar dibangun di seputar plugin, yang membuatnya sangat fleksibel dan dapat diperluas. Kita dapat memilih plugin mana yang akan ditambahkan selama proses pembuatan proyek. Tetapi kita tidak terbatas hanya untuk ini, kita dapat menambahkan sejumlah plugin kapan saja setelah pembuatan proyek. Vue CLI benar-benar dapat dikonfigurasi, diperluas, dan dapat diupgrade.

-Seperangkat plugin resmi yang sudah terpasang, yang mengintegrasikan tools first-class dari ekosistem front-end (Babel, ESLint, TypeScript, PWA, Jest, Mocha, Cypress, dan Nightwatch).

-Single default preset, yang dapat kita modifikasi sesuai kebutuhan kita selama pembuatan proyek atau sesudahnya.

-Tidak perlu eject. Berbeda dengan tools CLI React dan Angular, kita dapat dengan aman memeriksa dan mengubah konfigurasi webpack proyek kita kapan saja setelah pembuatan tanpa perlu mengeluarkan aplikasi dan beralih ke konfigurasi manual.
Support Multi-page.

-Prototipe instan tanpa konfigurasi apa pun.

-Target build yang berbeda memungkinkan kita memproduksi berbagai versi proyek kita. Kita dapat menggunakan satu dan basis kode yang sama dan membuatnya sebagai aplikasi, pustaka, atau komponen web.

-Fitur mode modern. Ini akan membangun aplikasi kita untuk browser modern, tetapi dengan fallback otomatis untuk yang lebih lama. Keren, ya?
GUI yang lengkap untuk membuat, memperbarui, dan mengelola proyek-proyek kompleks dengan mudah.

-UI Plugin API. Vue UI memaparkan API plugin yang dapat kita gunakan untuk menambahkan fungsi khusus ke versi GUI dari CLI.

-Banyak plugin yang berguna dari komunitas.

#Task
Pada task kali ini membuat todo dengan menggunakan vue cli versi 4.5.15 berdasarkan di video
