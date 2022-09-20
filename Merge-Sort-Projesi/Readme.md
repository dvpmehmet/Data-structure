Proje 2
Sorular:
[16,21,11,8,12,22] -> Merge Sort

Soru: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Cevap:
               [16,21,11,8,12,22]

      [16,21,11]                 [8,12,22]   

    [16]   [21,11]           [8,12]       [22]

   [16]      [21] [11]      [8]   [12]       [22]

  [16]         [11,21].     [8,12]          [22]
    
       [11,16,21]                   [8,12,22]
         
                [8,11,12,16,21,22]


Soru: Big-O gösterimini yazınız.

Cevap:O(n*logn)--> O(6*(log6)