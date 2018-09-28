# Membuat Table

Table dapat diartikan sebagai sebuah bagan yang terdiri dari kolom dan baris. Pada masing-masing lanjur baris dapat diisikan keterangan atau informasi yang akan disajikan dalam bentuk teks atau gambar, yag dikelompokkan berdasarkan kolom yang saling bersesuaian.

Sebagai contoh, berikut ini adalah tampilan dari sebuah tabel yang berisikan informasi data anggota, dimana ada kolom yaitu Nama dan Alamat.  

![](../.gitbook/assets/screen-shot-2018-09-23-at-13.52.38.png)

Dengan menggunakan HTML, table diatas dapat dihasilkan dengan kode sebagai berikut :

{% codetabs name="HTML", type="html" %}
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Table</title>
</head>
<body>
    <table border="1" width="35%">
        <thead>
            <tr>
                <th>Nama</th>
                <th>Alamat</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Bambang</td>
                <td>Way Halim</td>
            </tr>
            <tr>
                <td>Budi</td>
                <td>Sukabumi</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
{% endcodetabs %}

Adakalanya penulisan **thead** dan **tbody** tidak dituliskan. Hal ini tidak akan mengurangi hasil dari table yang kita inginkan.

{% codetabs name="HTML", type="html" %}
<table border="1" width="35%">
    <tr>
        <th>Nama</th>
        <th>Alamat</th>
    </tr>
    <tr>
        <td>Bambang</td>
        <td>Way Halim</td>
    </tr>
    <tr>
        <td>Budi</td>
        <td>Sukabumi</td>
    </tr>
</table>
{% endcodetabs %}

![](../.gitbook/assets/screen-shot-2018-09-23-at-13.51.10.png)

Walaupun mungkin hasil yang diharapkan sedikit berbeda dari sisi tampilan, tetapi secara fungsi sudah sesuai. 

