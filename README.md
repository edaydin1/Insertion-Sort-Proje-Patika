# Insertion-Sort-Proje-Patika
Insertion Sort Projesi
Proje 1
1-
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.


2-
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
###############################################################################################################
1-
1.Step = 2  [2| 22,27,16,18,6]
2.Step = 6  [2,6| 22,27,16,18]
3.Step = 16  [2,6,16| 22,27,18]
4.Step = 18  [2,6,16,18| 22,27]
Average case: Aradığımız sayının ortada olması
O(n^2)

2-
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
🔸 1. Adım:En küçük eleman: 2 2 ile ilk eleman (7) yer değiştirir.[2,3,5,8,7,9,4,15,6][2,3,5,8,7,9,4,15,6]
🔸 2. Adım:Kalan dizi:[3,5,8,7,9,4,15,6][3,5,8,7,9,4,15,6] En küçük eleman: 3Zaten yerinde → Değişiklik yok.[2,3,5,8,7,9,4,15,6] [2,3,5,8,7,9,4,15,6]
🔸 3. Adım:Kalan dizi:[5,8,7,9,4,15,6][5,8,7,9,4,15,6] En küçük eleman: 44 ile 5 yer değiştirir.[2,3,4,8,7,9,5,15,6] [2,3,4,8,7,9,5,15,6]
🔸 4. Adım:Kalan dizi:[8,7,9,5,15,6][8,7,9,5,15,6] En küçük eleman: 55 ile 8 yer değiştirir.[2,3,4,5,7,9,8,15,6] [2,3,4,5,7,9,8,15,6]


# Merge-Sort-Proje-Patika
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
###############################################################################################################
[16,21,11,8,12,22] 
[16,21,11] [8,12,22] 
[16,21] [11][ 8,12] [22] 
[16] [21] [11] [8] [12] [22] 
[8,11,12,16,21,22]
Big-O gösterimi= O(nlogn)


# Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
##################################################################################################################

7      
             7
            /  \
           5    8
          /  \    \
        1     6    9
      /  \
     0    3
         /  \
        2     4
       

