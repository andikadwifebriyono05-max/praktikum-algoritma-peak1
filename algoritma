print("Program Menentukan Jumlah Hari Dalam Bulan")
ulang = "y"

while ulang.lower() == "y":
    bulan = int(input("Masukkan bulan (1-12): "))
    tahun = int(input("Masukkan tahun: "))

    # Tentukan jumlah hari
    if bulan == 1 or bulan == 3 or bulan == 5 or bulan == 7 or bulan == 8 or bulan == 10 or bulan == 12:
        jumlah_hari = 31
    elif bulan == 4 or bulan == 6 or bulan == 9 or bulan == 11:
        jumlah_hari = 30
    elif bulan == 2:
        # Mengecek tahun kabisat
        if (tahun % 4 == 0 and tahun % 100 != 0) or (tahun % 400 == 0):
            jumlah_hari = 29
        else:
            jumlah_hari = 28
    else:
        jumlah_hari = 0

    if jumlah_hari != 0:
        print(f"Jumlah hari pada bulan {bulan} tahun {tahun} adalah {jumlah_hari} hari.\n")
    else:
        print("Input bulan tidak valid!\n")

    ulang = input("Apakah ingin menghitung lagi? (y/t): ")

print("Program selesai. Terima kasih!")
