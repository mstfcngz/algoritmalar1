[22,27,16,2,18,6] -> Insertion Sort
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

n+(n-1)+(n-2)+(n-3)... +1
Bu durumda n.(n+1)/2
Bu da bize O(n^2) verir.
Big-O gösterimi = O(n^2) dir.

Dizi sıralandıktan sonra 18 sayısı ortadadır ve average case kapsamındadır.

[7,3,5,8,2,9,4,15,6]-> Insertion Sort  ilk dört adımı
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
. 
.
.
.