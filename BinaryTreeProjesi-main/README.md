# Binary Search Tree Projesi

Bu repo, [Patika.dev](https://www.patika.dev/tr) Veri Yapıları ve Algoritmalar eğitimi kapsamında hazırlanan Binary Search Tree (BST) projesidir.

---

## Proje Sorusu

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

---

## Binary Search Tree Aşamaları

Binary Search Tree yapısında, her düğüm (node) kendisinden küçük olan elemanları sol alt ağacına, büyük olanları ise sağ alt ağacına yerleştirir.

1.  **Root 7'dir.**
2.  **5**, 7'den küçük olduğu için **7'nin soluna** eklenir.
3.  **1**, 7 ve 5'ten küçük olduğu için **5'in soluna** eklenir.
4.  **8**, 7'den büyük olduğu için **7'nin sağına** eklenir.
5.  **3**, 7 ve 5'ten küçük, 1'den büyük olduğu için **1'in sağına** eklenir.
6.  **6**, 7'den küçük, 5'ten büyük olduğu için **5'in sağına** eklenir.
7.  **0**, 7, 5 ve 1'den küçük olduğu için **1'in soluna** eklenir.
8.  **9**, 7 ve 8'den büyük olduğu için **8'in sağına** eklenir.
9.  **4**, 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğu için **3'ün sağına** eklenir.
10. **2**, 7 ve 5'ten küçük, 1'den büyük, 3'ten küçük olduğu için **3'ün soluna** eklenir.

---

## Görselleştirme (Tree Structure)

Dizinin BST yapısına dönüştürülmüş hali şu şekildedir:

```text
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4
