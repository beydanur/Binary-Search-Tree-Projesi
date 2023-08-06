# Binary-Search-Tree-Projesi
VERİ YAPILARI VE ALGORİTMALAR

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

           
               7                             root 7'dir.
             /   \                           5, roottan küçük olduğundan rootun solunda bulunur.
           5       8                         1, roottan küçük ve 5'den de küçüktür,5'in solunda bulunur.
         /   \       \                       8, roottan büyüktür ve root'un sağında bulunur.
        1     6        9                     3, roottan küçük, 5'den küçük, 1'den büyüktür ,1'in sağında bulunur.
      /   \                                  6, roottan küçüktür, 5'den büyüktür ,5'in sağında bulunur.
    0       3                                0, roottan, 5'den, 1'den küçüktür. 1'in solunda bulunur.
          /   \                              9, roottan, 8'den büyüktür. 8'in sağında bulunur.
         2     4                             4, roottan, 5'den küçüktür, 1'den 3'den büyüktür.3'ün sağında bulunur.
                                             2, roottan, 5'den küçüktür, 1'den büyük ve 3'den küçüktür.3'ün solunda bulunur.
