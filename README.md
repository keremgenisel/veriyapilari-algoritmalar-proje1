# Insertion Sort 

## [22,27,16,2,18,6] Dizisinin Insertion Sort

[22,27,16,2,18,6] > n
[2,27,16,22,18,6] > n-1
[2,6,16,22,18,27] > n-2
[2,6,16,18,22,17] 1

## Big-O Gösterimi 

O(n^2)

## 18 Sayısı Hangi Case Kapsamına Girer? (Time Complexity)

[2,6,16,(18),22,17]

Ortada olduğu için Average Case

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

[7,3,5,8,2,9,4,15,6] > n
[2,3,5,8,7,9,4,15,6] > n-1
[2,3,4,8,7,9,5,15,6] > n-2
[2,3,4,5,7,9,8,15,6] > n-3
[2,3,5,5,6,9,8,15,7] > n-4