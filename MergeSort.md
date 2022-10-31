# Merge Short 

## [16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Adımlar | Böl-Birleştir
-- | --
1. Adım Böl | [16,21,11] - [8,12,22]
2. Adım Böl | [16,21] - [11] - [8,12] - [22]
3. Adım Böl | [16] - [21] - [11] - [8] - [12] - [22]
4. Adım Birleştir | [16,21] - [11] - [8,12] - [22]
5. Adım Birleştir| [11,16,21] - [8,12,22]
6. Adım Birleştir | [8,11,12,16,21,22]

2. Big-O gösterimini yazınız.

```
 O(nlogn)

 ```