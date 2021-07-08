Folder ini mengandung 2 file.
1. Assessment Table.ipynb
iPython Notebook berisi cara memasukkan data di assessments.csv ke sqlite db.
Step-step yang dilakukan:
- Mengambil data dengan Pandas
- Koneksi ke SqLite
- Membuat table baru dan memasukkan data ke table
- Query result (tanpa join) menjadi dataframe
- Menulis dataframe ke Excel

2. Full Function
iPython Notebook berisi program memasukkan data seluruh .csv ke sqlite db, 
dan menjalankan tugas untuk query sesuai yang diminta di NG3.

Karena saya malas ngetik koding panjang XD, saya membuat function yang bisa dijalankan 
berkali-kali untuk memasukkan data .csv ke sqlite, adaptif terhadap bentuk table dan kolom-kolomnya.