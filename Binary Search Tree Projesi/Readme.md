Proje 3

Soru: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap: Binary Search, her düğümün solundaki koldan ulaşılabilecek bütün verilerin düğümün değerinden küçük, sağ kolundan ulaşılabilecek verilerin değerinin o düğümün değerinden büyük olmasını şart koşar.

1.adım: Dizinin en başındaki eleman root olarak seçilir ve root 7 olur.

2.adım: Dizinin ikinci elemanı olan 5 sayısı 7'den küçük olduğunda 7'nin soluna ekledik.

3.adım: Dizinin üçüncü elamanı olan 1 sayısı 5'ten ve 7'den küçük olduğunda 7 ve 5'in soluna ekledik.

4.adım: Dizinin dördüncü elemanı olan 8 sayısı 7'den büyük olduğunda 7'nin sağına ekledik.

5.adım: Dizinin beşinci elemanı olan 3 sayısı 7'den ve 5'ten küçük olduğunda 5'in soluna, 1'den büyük olduğunda 1'in sağına ekledik.

6.adım: Dizinin altıncı elemanı olan 6 sayısı 7'den küçük olduğunda 7'nin soluna, 5'ten büyük olduğunda 5'in sağına ekledik.

7.adım: Dizinin yedinci elemanı 0 sayısı 7'den, 5'ten ve 1'den küçük olduğunda 1'in soluna ekledik.

8.adım: Dizinin sekizinci elemanı olan 9 sayısı 7'den ve 8'den büyük olduğunda 8'in sağına ekledik.

9.adım: Dizinin dokuzuncu elemanı 4 sayısı 7'den ve 5'ten küçük olduğunda 5'in soluna, 1'den ve 3'ten büyük olduğunda 3'ün sağına ekledik.

10.adım: Dizinin onuncu elemanı olan 2 sayısı 7'den ve 5'ten küçük olduğunda 5'in soluna, 1'den büyük olduğunda 1'in sağına ve 3'ten küçük olduğunda 3'ün soluna ekledik.

Sonuç:            7
                 / \
                5   8
               / \   \
              1   6   9
             / \
            0   3
               / \
              2   4	