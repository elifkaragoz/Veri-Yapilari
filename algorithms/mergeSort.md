
Question; [16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Answer;
Verilen dizi 2 ye bölünür -> [16, 21, 11] | [8, 12, 22] -> [16] | [21, 11] -> [8] | [12, 22] -> [16] | [21] | [11] , [8] | [12] | [22]
tek elemanlı dizileri birleştiririz -> [16, 21] | [11] -> [8, 12] | [22]
Her bir çifti birleştiririz -> [11, 16, 21] -> [8, 12, 22]

Son olarak iki sıralı diziyi birleştiririz:
[8, 11, 12, 16, 21, 22]

Question; Big-O gösterimi nedir?

Answer; O(nlogn)
