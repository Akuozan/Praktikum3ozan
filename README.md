(#praktikum 3-tipe data,variabel,dan operator 

nama:fauzan giri

kelas: Ti24A5 

nim : 312410535

mata kuliah : Bahasa pemrograman 

## mencari bilangan terbesar dari bilangan yang di input kan 
program ini menentukan bilangan terbesar dari serangkaian bilangin yang di input kan hingga input 0, program ini menggunakan loop`while`dan kondisi`if` untuk memperbaharui nilai terbesar yang di temukan 
## flowchart program 
![foto](https://github.com/Akuozan/Praktikum3ozan/edit/main/README.md


largest = float('-inf')  # Menginisialisasi Largest dengan -∞

while True:
    print("Enter 0 to stop")
    n = float(input("Input a number: "))  # Meminta input dari pengguna

    if n == 0:
        break  # Keluar dari loop jika input adalah 0

    if n > largest:
        largest = n  # Update nilai Largest jika n lebih besar

if largest == float('-inf'):
    print("No numbers were entered.")
else:
    print("The largest number is:", largest)
```
