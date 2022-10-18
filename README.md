# Veri-yapilari-ve-algoritmalar2
 www.patika.dev
# Merge Sort Projesi-Patika.dev
 
 [16,21,11,8,12,22] -> Merge Sort

- 1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- 2-Big-O gösterimini yazınız.
 
 ## 1- Merge Sort Aşamalar
 ```
 Merge sort'a göre sayı dizisini tek eleman kalana kadar sürekli yarıya bölmeliyiz.
 [16,21,11,8,12,22] 
 - [16,21,11]     [8,12,22]
 - [16,21]   [11]   [8,12]   [22]
 - [16]  [21]  [11]  [8]  [12]  [22] bu aşamadan sonra tek tek sıralı eklenip birleştirilmeye başlanır
 - [16,21]   [11]   [8,12]   [22]  
 - [11,16,21]   [8,12,22]
 - [8,11,12,16,21,22]
sonuçta küçükten büyüğe sıralı elde edilir 
 ```
 
 ## 2- Big O Notation Gösterimi
  ```
 Eleman sayısını n olarak alırsak eleman sayısı sürekli yarıya inmesi sebebiyle 2^x=n çözümlenirse logn = x bulunur
 ayrıca dizilim için n-1 sorgulama yapıldığı için time complexity O(n) olur.
 İkisi dahil edilirse Big O notation tüm caseler için O(n*logn) bulunur.
  ```
   ```
 Worst case   : O(n*logn)
 Average case : O(n*logn)
 Best case    : O(n*logn)
 ```
