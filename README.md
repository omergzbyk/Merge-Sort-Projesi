# Merge-Sort-Projesi
Proje 2 [16,21,11,8,12,22] -> Merge Sort  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

Ödev: [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

ÇÖZÜM:

[16,21,11] [8,12,22]

[16,21] [11] [8] [12,22]

[16] [21] [11] [8] [12] [22]

[16,21] [11] [8] [12,22]

[11,16,21] [8,12,22]

[8,11,12,16,21,22]

Big-O Gösterimi:

n=6 Best case : O(nlogn) Average case : O(nlogn) Worst case : O(nlogn) -> O(6log6)
