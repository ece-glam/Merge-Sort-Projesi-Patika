# Merge-Sort-Projesi-Patika
Merge Sort Projesi<br />
[16,21,11,8,12,22] -> Merge Sort<br />

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.<br />
Steps:
1. [16,21,11,8,12,22]
2. [16,21,11]  [8,12,22]
3. [16,21]- [11] [8,12]-[22]
4. [16] [21] [11] [8] [12] [22]
5. [16,21]-[11]  [8,12]-[22]
6. [11,16,21] [8,12,22]
7. [8.11,12,16,21,22]

Big-O gösterimini yazınız. <br />
In everys steps we check the n/2 iterations
- Big-O(nlog(n))
