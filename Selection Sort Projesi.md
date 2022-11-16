# Proje 1
# Sorular:
```sh
1) [22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2) Big-O gösterimini yazınız.

3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki caselerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```

# Cevaplar:
# 1) [22,27,16,2,18,6] Insertion Sort aşamaları:
```sh
1.[22,27,16,2,18,6] -> [2,27,16,22,18,6] en küçük olan 2 ile 22 yer değiştirir
2.[2,27,16,22,18,6] -> [2,6,16,22,18,27] daha sonra sıradaki 27 ile 6 yer değiştirir
3.[2,6,16,22,18,27] -> [2,6,16,22,18,27] sırada 16 dan daha küçük bir değer olmadığı için değişmeden devam eder.
4.[2,6,16,22,18,27] -> [2,6,16,18,22,27] 18 ile 22 yer değiştirir
5. dizinin son hali -> [2,6,16,18,22,27]
```
# 2) Big-O gösterimi:
```sh
-> Big O = O(n^2)
```
# 3) Time Complexity: 18 sayısı hangi case durumuna aittir? 
```sh
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

-> Aradığımız 18 sayısı dizinin ortasında olduğu için AVARAGE CASE olur.
```
# 4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:
```sh
1. [2,3,5,8,7,9,4,15,6]		
2. [2,3,5,8,7,9,4,15,6]		
3. [2,3,4,8,7,9,5,15,6]		
4. [2,3,4,5,7,9,8,15,6]
```
