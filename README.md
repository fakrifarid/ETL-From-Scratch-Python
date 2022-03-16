# ETL from Scratch with Python

Melakukan proses ETL (Extract, Transform, Load) dari scratch menggunakan Python.

Proses *Extract* dilakukan dengan melakukan web scraping pada suatu alamat web untuk mendapatkan data yang kemudian dimasukkan ke dalam DataFrame.

Proses *Transform* dilakukan dengan manipulasi data dari bentuk object menjadi bentuk desimal/float pada kolom `price` dan integer pada kolom `jumlah_review`. Selain itu juga dengan menambahkan `id` berupa kode unik dengan memanfaatkan UUID.

Proses *Load* dilakukan dengan menyimpan data hasil *Transform* ke dalam Database. Nantinya, data yang ada di dalam Database tersebut bisa dipergunakan untuk keperluan analisis maupun proses ETL yang lain.

## Library yang dibutuhkan

`os`, `uuid`, `requests`, `pandas`, `bs4(BeautifulSoup)`, `SQLAlchemy`, `pymysql`, `google.colab`, `python-dotenv`, ...

## Tools

- Google Colaboratory untuk seluruh proses ETL
- [DBeaver](http://dbeaver.io) untuk mengakses data yang telah tersimpan ke dalam Database

## Hasil load ke database

Berikut ini adalah screenshoot hasil load ke DB.

![image](https://user-images.githubusercontent.com/95616496/158556506-850af6b4-0393-4071-8858-12a8b09d7efa.png)
