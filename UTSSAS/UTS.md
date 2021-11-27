Nama : Nadila Chusnul K - ( 1202190020 ) 
Kelas : IT 02-01 

 ### Ujian Tengan Semester Sistem Administrasi Server 
Download ISO Installer windows server 2022 menggunakan link di bawah ini terlebih dahulu 
      ```bash
    https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
    ```

     Ketika download selesai, kemudian buka virtual box membuat machine  dengan nama Windows Server 2022 kemudian setting version menjadi windows 10 ( 64 bit ) dan  next 
![A1](Aset/p1.jpg)
        
    Atur memory dengan size 2048 MB kemudian next 
![A1](Aset/p2.jpg)

    Buat virtual machine pada hard disk kemudian next 
![A1](Aset/p3.jpg)

    Buat  Hard disk file type kemudian next
![A1](Aset/p4.jpg)

    Selanjutnya buat stroge on physical hard disk dan next saja 
![A1](Aset/p5.jpg)

    Buat File Location and size kemudian next 
![A1](Aset/p6.jpg)

    Masuk ke > Setting > Network dan ubah Nat menjandi Bridge Adapter lalu ok 
![A1](Aset/p7.jpg)

    Klik Start kemudia masukan file yang sudah di download tadi 
![A1](Aset/p8.jpg)

    Kemudian klik next dan install now
![A1](Aset/p9.jpg)
![A1](aset/p27.jpg)

    Pilih Windows Server 2022 Standart (desktop) dan next
![A1](aset/p10.jpg)

    Centang dan next kemudian 
    Pilih custome : install Microsoft Server Operating System Only (advanced)
![A1](aset/p11.jpg)
![A1](aset/p12.jpg)

    Klik next dan tunggu proses installasi hingga selesai 
![A1](aset/p13.jpg)
![A1](aset/p14.jpg)

    Setelah proses installasi selesai maka sistem akan reboot ke cpmplate proses
![A1](aset/p15.jpg)

    Enter dan buat password baru pada customize setting 
![A1](aset/p16.jpg)

    Setelah selesai buat password, akses menu input > keyboard > Insert Ctrl + Alt + Del , kemudian enter masukkan password yang sudah dibuat 
![A1](aset/p17.jpg)
![A1](aset/p18.jpg)

    Kemudian kembali ke menu Device > Insert Guest Additions Cd Image >  cd Drive Virtual box > pilih VBox WindiwsAdditions
![A1](aset/p19.jpg)
![A1](aset/p20.jpg)
![A1](aset/p21.jpg)

    Lalu klik install 
![A1](aset/p22.jpg)
![A1](aset/p23.jpg)

    Reboot machine dan akses menu input – keyboard – Insert Ctrl + Alt + Del , kemudian enter masukkan password kembali 
![A1](aset/p24.jpg)

    Jalankan winver untuk memvalidasi mesin 
![A1](aset/p25.jpg)

    Windows Server 2022 terinstall 
![A1](aset/p26.jpg)

###  INSTALLASI ACTIVE DIRECTORY DOMAIN SERVER 

    Ubah nama di windows powershell  dengan ketik > “rename -computer -Newname Server 2022” 
![A1](aset/p28.jpg)

    Kemudian masuk pada server manager pilih menu Manage > Add roles features dan next 
![A1](aset/p29.jpg)

    Kemudian pilih Role-Based  or feature-based installation dan next 
![A1](aset/p30.jpg)

    Pilih select a server from the server pool , setelah itu pilih active directory domain server 
![A1](aset/p31.jpg)

    Setelah itu klik add features 
![A1](aset/p32.jpg)

    Masuk pada features kemudian centang Group Policy Management dan next 
![A1](aset/p33.jpg)

    Kemudian masuk pada confirm installation selection dan install 
![A1](aset/p34.jpg)
![A1](aset/p35.jpg)

    Mohon maaf bapak pada saat installasi sangatlah lama jadi saya belum bisa lanjut ke tahap setting ip 
