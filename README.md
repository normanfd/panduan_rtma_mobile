# Panduan Aplikasi Rtma Mobile
last update : 13 Maret 2024

Anda dapat mengklik tautan di bawah ini untuk menuju ke panduan yang sesuai:

## Instalasi dan update aplikasi
- [Install dan Update Aplikasi](0.1.install_dan_update_aplikasi.md)

## Arsip Dokumen Hasil Input
- [Arsip](arsip.md)

## Login Aplikasi
- [Login Aplikasi](0.0.Login.md)
- [Ubah Password](0.1.ubah_password.md)
- [Lupa Password](0.1.l.lupa_password.md)

## Fitur RTMA
- [Pencatatan dan Upload Online Rtma](1.0.catatan_fitur_rtma.md)
- [Fitur Input Penerimaan Kas](1.1.catatan_fitur_input_penerimaan_kas.md)
- [Simpan PDF & Arsip Rtma](1.2.simpan_pdf_rtma.md)
- [Riwayat Pencatatan dan Perubahan input pada Rtma](1.3.History_Input_Rtha.md)
- [Top Up Pembiayaan](1.4.TopUp%20Pembiayaan.md)

## Fitur Transaksi Pembiayaan
- [Input Transaksi Pembiayaan]()

## Fitur RTMA - Slip Simpanan / Slip Penarikan
- [Fitur Slip Simpanan](1.2.catatan_fitur_slip_simpanan.md)
- [Input Slip Simpanan](1.2.input_slip_simpanan.md)
- [Simpan PDF Slip Simpanan](1.2.simpan_pdf_slip_simpanan.md)
  
## Kartu Pengawasan Angsuran
- [Fitur KPA](2.0catatan_fitur_kpa.md)

## Registrasi Anggota
- [Fitur Registrasi Anggota](3.0.catatan_fitur_registrasi_anggota.md)

## Mutasi Anggota
- [Fitur Mutasi Anggota](4.0catatan_fitur_mutasi_anggota.md)

## Uji Kelayakan
- [Fitur Uji Kelayakan Anggota](5.0.catatan_uji_kelayakan.md)

## Registrasi Pembiayaan
- [Fitur Registrasi Pembiayaan](6.0.catatan_registrasi_pembiayaan.md)
- [Fitur Registrasi Pembiayaan Kiva](9.0.registrasi_pembiayaan_kiva.md)

## Analisis Pembiayaan
- [Fitur Analisis Pembiayaan](7.0.catatan_analisis_pembiayaan.md)

## Registrasi Simpanan
- [Fitur Registrasi Simpanan](8.0.catatan_registrasi_simpanan.md)

## Daftar Pembaruan Aplikasi
[Riwayat Pembaruan Aplikasi](0.2.Riwayat_Pembaruan_Aplikasi.md)

## perizinan aplikasi
[Panduan mengaktifkan izin aplikasi](izin_penggunaan_aplikasi.md)

## Panduan lainnya yang mungkin berguna untuk sebagian petugas
[Panduan Lainnya](lainnya.md)

## PENTING
Alur penggunaan Harian Rtma Mobile
```
Staff Lapang
A. Ketika dikantor
    1. Login Aplikasi
    2. Download data offline dengan wifi / paket data dikantor
    3. input transaksi pembiayaan (untuk kasus top up pembiayaan) lewati jika tidak ada
        3.1 pelunasan pembiayaan sebelumnya
        3.2 posting pelunasan pembiayaan sebelumnya
        3.2 otor pembiayaan baru bmi online
    4. generate rtha sesuai rembug
    5. generate kartu pengawas angsuran sesuai hari rembug
    6. generate uji kelayakan sesuai hari rembug
    7. jika ada pencairan hari ini
        7.1 minta asmen adm ttd persetujuan
        7.2 minta mancab ttd persetujuan
        7.3 sinkronisasi ttd formulir yang cair hari ini
    8. jika ada mutasi anggota hari ini
        8.1 minta asmen adm ttd
        8.2 minta mancab ttd
        8.3 sinkronisasi ttd formulir yang keluar hari ini

B. Ketika dilapang
    1. Input rtha (transaksi penagihan angsuran pembiayaan, setoran & penarikan simpanan, dan transaksi ziswaf per rembug)
        1.1 input absensi
        1.2 input uang yang diterima tiap kelompok dan menentukan selisih
        1.3 input pembayaran angsuran
        1.4 input pelunasan pembayaran angsuran
        1.5 input pencairan pembayaran angsuran
        1.6 input setoran simpanan
        1.7 input penarikan simpanan
        1.8 input setoran ziswaf
        1.9 input ttd ketua rembug
        2.0 input ttd petugas
        2.1 simpan rtha
        3.1 input bukti penarikan simpanan
        3.2 input penerimaan kasus
        3.3 input catatan (apapun, misal selisih, janji bayar, tdk bayar, dan lain2)
        3.4 print bukti slip penarikan 
        3.5 simpan pdf rtha
        3.6 simpan pdf slip simpanan
        3.7 upload online (jika ada internet)
            3.7.1 kalau ada anggota baru, upload setelah otor anggota baru
            3.7.2 kalau ada mutasi anggota, upload setelah otor mutasi

    2. input registrasi anggota baru (jika ada)
        2.1 registrasi anggota baru
        2.2 input setoran awal di rtha
        2.3 input penerimaan kas
        2.4 upload reg anggota baru (jika ada internet)
        2.5 request otor administrasi anggota baru ke asmen adm (bmi online)
        2.5 upload rtha (jika ada internet)

    3. input pengajuan mutasi anggota keluar (jika ada) 
        3.1 pengajuan baru 
            3.1.1 input mutasi (umumnya anggota keluar setelah h+1 minggu)

        3.2 mutasi hari ini
            3.2.1 unggah foto serah terima
            3.2.2 upload online mutasi anggota
            3.2.3 otor mutasi keluar anggota

    4. input registrasi pembiayaan (jika ada)
        4.1 pengajuan baru
            4.1.1 input formulir
            4.1.2 simpan pdf
            4.1.3 upload online (jika ada internet)

        4.2 pencairan
            4.2.1 input ttd anggota pencairan, ttd petugas pencairan, foto serah terima
            4.2.2 upload online
            4.2.3 input ttd mancab (dikantor)
                4.2.3.1 ttd langsung ditab
                4.2.3.2 ttd dengan sinkron ditab
            4.2.4 sinkronisasi ttd mancab
            4.2.5 upload online
            4.2.6 posting rtha

    5. input registrasi simpanan (jika ada)
        5.1 input formulir

    6. uji kelayakan (jika ada)
        6.1 input formulir

    7. input analisis pembiayaan (jika ada)
        7.1 input formulir

    8. lanjut ke Rp selanjutnya

C. ketika kembali ke kantor
    1. rtha 
        1.1 minta asmen keuangan ttd rtha1
        1.2 upload online rtha
        1.3 simpan pdf rtha
        1.4 upload pdf ke gdrive cabang
    2. jika ada reg anggota
        2.1 minta mancab utk ttd formulir
            2.1.1 melalui sinkronisasi data
            2.1.2 ttd langsung ditab
        2.2 sinkronisasi data utk dpt ttd mancab
        2.3 simpan pdf
        2.4 upload pdf ke gdrive cabang
    4. jika ada mutasi anggota
        4.1 upload online formulir
        4.2 simpan pdf
        4.3 upload pdf ke gdrive cabang
    5. jika ada uji kelayakan
        5.1 minta mancab ttd uji kelayakan
            5.1.1 melalui sinkronisasi data
            5.1.2 ttd langsung ditab
        5.2 simpan pdf
        5.3 upload pdf ke gdrive cabang
    6. jika ada pencairan reg pembiayaan
        6.1 minta mancab ttd pencairan
            6.1.1 melalui sinkronisasi data
            6.1.2 ttd langsung ditab
        6.2 simpan pdf
        6.3 upload pdf ke gdrive cabang
```

![Upload Online Sinkronisasi dan Perbarui data](https://github.com/normanfd/panduan_rtma_mobile/assets/37357830/b26121af-c901-4ff0-ad4e-0df0ea222f71)
