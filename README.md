#praktikum
tugas praktikum bahasa pemrograman pertemuan ke 5
# Program untuk menentukan bilangan terbesar dari tiga bilangan

# Input tiga bilangan dari pengguna
a = int(input("Masukkan bilangan pertama: "))
b = int(input("Masukkan bilangan kedua: "))
c = int(input("Masukkan bilangan ketiga: "))

# Menentukan bilangan terbesar
if a > b and a > c:
    terbesar = a
elif b > c:
    terbesar = b
else:
    terbesar = c

# Menampilkan hasil bilangan terbesar
print("Bilangan terbesar adalah:", terbesar)

  penjelasan:
Input Tiga Bilangan:
Program meminta pengguna untuk memasukkan tiga bilangan bulat, yang kemudian disimpan dalam variabel a, b, dan c menggunakan fungsi input() dan dikonversi menjadi tipe data int.
Menentukan Bilangan Terbesar:
Program menggunakan pernyataan if-elif-else untuk menentukan bilangan terbesar dari ketiga variabel.
Jika a lebih besar dari b dan c, maka a dianggap terbesar.
Jika kondisi pertama tidak terpenuhi, tetapi b lebih besar dari c, maka b dianggap terbesar.
Jika tidak ada kondisi yang terpenuhi, maka c adalah yang terbesar.
Setelah menentukan bilangan terbesar, program menampilkan hasil tersebut ke layar.
python
print("Bilangan terbesar adalah:", terbesar)
contoh eksekusi program
Masukkan bilangan pertama: 13
Masukkan bilangan kedua: 16
Masukkan bilangan ketiga: 20
Bilangan terbesar adalah: 20
Pada contoh di atas, pengguna memasukkan 13,16,dan 20.Program menentukan bahwa 20 adalah bilangan terbesar dan menampilkannya sebagai hasil

max_value = 0

code python N
  max_value = 0

while True:
    n = int(input("Input N (masukkan 0 untuk berhenti): "))
    
    if n == 0:
        break
        
    if n > max_value:
        max_value = n

print("Nilai maksimum adalah:", max_value)  
penjelasan:Kode Python di atas digunakan untuk mencari nilai maksimum dari sekumpulan angka yang dimasukkan oleh pengguna. Berikut adalah penjelasan tiap barisnya:

max_value = 0: Variabel max_value diinisialisasi dengan nilai 0, yang akan menyimpan nilai terbesar dari angka yang dimasukkan.

while True:: Memulai loop while yang berjalan terus-menerus (infinite loop) hingga mencapai perintah break di dalamnya.

n = int(input("Input N (masukkan 0 untuk berhenti): ")): Pengguna diminta memasukkan angka n. Jika pengguna memasukkan 0, loop akan berhenti. Jika pengguna memasukkan angka selain 0, program akan terus berjalan dan memproses angka tersebut.

if n == 0:: Mengecek apakah n bernilai 0. Jika benar, maka program keluar dari loop dengan perintah break.

if n > max_value:: Jika n lebih besar dari max_value, maka max_value diperbarui dengan nilai n. Dengan demikian, max_value selalu menyimpan angka terbesar yang dimasukkan sejauh ini.

print("Nilai maksimum adalah:", max_value): Setelah loop selesai (ketika pengguna memasukkan 0), program mencetak nilai terbesar yang ditemukan.

Contoh Jalannya Program:
Input N (masukkan 0 untuk berhenti): 37
Input N (masukkan 0 untuk berhenti): 40
Input N (masukkan 0 untuk berhenti): 53
Input N (masukkan 0 untuk berhenti): 0
Nilai maksimum adalah: 53
Jika pengguna memasukkan angka secara berurutan:37,40,53,0,maka program akan menampilkan "Nilai maksimum adalah:53"
