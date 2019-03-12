1. Jawaban Studi Kasus 1.
a. Operasi Pengisian Nilai (Assignment)

- Base Case
maks <- x1 => 1 kali
i <- 2 => 1 kali
i <- i+1 => n – 1 kali
maks <- xi => 0 kali

T1min = 1 + 1 + n - 1 + 0 = 1 + n

- Worst Case
maks <- x1, =>1 kali
i <- 2 , => 1 kali
i <- i+1, =>n – 1 kali
maks <- xi =>n kali
T1max = 1 + + n - 1 + n = 1 + 2n

b. Operasi Penjumlahan
-Base Case

i + 1 , => n – 1 kali
T2min = n - 1

-Worst Case
i + 1 , => n – 1 kali
T2min = n - 1

c. Operasi Perbandingan
-Base Case
xi > maks, => n kali

- Worst Case
c.Operasi Perbandingan
xi > maks, => n kali

T(min)= t_1+ t_2+ t_3=1+n+n-1+n=3n
T(max)= t_1+ t_2+ t_3=1+2n+n-1+n=4n

