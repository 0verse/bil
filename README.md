# bil programlama dili

```
ön  temel
    yazma
ek

ön  kişi
    yaş sayı
    ad  dizi
el

ön  yönler
    doğu
    batı
    kuzey
    güney
en

ön kopyalama (öz , kopya) ; dönme kopya : öz ; iş

ön  artırma (a tüm32 , b tüm32) tüm32
    dönme a + b
iş

ön  gösterge ()
    a1  :: 123 // değişmeyen
    a2  :  321 // değişen
    c1         : 1
    c2 tamsayı : 6000000000000
    c :: kopyalama (a1 , c1)
    b1      : "merhaba"
    b2 dizi : "dünya"
    yazma (b1 , b2)
    b2      : "yeni dünya"
    yazma (b1 , b2)
    yazma (a2 , b2)
    yazma (artırma (2 , 4))

    demet : (1 , "at" , 1.5)
    dizin : [1 , 2 , 3 , 4 , 5]
    lügat : {"balık" 1 , "aslan" 2}

    ön  demet
        1    => yazma ("sayı")
        "at" => yazma ("dizi")
        1.5  => yazma ("kayı")
    eş

    şimdi :: doğru

    ön  şimdi
        ön  b2 = "dünya"
            yazma ("dünyadır")
            bitir
        ya
        ön  b2 = "yeni dünya"
            yazma ("yeni dünyadır")
            bitir
        ya
        ön
            yazma ("başkadır")
            bitir
        ya
    an
uç
```
