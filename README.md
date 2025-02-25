def toplama(a, b):
    return a + b

def cikarma(a, b):
    return a - b

def carpma(a, b):
    return a * b

def bolme(a, b):
    return a / b if b != 0 else "Tanımsız"

print("İşlem Seçin: +, -, *, /")
islem = input("İşlem: ")
sayi1 = float(input("Birinci sayı: "))
sayi2 = float(input("İkinci sayı: "))

if islem == "+":
    print("Sonuç:", toplama(sayi1, sayi2))
elif islem == "-":
    print("Sonuç:", cikarma(sayi1, sayi2))
elif islem == "*":
    print("Sonuç:", carpma(sayi1, sayi2))
elif islem == "/":
    print("Sonuç:", bolme(sayi1, sayi2))
else:
    print("Geçersiz işlem!")
# HesapMakinesi
