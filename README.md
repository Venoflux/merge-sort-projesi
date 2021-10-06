# merge-sort-projesi
Patika'nın Veri Yapıları ve Algoritmalar kısmının proje ödevi.

## [16 , 21, 11, 8, 12, 22] -> Merge Sort
**1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

    -> [16, 21, 11, 8, 12, 22]
    -> [16, 21, 11] [8, 12, 22]
    -> [16, 21] [11] [8, 12] [22]
    -> [16] [21] [11] [8] [12] [22]
    -> [16, 21] [11] [8, 12] [22]
    -> [11, 16, 21] [8, 12, 22]
    -> [8, 11, 12, 16, 22]

**2) Big-O gösterimini yazınız.**

Average case olarak baz alınır ise **O(n $\times$ log n)** öyle ise 6 elemanlı bir array için **O(6 $\times$ log 6) = 15.5 $\approx$ 16**