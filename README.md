# Latihan 9 Bahasa Pemrograman
## Buat sebuah list sebanyak 5 elemen dengan nilai bebas
### Akses list:
* Tampilkan elemen ke 3
* Ambil nilai elemen ke 2 sampai elemen ke 4
* Ambil elemen terakhir

## Programnya
``````python
list1 = ["ival", "zah", "alfi", "12", "04"]
print("Tampilkan element ke-3 :", list1[3]) 
print("Ambil nilai element 2-4", list1[2:5])
print("Ambil element terakhir :", list1[0:4])

print( 45*"=", "\n")
``````
### Ubah elemen list:
* Ubah elemen ke 4 dengan nilai lainnya
* Ubah elemen ke 4 sampai dengan elemen terakhir

## Programnya
``````python
list2 = [11, 12, 13, 14, 15]
print(list2)
list2[4] = "Element 4"
print(list2)

print()

list3 = ["Siapa", "Kamu", "Ngatur", "Hidup", "Aku"]
print("Sebelum di ubah :", list3)
list3[0:6] = ["S", "K", "N", "H", "A"]
print("Setelah di ubah :", list3, "\n")
``````
### Tambah elemen list:
* Ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
* Tambah list B dengan nilai string
* Tambah list B dengan 3 nilai
* Gabungkan list B dengan list A

## Programnya
``````python
lista  = [1, 2, 3, 4, 5]
print("ListA\n", lista)
listb  = [6, 7, 8]
print("ListB Sebelum di tambahkan :\n", listb, "\n")

lista  = [1 ,2 ,3 ,4 ,5]
print("ListA\n", lista)
listb  = [6 ,7 ,8 ]
listb.insert(2, lista[0:2])  
print("ListB Sesudah di tambahkan :\n", listb, "\n")

# Mendambahkan list B dengan nilai string
listb.append("Timey")
print("ListB :\n", listb,"\n")

# Menambahkan list B dengan 3 Nilai
listb.extend([10, 12, 14])
print("Mendambahkan ListB dengan 3 nilai :\n", listb,"\n")
# Menggabungkan ListA dan ListB 
listN = lista + listb
print("Gabungan listA & ListB: \n", listN)
``````
### Outputnya :

![Alt text](<ss praktikum5/Screenshot (39).png>)

![Alt text](<ss praktikum5/Screenshot (40).png>)