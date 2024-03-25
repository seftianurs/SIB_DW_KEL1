# SIB_DW_KEL1

## Repositori ini berisi assignment materi python part 4 dan 5

## Task 1 (Basic OOP)
    Yang didalamnya berisi 3 metode:

    extract(): akan membaca data dari sebuah file CSV (Misalkan, marketing_data.csv)

    transform(): akan melakukan pembersihan dan transformasi sederhana pada data (seperti mengubah format tanggal atau membersihkan nilai yang kosong)

    store(): akan menyimpan data yang telah ditransformasi ke dalam struktur data DataFrame.

   # Variable:
    df = variable untuk menyimpan dataframe yang berisi data_marketing
    data_transformed = variable yg berisi data marketing_data yang telah di transformasi
    etl_processor: variable ini merupakan objek dari kelas MarketingDataETL. Dibuat dengan menggunakan fungsi MarketingDataETL('/content/marketing_data.csv')


## Task 2 (Inheritance & Polymorphism)
    Menggunakan inheritance untuk membuat class TargetedMarketingETL yang mewarisi dari MarketingDataETL. 

    Lalu menambahkan metode segment_customers() yang mengelompokkan pelanggan berdasarkan kriteria tertentu (misalnya, pengeluaran total atau kategori produk yang dibeli).

    Mendemonstrasi polymorphism dengan meng-override metode transform() dalam TargetedMarketingETL untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi.

 # Variable
