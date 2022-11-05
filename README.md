# kodluyoruz2.hafta-odevi
Kodluyoruz Insertion Sort Projesi
# [22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Cevap:
1. [22,27,16,2,18,6]
2. [16,22,27,2,18,6]
3. [2,16,22,27,18,6]
4. [2,16,18,22,27,6]
5. [2,6,16,18,22,27]
1.Aşama: Dizinin ilk elemanı olan 22 sağındaki ikinci elemanla kıyaslanır. 22<27 olduğundan dolayı sıralama aynı.
2.Aşama: İkinci eleman ile üçüncü elemanı kıyaslıyoruz. 27<16 olduğu için 16 ile 27 yer değiştiriyoruz. Devamında 16 ile ilk eleman kıyaslanır ve 22 ve 16 yer değiştirir.
3. Aşama: Üçüncü ve dördüncü eleman kıyaslanır ve  27 ile 2 yer değiştirir. 2 ile 22 kıyaslanır ve yer değiştirir. 2, 16 ile de kıyaslanır ve yer değiştirirler.
4. 4. Aşama: 27,18 yer değiştirir. 18,22 yer değişir. 18 ikinci elemanla kıyaslanır ve büyük olduğu için yer değiştirme olmaz.
5. 5. Aşama: 27 ve 6 yer değişir. 6 ve 22 yer değişir. 6 ve 18 yer değişir. 6 ve 16 yer değişir. 6 ve ilk eleman kıyaslanır, 6 büyük olduğu için değişme olmaz ve sıralama tamamlanır.

2- Big-O Gösterimi
Cevap:
Worst Case:O(n^2)
Average Case:O(n^2)
Best Case:O(n)

3- Time Complexity
Cevap:
Worst Case:[27,22,18,16,6,2]
Average Case:[6,16,22,2,18,27]
Best Case:[2,6,16,18,22,27]

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Cevap:
18 sıralamanın ortasında olduğu için Avarage Case'tir.

5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
Cevap:
1: [3,7,5,8,2,9,4,15,6]
2: [3,5,7,8,2,9,4,15,6]
3: [3,5,7,8,2,9,4,15,6]
4: [2,3,5,7,8,9,4,15,6]


