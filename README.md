# binary-search-tree-projesi
#### [Patika.dev](www.patika.dev/) sitesindeki Veri Yapıları ve Algoritmalar dersleri sonu "Binary Search Tree Projesi" 

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları (Görsel anlatım)

|  |  |     |  |  |  |  |  |  |  |  |
|--|--|-    |- |- |- |- |- |- |- |- |
|  |  |     |  |  |  | 7|  |  |  |  |  
|  |  |     |  |  | /|  |\ |  |  |  | 
|  |  |     |  | 5|  |  |  |8 |  |  | 
|  |  |     | /|  |\ |  |  |  |\ |  | 
|  |  |  1  |  |  |  |6 |  |  |  | 9|
|  | /|     |\ |  |  |  |  |  |  |  |
| 0|  |     |  | 3|  |  |  |  |  |  |
|  |  |     | /|  |\ |  |  |  |  |  |
|  |  | 2   |  |  |  |4 |  |  |  |  |

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları (Yazılı anlatım) 
Binary-Search-Tree basitçe şöyle çalışıyor; bize verilen sayı dizisinden bir sayıyı ele alıyoruz ve buna **root** ismini veriyoruz. Sırayla sayılara bakmaya başlıyoruz. Teker teker ilerliyoruz. Baktığımız sayı root 'tan küçükse soluna, büyükse sağına yazıyoruz. 
``` 
root olarak 7'yi kabul ettim ve 7'yi başa yazdım. Bu adım bitti.
```
```
Dizedeki sayılara sırayla bakıyorum. 7'den sonra gelen 5 sayısı 7'den küçük olduğu için 7'nin soluna yazdım. Bu adım bitti. 
```
``` 
1 sayısı 7'den küçük olduğu için ve aynı zamanda 5'den küçük olduğu için 5'in soluna yazdım. Bu adım bitti. 
```
```
8 sayısı 7'den büyük olduğu için 7'nin sağına yazdım. Bu adım bitti.
```
```
3 sayısı, 7'den küçük ve aynı zamanda 5'ten küçük ama 1'den büyük. Bu yüzden 1'in sağına yazdım. Bu adım bitti.
```
```
6 sayısı 7'den küçük, 5'ten büyük olduğu için 5'in sağına yazdım. Bu adım bitti.
```
```
0 sayısı 7, 5 ve 1'den küçük olduğu için sola ve en sona yazdım. Bu adım bitti.
```
```
9 sayısı 7'den büyük olduğu için 7'nin ve 8'in sağına yazdım. Bu adım bitti.
```
```
4 sayısı 7 ve 5'ten küçük ama 3'ten büyüktür. Bu nedenle 3'ün sağına yazdım. Bu adım bitti.
```
```
2 sayısı 7'den ve 3'ten küçük olduğu için 3'ün soluna yazdım. Bu adım bitti.
```
```
Bütün sayılar bitti
```
