# Catatan Penting Fitur Rtma (Last update (12/09/2023))
beberapa kasus dan pertanyaan yang sering ditanyakan sebagai berikut : 

## Kasus 1 : Registrasi Anggota -> Generate Rtma
- Jika terdapat Anggota Baru yang didaftarkan melalui **BMIOnline** atau melalui **RtmaMobile** yang telah diupload Online sebelum Generate Rtma, 
maka setoran awal (pokok, minggon, dan adm) tidak dapat diinput melalui Rtma Mobile

| No | Solusi | Rekomendasi
| ----------- | ----------- |---|
| 1 | Registrasi anggota melalui rtma mobile (jangan diupload online sebelum generate rtma) untuk urutan bebas boleh registrasi anggota dulu atau generate rtma dulu asal anggota tidak diupload online terlebih dahulu| ✅
| 2 | Input setoran awal melalui Transaksi perorangan BMI Online dan mengakibatkan selisih Penerimaan Kas pada RtmaMobile | |

## Kasus 2 : Terdapat Anggota Baru didaftarkan melalui BMI Online
- Jika terdapat Anggota Baru yang didaftarkan melalui BMI Online, maka setoran awal (pokok, minggon, dan adm) tidak dapat diinput melalui Rtma Mobile

| No | Solusi | Rekomendasi
| ----------- | ----------- |---|
| 1 | Registrasi anggota melalui RtmaMobile dan input setoran awal pada Fitur Rtma RtmaMobile | ✅
| 2 | Input setoran awal melalui Transaksi perorangan BMI Online | |

## Kasus 3 : Terdapat Top Up pembiayaan untuk produk pembiayaan yang sama
```diff
- Catatan : Rtma Mobile saat ini belum mendukung fitur Top Up Pembiayaan
```
- Jika terdapat Top up (pelunasan dan pencairan) pada hari yang sama maka fitur Rtma pada RtmaMobile akan menyebabkan selisih pada rekap penerimaan kas RtmaMobile (senilai pencairan pembiayaan)

| No | Solusi | Rekomendasi
| ----------- | ----------- |---|
| 1 | lakukan pelunasan pembiayaan sebelumnya pada Transaksi pembiayaan perorangan di BmiOnline, kemudian Generate Rtma Mobile dan lakukan pencairan melalui rtma mobile| ✅

