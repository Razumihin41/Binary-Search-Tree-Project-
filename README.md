## BINARY SEARCH TREE PROJECT

Patika dev profilim --> https://app.patika.dev/razumihin

---

### Soru 1.

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalari;

|  |  |  |  |  |  | 7 |  |  |  |  |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|  |  |  |  |  | / |  | \ |  |  |  |
|  |  |  |  | 5 |  |  |  | 8 |  |  |
|  |  |  | / |  | \ |  |  |  | \ |  |
|  |  | 1 |  |  |  | 6 |  |  |  | 9 |
|  | / |  | \ |  |  |  |  |  |  |  |
| 0 |  |  |  | 3 |  |  |  |  |  |  |
|  |  |  | / |  | \ |  |  |  |  |  |
|  |  | 2 |  |  |  | 4 |  |  |  |  |

şeklindedir.

**Metot:** Inceledigimiz sayi bir önceki sayidan küçük ise sola, büyük ise saga olacak şekilde kiyaslanan sayidan kücük olana kadar asagiya dogru sorgulama islemine devam edilip konumlandilir. 