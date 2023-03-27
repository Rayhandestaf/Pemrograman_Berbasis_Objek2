SCRIPT PROCEDURAL:
# Tugas Minggu 1
# NIM : 210511075
# Nama : Rayhan Desta F
# Kelas : TI21B
class KonversiSuhu:
@staticmethod
def celsius1_to_fahrenheit(celsius):
return (9/5) * celsius1 + 32
@staticmethod
def celsius2_to_reamur(celsius):
return (4/5) * celsius2
@staticmethod
def celsius3_to_kelvin(celsius):
return celsius3 + 273.15
celsius1 = 75
celsius2 = 30
celsius3 = 60
fahrenheit = KonversiSuhu.celsius1_to_fahrenheit(celsius1)
reamur = KonversiSuhu.celsius2_to_reamur(celsius2)
kelvin = KonversiSuhu.celsius3_to_kelvin(celsius3)
print("konversi",celsius1, "derajat celcius adalah ",fahrenheit, "derajat
fahrenheit")
print("konversi",celsius2, "derajat celcius adalah ",reamur, "derajat Reamur")
print("konversi",celsius3, "derajat celcius adalah ",kelvin, "derajat Kelvin")


SCRIPT OOP:
# Tugas Praktikum
# NIM : 210511075
# Nama : Rayhan Desta F
# Kelas : TI21B
# 2. Buatlah Class yang mengimplementasikan Object Oriented Programming, beri
nama: celcius_oop.py
class KonversiSuhu:
def init (self, celcius):
self.celcius = celcius
def to_reamur(self):
return (4/5) * self.celcius
def to_kelvin(self):
return self.celcius + 273.15
def to_fahrenheit(self):
return (9/5) * self.celcius + 32
suhu = KonversiSuhu(60)
fahrenheit = suhu.to_fahrenheit()
kelvin = suhu.to_kelvin()
reamur = suhu.to_reamur()
print(f"{suhu.celcius} derajat Celsius = {reamur} derajat Reamur")
print(f"{suhu.celcius} derajat Celsius = {kelvin} Kelvin")
print(f"{suhu.celcius} derajat Celsius = {fahrenheit} derajat Fahrenheit")
