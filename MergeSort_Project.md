# Merge Sort
## [16,21,11,8,12,22] 
1. First of all, array is divided up to reaching each element seperately,
- [16,21,11] & [8,12,22]

- [16] [21,11] & [8] [12,22]

- [16] [21] [11] & [8] [12] [22]
2. Then, merging is carried out by binary terms up to obtain sorted array
- [16] [11] [21] & [8] [12] [22]

- [11 16 21] & [8 12 22 ]

- [8 11 12 16 21 22 ]
3. Big-O Notation: O(nlogn)
