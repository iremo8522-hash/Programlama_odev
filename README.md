ad = input("Adınızı giriniz: ")
soyad = input("Soyadınızı giriniz: ")
tamad = ad + " " + soyad
print("Tam Adınız:", tamad)

sayı1 = int(input("Birinci sayıyı giriniz: "))
sayı2 = int(input("İkinci sayıyı giriniz: "))
toplam = sayı1 + sayı2
fark = sayı1 - sayı2
çarpım = sayı1 * sayı2
print("Toplam:", toplam)
print("Fark:", fark)
print("Çarpım:", çarpım)

yas = int(input("Yaşınızı giriniz: "))
büyükmü = yas > 18
print("18 yaşından büyük mü?:", büyükmü)

kısakenar = int(input("Kısa kenar uzunluğunu giriniz: "))
uzunkenar = int(input("Uzun kenar uzunluğunu giriniz: "))
alan = kısakenar * uzunkenar
çevre = 2 * (kısakenar + uzunkenar)
print("Dikdörtgenin Alanı:", alan)
print("Dikdörtgenin Çevresi:", çevre)

sayı = int(input("Bir sayı giriniz: "))
pozitifmi = sayı > 0
print("Sayı pozitif mi?:", pozitifmi)

kelime = input("Bir kelime giriniz: ")
ilküç = kelime[0:3] 
soniki = kelime[-2:]
print("Kelimenin ilk 3 harfi:", ilküç)
print("Kelimenin son 2 harfi:", soniki)

sayı1 = int(input("Birinci tam sayıyı giriniz: "))
sayı2 = int(input("İkinci tam sayıyı giriniz: "))
ortalama = float((sayı1 + sayı2) / 2)
print("Sayıların Ortalaması:", ortalama)

sayı1 = int(input("Birinci sayıyı giriniz: "))
sayı2 = int(input("İkinci sayıyı giriniz: "))
çiftmi1 = sayı1 % 2 == 0
çiftmi2 = sayı2 % 2 == 0
ikisideçiftmi = çiftmi1 and çiftmi2
print("İki sayı da çift mi?:", ikisideçiftmi)

metin = input("Bir metin giriniz: ")
uzunluk = len(metin)
büyükharfmetin = metin.upper()
print("Metnin Uzunluğu:", uzunluk)
print("Metnin Büyük Harf Hali:", büyükharfmetin)

yarıçap = int(input("Dairenin yarıçapını giriniz: "))
PI = 3.14
alan = PI * (yarıçap ** 2)
print("Dairenin Alanı:", alan)

sayı1 = float(input("Birinci sayıyı giriniz: "))
sayı2 = float(input("İkinci sayıyı giriniz: "))
eşitmi = sayı1 == sayı2       
büyükmü = sayı1 > sayı2       
print("Sayılar eşit mi? (sayı1 == sayı2):", eşitmi)
print("Birinci sayı ikinciden büyük mü? (sayı1 > sayı2):", büyükmü)

sayı = int(input("Bir tam sayı giriniz: "))
bölünür3 = sayı % 3 == 0
ölünür5 = sayı % 5 == 0
bölünürmü = bölünür3 and bölünür5
print("Sayı hem 3'e hem de 5'e tam bölünüyor mu?:", bölünürmü)
bölünür5 = sayı % 5 == 0
bölünürmü = bölünür3 and bölünür5
print("Sayı hem 3'e hem de 5'e tam bölünüyor mu?:", bölünürmü)
