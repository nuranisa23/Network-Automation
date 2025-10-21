# Network-Automation
Program ini berfungsi untuk **mengecek status semua interface jaringan** di sistem Linux dan **menonaktifkan interface yang sedang down**.
Skrip akan menampilkan nama serta status tiap interface, lalu jika ditemukan interface (selain `lo`) yang berstatus `down`, program akan otomatis menjalankan perintah `ip link set <interface> down` untuk menonaktifkannya.
Tujuannya adalah untuk mempermudah pemantauan serta pengelolaan interface jaringan agar tetap sesuai kondisi operasionalnya.
