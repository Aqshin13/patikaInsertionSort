# Proje 1

[Patika](www.patika.dev)

### [22,27,16,2,18,6] -> Insertion Sort
1 Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2 Big-O gösterimini yazınız.
3 Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4 Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1

```
1 [22|,27,16,2,18,6]

2 [22,27,|16,2,18,6]

3 [16,22,27,|2,18,6]

4 [2,16,22,27,|18,6]

5 [2,16,18,22,27,|6]

6 [2,6,16,18,22,27|]

```


## 2
```
Big-O: 

Insertion Sort is a stable comparison sort algorithm with poor performance.
Insertion Sort uses the insertion method and while it can perform at O(n) in the best case, it performs at O(n2) in the average and worst case.

```

## 3
```
 Time Complexity:
 Average case: Aradığımız sayının ortada olması,O(n2)
 Worst case: Aradığımız sayının sonda olması, O(n2)
 Best case: Aradığımız sayının dizinin en başında olması.O(n)
 
 ```
 
 
 ## 4
 ```
 Average Case
 ```
 
 ## 5
 
 
 ```
 [7,3,5,8,2,9,4,15,6]
 
 
 
1 [7|3,5,8,2,9,4,15,6]
 
2 [3,7|5,8,2,9,4,15,6]
 
3 [3,5,7|8,2,9,4,15,6]
 
4 [3,5,7,8|,2,9,4,15,6]
 
 ```