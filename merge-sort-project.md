# [16,21,11,8,12,22]
# Yukarıda verilen dizinin;
## A: Merge sort aşamaları
[16,21,11] ---- [8,12,22]  
<pre>   👇    </pre>  
[16,21] , [11] --- [8,12] , [22]  
<pre>   👇    </pre>    
[16],[21],[11] --- [8],[12],[22]
<pre>   👇    </pre>  
[16,21] , [11] --- [8,12] , [22]  
<pre>   👇    </pre>  
[11,16,21] ---- [8,12,22]  
<pre>   👇    </pre>  
[8,11,12,16,21,22]
## B: Big O Notation gösterimi
O(nlogn)
