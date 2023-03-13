## Binary Search Tree Projesi

1- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

```
1- 7 sayısı Root olarak belirlenir.
2- 5 sayısı 7'den küçük olduğu için 7 sayısının soluna yazılır.
3- 1 sayısı 7 ve 5'ten küçük olduğu için 5 sayısının soluna eklenir.
4- 8 sayısı 7'den büyük olduğu için 7 sayısının sağına eklenir.
5- 3 sayısı 5 ve 7'den küçük olduğu için sola 1'den büyük olduğu için 1'in sağına yazılır.
6- 6 sayısı 7'den küçük olduğu için sola 5'ten büyük olduğu için 5'in sağına yazılır.
7- 0 sayısı hepsinden küçük olsuğu için en sola yani 1'in soluna yazılır.
8- 9 sayısı 7'den ve 8'den büyük olduğunsan 8in sağına yazılır.
9- 4 sayısı 7 ve 5'twn küçük olsuğu için sola 3 ten büyük olduğu için 3'ün sağına yazılır.
10- 2 sayısı 7 ve 5'ten küçük ve 1'den büyük olduğu için ve 3'ten küçük olduğu için 3'ün soluna eklenir.

```
```
                                7
                             5     8
                           1   6     9 
                         0   3 
                           2    4
```                        
