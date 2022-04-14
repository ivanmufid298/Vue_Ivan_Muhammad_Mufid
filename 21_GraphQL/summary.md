#GraphQL Overview
GraphQL adalah bahasa query untuk API Anda, dan runtime sisi server untuk mengeksekusi kueri dengan menggunakan sistem tipe yang Anda tetapkan untuk data Anda. GraphQL meminimalkan jumlah data yang perlu ditransfer melalui jaringan. Dengan graphQL kita dapat menggunakan satu titik akhir tunggal ( /graphQL ) untuk setiap permintaan yang diperlukan.

#Hasura & Heroku
Hasura adalah layanan yang menyediakan graphql dan rest api. Dikelola penuh di cloud hasura atau dihosting sendiri. Buka https://hasura.io/ dan buat server graphql baru Anda sendiri, Heroku adalah platform cloud sebagai layanan yang mendukung beberapa bahasa pemrograman. Heroku juga menyediakan database postgres gratis. Buka https://heroku.com/ dan buat layanan Anda sendiri

#Apollo setup
Apollo Client adalah perpustakaan manajemen status komprehensif untuk JavaScript yang memungkinkan kami mengelola data lokal dan jarak jauh dengan GraphQL. Gunakan untuk mengambil, menyimpan, dan memodifikasi data aplikasi, sambil memperbarui UI secara otomatis. Pustaka inti @apollo/client menyediakan integrasi bawaan dengan React. Kami menggunakan klien Apollo untuk melakukan operasi GraphQL (kueri, mutasi, dan berlangganan) di dalam aplikasi React atau Next JS kami. Klien Apollo bekerja dengan baik dengan server GraphQL (Hasura, Apollo Server, dll)

#Query
You can use the ApolloQuery (or apollo-query) component to have watched Apollo queries directly in your template. After reading this page, see the API Reference for all the possible options.

#Mutation
Anda dapat menggunakan komponen ApolloMutation (atau apollo-mutation) untuk memanggil mutasi Apollo langsung di template Anda.

#Subsciption
Anda dapat berlangganan lebih banyak data dengan komponen ApolloSubscribeToMore (atau apollo-subscribe-to-more). Anda dapat memasukkan sebanyak mungkin yang Anda inginkan ke dalam komponen <ApolloQuery>.
