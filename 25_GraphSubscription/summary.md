#Graphql subscribtion
Spesifikasi GraphQL tidak menentukan protokol khusus untuk mengirim permintaan berlangganan. Pustaka JavaScript populer pertama yang mengimplementasikan langganan melalui WebSocket disebut subscriptions-transport-ws

#Operasi
Seperti kueri, langganan memungkinkan Anda mengambil data. Tidak seperti kueri, subscribtion adalah operasi jangka panjang yang dapat mengubah hasilnya seiring waktu. 

#Fungsi
-Perubahan kecil dan bertahap pada objek besar . Berulang kali polling untuk objek besar itu mahal, terutama ketika sebagian besar bidang objek jarang berubah. Sebagai gantinya, Anda dapat mengambil status awal objek dengan kueri, dan server Anda dapat secara proaktif mendorong pembaruan ke masing-masing bidang saat terjadi.
-Pembaruan waktu nyata dengan latensi rendah . Misalnya, klien aplikasi obrolan ingin menerima pesan baru segera setelah tersedia.

#Task
Melakukan subscription pada project react sebelumnya
