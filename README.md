# paradigma
project
>>> class Person: 
	def __init__(self, name, age): 
		self.name = name
		self.age = age

>>> p1 = Person("VITA", 20)
>>> print(p1.name)
VITA
>>> print(p1.age)
20

//membuat kelas dengan nama Person, dalam class tersebut terdapat fungsi __init untuk menetapkan nilai ke properti objek yaitu name
dan age. dan setelah itu terjadi pemanggilan menggunakan syntax pendeklarasian yaitu self.
variabel p1 memanggil dari kelas Person dengan objek yang sudah diisi yaitu name VITA dan age 20. setelah itu perintah print
untuk menampilkan dari variabel dan objek yang dipanggil. 

>>> class Complex:
	def __init__(self, realpart, imagpart):
		self.r = realpart
		self.i = imagpart
	
>>> x = Complex(3.0, -4.5)
>>> x.r, x.i
(3.0, -4.5)

//membuat kelas dengan nama Complex. dalam class tersebut terdapat fungsi __init untuk menetapkan nilai ke properti objek yaitu realpart
dan imagpart. dan setelah itu terjadi pemanggilan menggunakan syntax pendeklarasian yaitu self. terdapat variabel r untuk memanggil nilai
dari objek realpart dan i dari imagpart. kemudian variabel x memanggil dari kelas Complex dengan objek yang telah diisi r 3.0 dan i -4.5.
lalu terjadi pemanggilan dari variabel x maka muncul (3.0, -4.5)
