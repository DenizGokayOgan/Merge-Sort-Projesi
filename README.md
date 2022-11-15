# Merge-Sort-Projesi
[16,21,11,8,12,22] -> Merge Sort
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
### Aşamalar
```
[16,21,11]-------------[8,12,22]
[16,21]--[11]-----------[8,12]--[22]
[16]--[21]--[11]----------[8]--[12]--[22]
[16,21]--[11]---------[8,12]--[22]
[11,16,21]----------[8,12,22]
son hali---> [8,11,12,16,21,22]
```
### Big-O Gösterimi
```
O(nlogn)
```