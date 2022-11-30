# Patika-Selection-Sort-Proje
Patika Proje örneğidir
1.Soru - Aşamalar
[22,27,16,2,18,6]------->[2,6,16,18,22,27]

2.Soru Bİg o gösterimi
ilk başta n tarama yapılmıştır,ikinci aşamada n-1 ,üçüncü aşamada n-2 aşamalar 1 kalana devam etmektedir. Uygulamamızda n 6 olduğu için yapılan işlem sayısı aşağıdaki gibidir.
6+5+4+3+2+1=21
Ardışık sayıların toplamı ise n.(n+1)/2 ile gösterilir.n^2+1/2 den dominant olan değer n^2 alınır. Bog o(n^2)

3.Soru Time Complexity

 18 sayısı ortada denilebilir average case durumu vardır.
 
 
 4.Soru
 
 [7,3,5,8,2,9,4,15,6]- [2|3,5,8,7,9,4,15,6]-[2,3|5,8,7,9,4,15,6]-[2,3,4|8,7,9,5,15,6]-[2,3,4,5|7,9,8,15,6]-[2,3,4,5,6|9,8,15,7]-[2,3,4,5,6,7|8,15,9]-[2,3,4,5,6,7,8|15,9]-[2,3,4,5,6,7,8,9|15]
