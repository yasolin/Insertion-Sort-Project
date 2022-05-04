# Insertion Sort Project
[22,27,16,2,18,6] -> insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
n=> [22,27,16, 2,18, 6] ,n-1=> [2,27,16,22,18,6] ,n-2=> [2,6,16,22,18,27] ,n-3=>[2,6,16,22,18,27] ,n-4=> [2,6,16,18,22,27] ,n-5=> [2,6,16,18,22,27]

2.Big-O gösterimini yazınız.
Liste 6 elemanlı yanı n=6 Big-O(n*(n+1)/2)'den O(n^2)=36.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Average Case( Aradığımız sayının ortada olması) O(n^2), Worst Case(Aradığımız sayının ortada olması) O(n^2), Best Case(Aradığımız sayının dizinin başında olması) O(n)

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizi küçükten büyüğe sıralandıktan sonra 18 sayısı ortada kaldığı için average case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.adım [2,7,3,5,8,9,4,15,6] 2.adım [2,3,7,5,8,9,4,15,6] 3.adım [2,3,4,7,5,8,9,15,6] 4.adım [2,3,4,5,7,8,9,15,6]
