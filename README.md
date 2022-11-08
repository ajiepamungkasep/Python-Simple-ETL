# Python-Simple-ETL
## Pengantar
Project ini mengambil data dari suatu kompetisi Hackathon yang diselenggarakan DQLab dengan nama DQThon. Hackathon merupakan kompetisi membuat software yang dilaksanakan secara marathon yang biasanya diikuti secara tim. Umumnya, peserta hackathon diminta untuk mengembangkan platform (mobile, web, desktop, dll.) dalam kurun waktu tertentu untuk menyelesaikan permasalahan yang sudah ditetapkan/didefinisikan oleh penyelenggara ataupun berdasarkan tema yang dipilih oleh tim tersebut. Untuk bisa mengikuti hackathon dari suatu instansi, calon peserta diwajibkan untuk mendaftarkan diri mereka pada situs/form tertentu dengan memasukkan beberapa informasi yang diminta oleh penyelenggara tersebut.

Extract, Transform dan Load (ETL) merupakan kumpulan proses untuk "memindahkan" data dari satu tempat ke tempat lain.
Tempat yang dimaksud adalah dari sumber data (bisa berupa database aplikasi, file, logs, database dari 3rd party, dan lainnya) ke data warehouse.

Dataset terdiri dari 5000 baris data (5000 pendaftar) dengan format CSV (Comma-separated values) dan memiliki beberapa kolom diantaranya:

participant_id: ID dari peserta/partisipan hackathon. Kolom ini bersifat unique sehingga antar peserta pasti memiliki ID yang berbeda
first_name: nama depan peserta
last_name: nama belakang peserta
birth_date: tanggal lahir peserta
address: alamat tempat tinggal peserta
phone_number: nomor hp/telepon peserta
country: negara asal peserta
institute: institusi peserta saat ini, bisa berupa nama perusahaan maupun nama universitas
occupation: pekerjaan peserta saat ini
register_time: waktu peserta melakukan pendaftaran hackathon dalam second
Pada proyek ini akan menghasilkan beberapa kolom dengan memanfaatkan kolom-kolom yang ada, sehingga akhir dari proyek ini berupa hasil transformasi data dengan beberapa kolom baru selain dari 10 kolom diatas.

