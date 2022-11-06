# binarysearchtree
Kodluyoruz Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
|**root=7**       |  | 7|  |
**5 sayısı 7'den küçük olduğunda 7'nin soluna ekledik**
|   Açıklama  |     |  |  |
|--           |-    |- |- |
|             |     |  | 7|  
|             |     | /|  | 
|**5 ekledik**|**5**|  |  | 
**1 sayısı 5'ten ve 7'den küçük olduğunda 7 ve 5'in soluna ekledik** 
|     Açıklama  |     |  |  |  |  |
|             --|--   |--|- |- |- |
|               |     |  |  |  | 7|  
|               |     |  |  | /|  | 
|               |     |  | 5|  |  |  
|               |     | /|  |  |  | 
|**1 ekledik**  |**1**|  |  |  |  |
**8 sayısı 7'den büyük olduğunda 7'nin sağına ekledik** 
| Açıklama      |  |  |  |  |  |  |     |
|--             |--|--|- |- |- |- |-    |
|               |  |  |  |  | 7|  |     |  
|               |  |  |  | /|  |\ |     | 
|**8 ekledik**  |  |  | 5|  |  |  |**8**| 
|               |  | /|  |  |  |  |     | 
|               | 1|  |  |  |  |  |     |
**3 sayısı  7'den ve 5'ten küçük  olduğunda 5'in soluna, 1'den büyük olduğunda 1'in sağına ekledik**  
|  Açıklama     |  |  |     |  |  |  |  |
|--             |--|--|-    |- |- |- |- |
|               |  |  |     |  | 7|  |  |  
|               |  |  |     | /|  |\ |  | 
|               |  |  | 5   |  |  |  |8 | 
|               |  | /|     |  |  |  |  | 
|               | 1|  |     |  |  |  |  |
|               |  |\ |     |  |  |  |  |
|**3 ekledik**  |  |  |**3**|  |  |  |  |
**6 sayısı 7'den küçük  olduğunda 7'nin soluna, 5'ten büyük olduğunda 5'in sağına ekledik**  
| Açıklama      |  |  |  |  |     |  |  |
|--             |--|--|- |- |-    |- |- |
|               |  |  |  |  | 7   |  |  |  
|               |  |  |  | /|     |\ |  | 
|               |  |  | 5|  |     |  |8 | 
|               |  | /|  |\ |     |  |  | 
| **6 ekledik** | 1|  |  |  |**6**|  |  |
 |               |  |\ |  |  |     |  |  |
 |               |  |  | 3|  |     |  |  |

 **3 sayısı  7'den, 5'ten ve 1'den küçük  olduğunda 1'in soluna ekledik**  
 **0 sayısı  7'den, 5'ten ve 1'den küçük  olduğunda 1'in soluna ekledik**  
 | Açıklama       |     |  |  |  |  |  |  |  |  |
 |--              |--   |--|- |- |- |- |- |- |- |
 |                |     |  |  |  |  |  | 7|  |  |  
 @@ -67,7 +67,7 @@
 |                |     | /|  |\ |  |  |  |  |  |
 | **0 ekledik**  |**0**|  |  |  | 3|  |  |  |  |

 **9 sayısı  7'den ve 5'ten büyük olduğunda  8'in sağına ekledik**  
 **9 sayısı  7'den ve 8'den büyük olduğunda  8'in sağına ekledik**  
 | Açıklama     |  |  |  |  |  |  |  |  |  |  |     |
 |--            |--|--|- |- |- |- |- |- |- |- |-    |
 |              |  |  |  |  |  |  | 7|  |  |  |     |  
