#Andreas Nugroho
#71200646
#Deni adalah seorang pegawai di salah satu agency. Karena untuk mencegah covid, manager dari perusaan tersebut
#meminta ke deni untuk membuatkan aplikasi absen yang tidak perlu menggunakan sidik jari. karena deni tidak
#mampu membuatnya lalu deni meminta tolong kepada kamu untuk membuatkan aplikasi yang di minta deni.
#Bantulah deni agar bisa menyelesaikan tugasnya.

#input
#Nama
#Kehadiran

#proses
#if dan perulangan

#output
#data absensi dalam bentuk file txt

while True:
    print("=== Selamat Datang ===")
    print("1. Absen Pegawai\n2. Tampilkan Data (Khusus Admin)\n3. keluar")
    pilih = int(input("Masukkan Pilihan Anda: "))

    if pilih == 1:
        buka = open("absen.txt","a")
        nama = input("Masukkan Nama :")
        print("=== Absen Hari Ini ===")
        print("1.Hadir \n2.Tidak Hadir")
        absen = int(input("Masukkan Pilihan Anda: "))
        if absen == 1:
            absen = "Hadir"
            print(nama,"Berhasil Absen!")
        elif absen == 2:
            absen = "Tidak Hadir"
            print(nama,"Berhasil Absen!")
        else:
            print("Inputan tidak ada!")
        hasil = "\nNama: {}\nAbsen Hari Ini: {}\n----".format(nama,absen)
        buka.write(hasil)
        buka.close()

    elif pilih == 2:
        nama = input("Username :")
        kode = input("Password :")
        if nama == "admin" and kode == "admin":
            buka = open("absen.txt","r")
            baca = buka.read()
            print(baca)
            buka.close()

    elif pilih == 3:
        print("Berhasil Keluar!")
        break

    else:
        print("Inputan tidak ada!")
