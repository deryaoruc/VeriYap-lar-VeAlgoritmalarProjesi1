# 1. Örnek

--------------------------------

[22,27,16,2,18,6]

### A) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
--------------------------------------


1. Adım-> 22| 27 16 2 18 6 
1. Adım-> 22 27| 16 2 18 6 
2. Adım-> 22 27 16| 2 18 6
3. Adım-> 16 22 27| 2 18 6
4. Adım-> 16 22 27 2| 18 6
5. Adım-> 2 16 22 27| 18 6
6. Adım-> 2 16 22 27 18| 6
7. Adım-> 2 16 18 22 27| 6
8. Adım-> 2 16 18 22 27 6
9. Adım-> 2 6 16 18 22 27



### B) Big-O gösterimini yazınız.

--------------------------------------------------

O(n^2)


### C) Time Complexity:

--------------------------

Average Case: Aradığımız sayının ortada olması --> O(n^2)
Worst Case: Aradığımız sayının sonda olması --> O(n^2)
Best Case: Aradığımız sayının dizinin en başında olması --> O(n)


### D) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
----------------------------------------

1. adımda sıralaması değişeceği için average case’dir.
 
# 2. Örnek 

---------------------------------------
 
### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort’a göre ilk 4 adımını yazınız.

------------------------------------------

1-[3,7,5,8,2,9,4,15,6]
2-[3,5,7,8,2,9,4,15,6]
3-[3,5,7,8,2,9,4,15,6]
4-[2,3,5,7,8,9,4,15,6]