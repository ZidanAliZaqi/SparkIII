# SparkIII
1. Lihat dan load dataset worldcities.csv
2. Sebelumnya tentukan Schema dari DataFrame menggunakan StructType (Optional) Column pada dataset worldcities.csv antara lain: 
("city", "city_ascii", "lat", "lng", "country", "iso2", "iso3", "admin_name", "capital", "population", "id") File menggunakan separated “,” 
(silakan cek datasetnya terlebih dahulu)
3. Buat program menggunakan SparkSQL untuk mencari total populasi setiap negara
(group by “country” lalu sum field “population” ) 
4. Lalu urutkan dari yang paling tinggi total populasinya (gunakan desc)
5. Simpan pada variable results, kemudian print 
(print sample saja misal 5 data pertama)
6. Simpan data results ke dalam bentuk csv, json atau parquet
(pilih salah satu format saja)
