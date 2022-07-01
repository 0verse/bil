# bil programlama dili

```
temel
    yazma
önek

kişi
    sayı yaş
    dizi ad
yapı

yönler
    doğu
    batı
    kuzey
    güney
sıra

tam16 kopyalama "tüm16 öz , tam16 kopya" ; dönme kopya : öz ; ekiş

artırma "adsız sayı a, adsız sayı b"
    a + b
ekiş

gösterge
    tüm16 a1 :: 123 // değişmeyen
    sayı  a2  : 321 // değişen
    tam16 c1  : 1
    tamsayı c2  : 6000000000000
    c :: kopyalama "tüm16 a1 , tam16 c1"
    b1 : 'merhaba'
    dizi b2 : 'dünya'
    yazma "b1 , b2"
    b2 : 'yeni dünya'
    yazma "b1 , b2"
    yazma "a2 , b2"
    yazma "artırma "2 , 4""

    demet : (1 , 'at' , 1.5)
    dizin : [1 , 2 , 3 , 4 , 5]
    lügat : {'balık' : 1 , 'aslan' : 2}

    bool şimdi :: 1
    süre şimdi
        eğer b2 = 'dünya'
            yazma "'dünyadır'"
            bitir
        veya b2 = 'yeni dünya'
            yazma "'yeni dünyadır'"
            bitir
        duru
    duru
öniş

```
