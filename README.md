def faktoriyel(no):
    sonuc=1
    for i in range(1,no+1):
        sonuc=sonuc*i
    print("faktoriyel:  ",sonuc)
sayi=int(input("sayı gir:  "))
faktoriyel(sayi)
