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
