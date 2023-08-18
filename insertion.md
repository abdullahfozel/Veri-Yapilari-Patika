# Proje 1 - Insertion Sort

## 1.Soru
[22, 27, 16, 2, 18, 6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

## Çözüm

<p align="center">

| Aşama | Dizi | Seçilen Eleman | Karşılaştırma |
| :----: | :----: | :----: | :----: |
| 1 | [22, 27, 16, 2, 18, 6] | 27 | (22 < 27) |
| 2 | [22, 27, 16, 2, 18, 6] | 16 | (16 < 27) & (16 < 22) |
| 3 | [16, 22, 27, 2, 18, 6] | 2 | (2 < 27) & (2 < 22) & (2 < 16) |
| 4 | [2, 16, 22, 27, 18, 6] | 18 | (18 < 27) & (18 < 22) & (16 < 18) |
| 5 | [2, 16, 18, 22, 27, 6] | 6 | (6 < 27) & (6 < 22) & (6 < 18) & (6 < 16) & (2 < 6) |
| 6 | [2, 6, 16, 18, 22, 27] | - | - |
</p>

## 2.Soru
Big-O gösterimini yazınız.

## Çözüm
N elemanlı bir diziyi sıralamak için:

1 + 2 + ... + (n-1) + n

= (n * (n+1)) / 2

= (n² + n) / 2

= O(n²)

## 3.Soru
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

## Çözüm
Average case: Aradığımız sayının ortada olması

## 4. Soru 
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Çözüm

<p align="center">

| Aşama | Dizi | Seçilen Eleman | Karşılaştırma |
| :----: | :----: | :----: | :----: |
| 1 | [7, 3, 5, 8, 2, 9, 4, 15, 6] | 3 | (3 < 7) |
| 2 | [3, 7, 5, 8, 2, 9, 4, 15, 6] | 5 | (3 < 5) & (5 < 7) |
| 3 | [3, 5, 7, 8, 2, 9, 4, 15, 6] | 2 | (2 < 3) & (2 < 5) & (2 < 7) |
| 4 | [2, 3, 5, 7, 8, 9, 4, 15, 6] | 18 | (18 < 27) & (18 < 22) & (16 < 18) |

</p>
