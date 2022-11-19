# Veri Yapıları ve Algoritmalar
## Proje 3
## Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
***

Root dizinin ilk elemanı olan 7 dir.

```
  7
 / \
```
İkinci eleman olan 5, 7 'den küçüktür. Büyük olan elemanlar her zaman sağ tarafa yazılacağı için 5, 7'nin sol tarafına alınır.

```
  7
 / \
5
```
Üçüncü elaman olan 1, 7'den daha küçük olduğu için soldan devam edilir. 5'ten de küçük olduğu 1, için 5 'in soluna yazılır. Küçük olan elemanlar her aşamada sol tarafta yer almalıdır.

```
    7
   / \
  5
 / \
1
```
Dördüncü eleman olan 8, 7'den daha büyüktür. Büyük olan eleman, daha büyük olduğu elemanın sağ tarafına alınmalıdır. 

```
    7
   / \
  5   8
 / \
1

```
Beşinci eleman olan 3, 7'den küçük olduğu için soldan devam edilir. 3, 5'ten de küçük olup 1'den büyük olduğu için 3 sayısı 1'in sağına yazılır.

```
     7
    / \
   5   8
  / \
 1
/ \ 
   3 

```
Altıncı eleman olan 6, 7'den küçük olduğu için soldan devam edilir. 5'ten büyük olduğu için 5'in sağına yazılır.

```

     7
    / \
   5   8
  / \
 1   6
/ \ 
   3 
```

Yedinci eleman olan 0, 7'den küçüktür ve soldan devam edilir. 5'ten küçük olduğu için yine soldan devam edilir. 1'den de küçük olduğu için 1'in soluna yazılır.

```
      7
     / \
    5   8
   / \
  1   6
 / \ 
0   3 
```
Sekizinci eleman olan 9, 7 'den büyüktür. Sağdan devam edilir. 8'den de büyük olduğu için 8'in sağına yazılır.

```
        7
       / \
     5     8
    / \   / \
   1   6     9
  / \ 
 0   3 
 ```
 Dokuzuncu eleman olan 4,7'den küçüktür ve soldan devam edilir. 5'ten de küçük olduğu için yine soldan devam edilir. 1'den büyük olduğu için sağa geçilir. 3'ten büyük olduğu için 3'ün sağına yazılır.
 ```
        7
       / \
     5     8
    / \   / \
   1   6     9
  / \ 
 0   3 
    / \
       4
```
Onuncu ve son eleman olan 2, 7'den küçük olduğu için soldan devam edilir. 5'ten küçük olduğu için yine soldan devam edilir. 1'den büyük olduğu için sağdan devam edilir. 3'ten küçük olduğu için 3'ün soluna yazılır.
```
        7
       / \
     5     8
    / \   / \
   1   6     9
  / \ 
 0   3 
    / \
   2   4

```
Root 7'dir. Sağında 8, solunda 5 bulunur.