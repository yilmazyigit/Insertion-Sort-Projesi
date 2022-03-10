<h1>Patika Veri Yapilari Ve Algoritma Projesi</h1>

<h3> [22,27,16,2,18,6] -> Insertion Sort </h3>

<p>Aşağıda verilen dizinin sort türüne göre aşamalarını yazınız.</p>
<p> [22,27,16,2,18,6] [2,22,27,16,18,6] [2,6,22,27,16,18] [2,6,16,22,27,18] [2,6,16,18,22,27] </p>
<p> Big-O gösterimini yazınız. O (n2) </p>
<p></p>Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. Average case [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. <br>[2,7,3,5,8,9,4,15,6] [2,3,7,5,8,9,4,15,6] [2,3,4,7,5,8,9,15,6] [2,3,4,5,7,8,9,15,6] </p>
<h3>Merge Sort Projesi</h3>
<h4>[16,21,11,8,12,22] -> Merge Sort</h4>
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.<br>

Başlangıç:[16,21,11,8,12,22] <br>

Adım 1:[16,21,11]-[8,12,22]<br>

Adım 2:[16,21]-[11]-[8,12,22]<br>

Adım 3:[16]-[21]-[11]-[8,12,22]<br>

Adım 4:[16,21]-[11]-[8,12,22]<br>

Adım 5:[11,16,21]-[8,12,22]<br>

Adım 6:[11,16,21]-[8,12]-[22]<br>

Adım 7:[11,16,21]-[8]-[12]-[22]<br>

Adım 8:[11,16,21]-[8,12]-[22]<br>

Adım 9:[11,16,21]-[8,12,22]<br>

Adım 10:[8,11,12,16,21,22]<br>

Son:[8,11,12,16,21,22]<br>

Big-O: O(nlogn)<br>

Binary Search Tree Projesi<br>
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. root = 7<br>

          7
         / \
        5   8
       / \   \  
      1   6   9
     / \   
    0   3 
       / \
      2   4      
