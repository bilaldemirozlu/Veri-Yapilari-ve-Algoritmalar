# Proje 3

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. Örnek: root x'dir. root'un sağında y bulunur. Solunda z bulunur vb.

root = 5

                   __________[5]___________
                   |                      |
          ________[3]_____          _____[7]____
          |              |          |          |
     ____[1]____        [4]        [6]        [8]____
     |         |                                    |
    [0]       [2]                                  [9]



- Root 5'tir.

- 3 5'ten küçük olduğu için root'un solunda bulunur.

- 1 5'ten ve 3'ten küçük olduğu için 3'ün solunda bulunur.

- 2 1'den büyük ve 3'ten küçük olduğu için 1 ve 3 arasında bulunur.

- 4 3'ten büyük ve 5'ten küçük olduğu için 3 ve 5 arasında bulunur.

- 0 hepsinden küçük olduğu için en solda bulunur.

- 7 5'ten büyük olduğu için root'un sağında bulunur.

- 6 5'ten büyük ve 7'den küçük olduğu için 5 ve 7 arasında bulunur.

- 8 5'ten ve 7'den büyük olduğu için 7'nin sağında bulunur.

- 9 hepsinden büyük olduğu için en sağda bulunur.
