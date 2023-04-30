# VeriYapilariVeAlgoritmalar
Patika.dev tarafından sağlanan "Veri Yapıları ve Algoritmalar" eğitim içeriğinin bölüm sonu projelerini içermektedir.

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[22, 27, 16, 2, 18, 6]
[2, 27, 16, 22, 18, 6]
[2, 6, 16, 22, 18, 27]
[2, 6, 16, 18, 22, 27]

Big-O gösterimi;
n+(n-1)+(n-2)...(n-4)+1=[n.(n+1)]/2=(n^2+n)/2
o(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı Average Case kapsamına girer.


[7, 3, 5, 8, 2 , 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[2|, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3|, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4|, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5|, 7, 9, 8, 15, 6]


Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

[16, 21, 11, 8, 12, 22]
[16, 21, 11] - [8, 12, 22]
[16] - [21, 11] - [8] - [12,22]
[16] - [21] - [11] [8] - [12] - [22]
[16] - [11, 21] - [8] - [12, 22]
[11, 16, 21] - [8, 12, 22]
[8, 11, 12, 16, 21, 22]

Big-O gösterimi;
O(nlogn)


Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Root 6'dır. Solunda 6'dan küçükler ve sağında 6'dan büyükler bulunur.

        6
       / \
      5   7
     /     \
    1       8
   / \       \
  0   3       9
     / \
    2   4
