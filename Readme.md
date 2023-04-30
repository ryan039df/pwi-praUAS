# Laporan Progress pembuatan proyek 

## Progress - 1

1. Apa saja yang sudah dilakukan?

a. Menentukan sensor dan aktuator yang akan dipakai dalam setiap subsistem

b. Menentukan rentang pengukuran sensor dan hasil keluaran aktuator dari setiap sensor dan aktuator yang ada


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Smart Farm
1. Susu Hewani dan Telur
a. Sensor kebersihan kandang (50% - 100%)
b. Sensor jenis pakan yang dipakai (1, 2, 3)
c. Sensor hormon prolaktin sapi (10% - 60%)
d. Aktuator Output susu dan telur (0 - 1000 pack)

2. Daging Merah
a. Sensor umur rata-rata ternak sapi (0 - 4 tahun)
b. Sensor porsi makan sapi (60% - 90%)
c. Sensor jumlah sapi (0 - 250 ekor)
d. Aktuator Output daging merah sapi (0 - 750 kg)

3. Daging Putih
a. Sensor kecepatan sirkulasi udara (0.15 - 0.3 m/s)
b. Sensor persentase makanan protein tinggi (20% - 25%)
c. Sensor kepadatan ayam dalam satu kandang (0% - 100%)
d. Aktuator Output daging putih ayam (0 - 500 kg)

Smart Plantation
1. Sumber Karbohidrat: Beras, Gandum, Jagung 
a. Sensor deteksi tanaman yang diproduksi (1, 2, 3)
b. Sensor kadar air tiap kali penyiraman (0 - 25000 Liter [1 hektar lahan] )
c. Sensor frekuensi pemakaian pestisida (1 - 4 kali/bulan)
d. Aktuator output sumber karbohidrat (0 - 400 kg)

2. Sayuran
a. Sensor luas lahan ( 0,1 - 1 hektar)
b. Sensor kelembaban tanah (60% - 90%)
c. Sensor deteksi hama (10 - 200 /m^2)
d. Aktuator output sayuran (0 - 400 kg)

3. Buah-buahan
a. Sensor deteksi kematangan (0% - 100%)
b. Sensor besar buah (0% - 100%)
c. Sensor jumlah pupuk yang dipakai (0 - 2kg pohon/tahun)
d. Aktuator output buah-buahan (0 - 500 kg)

Smart Restaurant
1. Deteksi musim (Nov - Feb: Winter --> Daging merah dibutuhkan, Summer --> sayuran> Daging, Fall --> semua sama rata, Spring --> Daging putih dibutuhkan). Random musim
a. Sensor bulan (1 - 12)
b. Sensor suhu (-9 - 30 celcius degree)
c. Sensor kelembaban udara (30% - 80%)
d. Aktuator musim (Spring, Summer, Fall, Winter)

2. Deteksi hasil penjualan. Random hasil penjualan
a. Sensor rata-rata rating (0 - 5 bintang)
b. Sensor counter pesanan berhasil (0 - 2500 / bulan)
c. Sensor rata-rata menu yang terjual (0 - 4 tingkat kemahalan)
d. Aktuator output hasil penjualan (0 - 125 juta / bulan)

3. Deteksi jumlah pengunjung restoran. Random jumlah pengunjung
a. Sensor jumlah pembayaran di kasir (0 - 2500 kali/bulan)
b. Sensor cctv image + human recognition (0 - 100 pengunjung/hari)
c. Sensor penggunaan meja (0 - 100 kali/hari)
d. Aktuator jumlah pengunjung (0 - 2500 pengunjung/bulan)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

c. Membuat kerangka tampilan UI dari dashboard Node-Red

<img width="285" alt="image" src="https://user-images.githubusercontent.com/62742933/235365058-a3767a58-e793-417e-9189-f78b168e20e1.png">
<img width="278" alt="image" src="https://user-images.githubusercontent.com/62742933/235365073-fc0bde8a-ea31-44be-98fe-992ff2d40209.png">
<img width="277" alt="image" src="https://user-images.githubusercontent.com/62742933/235365083-a6f42e99-abad-4b15-b907-1257f592fa18.png">

2. Apa saja kendala yang dihadapi?

a. Menentukan nama sensor yang akan dipakai dalam setiap subsistem (tidak boleh sama)

b. Menentukan rentang pengukuran yang cukup umum agar sesuai dengan kondisi riil

c. Penggunaan gauge untuk UI dashboard Node-Red dengan ukuran auto tidak cukup untuk 3 subsistem


3. Apa yang sudah dilakukan untuk mengatasi kendala tersebut?

a. Mencari inspirasi dari chatgpt untuk faktor-faktor apa saja yang mempengaruhi dari masing-masing subsistem

b. Mencari perkiraan rentang ukuran umum dari setiap faktor yang diukur oleh masing-masing sensor dari masing-masing subsistem

c. Penyesuaian ukuran gauge agar 3 subsistem bisa muat dalam satu UI dashboard 1 flow Node-Red


4. Apa rencana yang akan dikerjakan berikutnya?

a. Mengganti nama sensor dan aktuator yang ada di Node-Red dengan yang sudah ditentukan

b. Menyempurnakan proses kerja Node-Red

c. Menyempurnakan hasil tampilan dari Node-Red dashboard

