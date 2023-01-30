--------------------------------------------------------------------------------------

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.


1- Sıralı olmayan diziyi ortadan eşit olarak iki alt diziye ayırır.
2- Bu ayırma işlemi, alt diziler en çok iki elemanlı olana kadar devam eder.
3- Alt dizileri kendi içinde sıralar.
4- Sıralı iki alt diziyi tek bir sıralı dizi olacak şekilde birleştirir.

[16,21,11,8,12,22]
[16,21,11]   [8,12,22]
[16] [21,11]   [8] [12,22]
[16] [21] [11]   [8] [12] [22]

[16] [11,21]   [8] [12,22]
[11,16,21]   [8,12,22]
[8,11,12,16,21,22]

--------------------------------------------------------------------------------------

Big-O gösterimini yazınız.

Big-O = O(nlogn)

--------------------------------------------------------------------------------------