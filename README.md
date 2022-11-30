# Patika-Selection-Sort-Proje
Patika Proje örneğidir
[22,27,16,2,18,6]----->[2,6,16,18,22,27]

n.(n+1)/2 işlem vardır bu n^2+n/2 gelir dominant olan karakter n^2 olduğu için  o(n^2) alınır.

18 sayısı orta sıralara denk geldiği ve dizide her elemandan 1 tane olduğu için average case durumundan söz edilebilir.

[7,3,5,8,2,9,4,15,6]----->[2|3,5,8,7,9,4,15,6]----->[2,3|5,8,7,9,4,15,6]------->[2,3,4|8,7,9,5,15,6]------>[2,3,4,5|7,9,8,15,6]
  (n tarama)                (n-1 tarama)              (n-2 tarama)
