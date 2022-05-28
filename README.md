#Merge Sort
Dizi 2 elemanlı alt dizilere bölünür ve her bir alt dizi kendi içinde sıralanır. alt diziler diğer alt dizilerle kıyaslanarak orijinal dizi için sıralama yapılır.

**1.**    
|  16 | 21 | 11 | 8  | 12 |22|
| ----|----|----|----|----|--|

**2.** 

|  16 | 21 | 11 | 
| ----|----|----| 

| 8  | 12 |22|
|----|----|--|

**3.** 

|  16 | 21 |
| ----|----|

| 11 | 
|----| 

| 8  | 12 |
|----|----|

|22|
|--|

**4.**
|  16 |
| ----|

|  21 |
| ----|

|  11 |
| ----|

|  8 |
| ---|

|  12 |
| ----|

|  22 |
| ----|

**5.**
|  8 | 11 | 12 |
| ----|----|----|----|----|--|

|16  | 21 |22|
|----|----|--|


**6**
|  8 | 11 | 12 | 16  | 21 |22|
| ----|----|----|----|----|--|


# Big-O

Merge Sort sıralama işleminde her bir adımda diziyi ikiye bölme işlemi uygularız ve ikiye bölünen alt dizilerde sıralama işlemi yaparız.

$T(n)=n⋅T(1)+log_{2}n⋅n = log_{2}n⋅n$

$O(nlog_{2}n)$
