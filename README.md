
# Latihan Python di Pycharm
### Cara Menjalankan Pycharm 

- Pertama anda  Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini
 
![Screenshot (78)](https://user-images.githubusercontent.com/115678171/198815436-8756894e-4eb0-4b58-81fe-165afda78652.png)

- Selanjutnya membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan
 
![Screenshot (79)](https://user-images.githubusercontent.com/115678171/198815862-fbfc7ae9-dc11-4184-898a-4711596e2e7a.png)
![Screenshot (80)](https://user-images.githubusercontent.com/115678171/198815863-332a5b4f-c020-40b9-8331-4f98f5794ff9.png)

 ## Latihan 1
 ```python
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
print("variable a=",a)
print("variable b=",b)
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

#koversi nilai variable
a=int(a)
b=int(b)
print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%s".format(a,b) %(a/b))
 
 ![Screenshot (30)](https://user-images.githubusercontent.com/115714443/199500164-631db697-e943-4a7d-af0c-bdfbeb62d680.png)

## latihan 2

```python
#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')

# penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')

# string format
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

# string format
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10)
```
![Screenshot (31)](https://user-images.githubusercontent.com/115714443/199501999-7d75bfec-e96d-4b76-9aeb-892cb1c3ae9c.png)

# Latihan 3
1. Anda masukan code seperti dibawah ini dan lalu Run
```python
string = ""

x = int(input("Masukkan angka :"))
bar = x
# Looping Baris
while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri		
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1		
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1	

	string = string + "\n\n"
	bar = bar - 1

bar = 1	
# Looping Baris
while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri	
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1	
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri	
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
print (string)
````
![Screenshot (32)](https://user-images.githubusercontent.com/115714443/199503053-e333e49d-8e82-44dc-a26a-99f70e7d093f.png)
![Screenshot (33)](https://user-images.githubusercontent.com/115714443/199503115-6a19f854-c260-4227-ad50-1d87c831aab8.png)


## Menghitung Luas Dan Keliling Lingkaran
1. Masukan code di bawah ini lalu run
```python
import math

r = float(input("Masukan Jari-jari : "))

luas = math.pi * (r * r)
keliling = 2 * math.pi * r

print("Luas Lingkaran \t\t= ", luas)
print("Keliling Lingkaran\t= ", keliling)
````
![Screenshot (82)](https://user-images.githubusercontent.com/115678171/198817214-75aca326-f313-47fe-a27c-a7fe79f08332.png)

*Hasil Run*
![Screenshot (81)](https://user-images.githubusercontent.com/115678171/198817233-c6c11b97-3aaf-48ed-b7c0-e2ff8c813896.png)

## Flowchart Menghitung luas dan keliling lingkaran

![Flowchart-menghitung-luas-keliling-lingkaran-1](https://user-images.githubusercontent.com/115714443/199498739-05faaebe-78b7-436b-b2b8-b1da74d5d389.png)

*Terima Kasih*
