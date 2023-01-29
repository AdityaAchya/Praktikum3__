# Praktikum3__
Repository ini dibuat untuk memenuhi tugas Pertemuan 6 - Bahasa Pemrograman.

Nama : Aditya Achya Ananta Nur

NIM : 312210714

Kelas : TI.22.C.9

# Latihan 1

1. Penggunaan End

![1](https://user-images.githubusercontent.com/123864099/215335104-da321511-062c-4f3b-a207-6c2c2d039e54.png)


    #penggunaan end
    print('A', end='')
    print('B', end='')
    print('C', end='')
    print()
    print('X')
    print('Y')
    print('Z')

Output :

![2](https://user-images.githubusercontent.com/123864099/215335343-cf72b074-2029-41ee-aace-5fae1cb95207.png)


2. Penggunaan Separator

![Penggunaan Separator](https://user-images.githubusercontent.com/123864099/215335365-160603de-f8e3-44ad-9f65-60ece06e4442.png)


    #penggunaan separator
    w, x, y, z = 10, 15, 20, 25
    print(w, x, y, z)
    print(w, x, y, z, sep=',')
    print(w, x, y, z, sep='')
    print(w, x, y, z, sep=':')
    print(w, x, y, z, sep='-----')

Output :


![Penggunaan Separator](https://user-images.githubusercontent.com/123864099/215335464-ce0fb95c-9976-4c9f-9b58-a8b62efe7583.png)


3. Penggunaan String -1

![String Format](https://user-images.githubusercontent.com/123864099/215335547-786907d1-3ebc-412d-966a-3f4d391d57db.png)


    #string format
    print(0, 10**0)
    print(1, 10**1)
    print(2, 10**2)
    print(3, 10**3)
    print(4, 10**4)
    print(5, 10**5)
    print(6, 10**6)
    print(7, 10**7)
    print(8, 10**8)
    print(9, 10**9)
    print(10, 10**10)

Output :


![Output String Format](https://user-images.githubusercontent.com/123864099/215335575-32433530-884b-4d5f-b4f4-0bd9b9e52ca5.png)


4. Penggunaan String -2

![String Format1](https://user-images.githubusercontent.com/123864099/215335594-f352fb7f-b90d-4431-b390-ba407aaf586c.png)


    #string format
    print('{0:>3} {1:>16}'. format(0, 10**0))
    print('{0:>3} {1:>16}'. format(1, 10**1))
    print('{0:>3} {1:>16}'. format(2, 10**2))
    print('{0:>3} {1:>16}'. format(3, 10**3))
    print('{0:>3} {1:>16}'. format(4, 10**4))
    print('{0:>3} {1:>16}'. format(5, 10**5))
    print('{0:>3} {1:>16}'. format(6, 10**6))
    print('{0:>3} {1:>16}'. format(7, 10**7))
    print('{0:>3} {1:>16}'. format(8, 10**8))
    print('{0:>3} {1:>16}'. format(9, 10**9))
    print('{0:>3} {1:>16}'. format(10, 10**10))

Output :

![Output String Format1](https://user-images.githubusercontent.com/123864099/215335618-54f63215-ab54-40ef-802b-738652cb3a4f.png)


# Latihan 2

Program :

![Code Latihan](https://user-images.githubusercontent.com/123864099/215335685-b935f8ec-f290-43e7-b4e6-b25f9b65cb17.png)


    print("Latihan 2")

    #input nilai variabel
    a = input("Masukkan nilai a : ")
    b = input("Masukkan nilai b : ")

    #cetak nilai variabel
    print("Variabel a : ", a)
    print("Variabel b : ", b)

    #cetak hasil operasi kedua variabel dengan String Format
    print("Hasil Penggabungan {0}&{1}=%d".format(a,b)%int(a+b))

    #konversi nilai variabel
    a = int(a)
    b = int(b)
    print("Hasil Penjumlahan {0}+{1}=%d".format(a,b)%int(a+b))
    print("Hasil Pembagian {0}/{1}=%d".format(a,b)%int(a/b))

Output :


![Output Code](https://user-images.githubusercontent.com/123864099/215335863-68309da7-6aeb-496f-ad61-99afacb34c59.png)


# Latihan 3

Program :


![Code Belah Ketupat](https://user-images.githubusercontent.com/123864099/215335916-7510e2cc-6eea-41f3-82e4-9b7710611f31.png)


    #Belah Ketupat
    print('{0:>16}'.format("*"))
    print('{0:>17}'.format("***"))
    print('{0:>18}'.format("*****"))
    print('{0:>19}'.format("*******"))
    print('{0:>20}'.format("*********"))
    print('{0:>19}'.format("*******"))
    print('{0:>18}'.format("*****"))
    print('{0:>17}'.format("***"))
    print('{0:>16}'.format("*"))

Output :


![Output Belah Ketupat](https://user-images.githubusercontent.com/123864099/215335929-127df595-a58b-4f86-a53d-3f778ba874e8.png)



# Program Menghitung Luas dan Keliling Lingkaran Menggunakan Python

1. Buat File Menghitung Luas Lingkaran

![1](https://user-images.githubusercontent.com/123864099/215337301-c669084e-3fea-4327-873b-570fa2d56b7a.PNG)


2. Memasukkan library math pada awal program (otomatisasi rumus phi tanpa mendekalarasikan)

![2](https://user-images.githubusercontent.com/123864099/215337373-3b8f68d9-a5bf-490e-a760-9a3cf3a6e85f.PNG)

    #memasukkan libraries math
    import math

3. Membuat judul awal program

![3](https://user-images.githubusercontent.com/123864099/215337381-f7b73ec1-23c2-4b9c-bb88-918395ca5c2b.PNG)

    print("")
    print("-------------------------------------------------")
    print("Program Menghitung Luas dan Keliling Lingkaran")
    print("---------------ADITYA ACHYA ANANTA NUR---------------")
    print("--------------------312210714--------------------")

4. Membuat proses inputan jari-jari oleh user

![4](https://user-images.githubusercontent.com/123864099/215337406-ee45b54b-07b8-458d-a745-efc8552fe00c.PNG)

    #user memasukkan nilai jari-jari pada lingkaran
    r = float(input("Masukkan Jari-jari : "))

5. Membuat proses perhitungan luas dan keliling

![5](https://user-images.githubusercontent.com/123864099/215337467-511afea2-17ca-4a85-9b63-362274b859a6.png)


    #rumus perhitungan luas & keliling 
    luas = math.pi*r*r
    keliling = 2*math.pi*r

6. Run program yang sudah dibuat

![7](https://user-images.githubusercontent.com/123864099/215337758-277c075b-084f-45c7-b5c6-c529cde611b6.png)


7. Tampilan hasil ke layar

![6](https://user-images.githubusercontent.com/123864099/215337763-7f5b198d-e268-48d9-877c-8d139e8c15a1.PNG)


# Flowchart Menghitung Luas dan Keliling Lingkaran

![Flowchart py](https://user-images.githubusercontent.com/123864099/215337779-6a754dee-12b3-4cb5-9e26-a30b04c6ea06.png)

Sekian yang dapat saya sampaikan.

## TERIMA KASIH
### ADITYA ACHYA ANANTA NUR - 312210714 - TI.22.C. - TEKNIK INFORMATIKA - UNIVERSITAS PELITA BANGSA

