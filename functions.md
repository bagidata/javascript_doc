## Self-Invoking Functions

Fungsi ekspresi bisa dibuat menjadi "Self invoking".

Ekspresi self-invoking bisa dipanggil atau dijalankan secara otomatis tanpa perlu dipanggil.

Fungsi ekspresi akan dijalankan secara otomatis jika ekspresi diikuti dengan ().

Anda tidak bisa self-invoke (memanggil sendiri) fungsi deklarasi.


Anda HARUS menambahkan parentheses (tanda kurung) disekitar fungsi untuk menunjukan bahwa itu adalah fungsi ekspresi :

    (function () {
        var x = "Hello!!"; 
    })(); // Tanda kurung dibagian akhir artinya fungsi akan dijalankan otomatis.


> Fungsi di atas sebenarnya adalah fungsi self-invoking anonim (fungsi tanpa nama)

Sumber : https://www.w3schools.com/js/js_function_definition.asp
