# Web-Storage
Macam-Macam Web Storage dan Cara Mengetahui Dukungan Web Storage

| Aspek | sessionStorage | localStorage |
|-----------|------------|-----------|
| Masa berlaku data | Data hanya tersimpan selama sesi browser masih aktif (ditutup = hilang)	 | Data tetap tersimpan bahkan setelah browser ditutup dan dibuka kembali |
| Jangkauan data | Berlaku hanya dalam tab atau window yang sama | Berlaku untuk semua tab dan window di browser yang sama |
| Penghapusan data | Data otomatis hilang saat tab atau window ditutup | Data harus dihapus secara manual atau melalui kode (localStorage.removeItem()) |

<h3> Implikasi Perbedaan pada Kode </h1>
<p>
sessionStorage : Jika pengguna menutup browser atau menutup tab, maka data jumlah klik akan hilang dan kembali ke nol saat halaman dibuka lagi.
</p>

<p>
localStorage: Data jumlah klik akan tetap tersimpan meskipun pengguna menutup dan membuka kembali browser.
</p>
