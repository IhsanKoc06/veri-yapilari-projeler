# Insertion Sort Projesi

Bu repo, [Patika.dev](https://www.patika.dev/tr) Veri Yapıları ve Algoritmalar eğitimi kapsamında hazırlanan Insertion Sort projesidir.

---

## Proje 1

### Soru 1: [22, 27, 16, 2, 18, 6] dizisinin Insertion Sort aşamaları

Insertion Sort algoritmasında her adımda seçilen eleman, solundaki sıralı kısımda uygun yere yerleştirilir.

1.  **[22, 27, 16, 2, 18, 6]** -> Başlangıç (İlk eleman 22 sıralı kabul edilir).
2.  **[22, 27, 16, 2, 18, 6]** -> 27, 22'den büyük olduğu için yerinde kalır.
3.  **[16, 22, 27, 2, 18, 6]** -> 16, 22 ve 27 ile kıyaslanır, en başa yerleşir.
4.  **[2, 16, 22, 27, 18, 6]** -> 2, en başa kadar kaydırılarak yerleşir.
5.  **[2, 16, 18, 22, 27, 6]** -> 18, 22 ve 27'nin önüne yerleşir.
6.  **[2, 6, 16, 18, 22, 27]** -> 6, 16'nın önüne yerleşir. Dizi sıralanmıştır.

---

### Soru 2: Big-O Gösterimi

Algoritma iç içe iki döngü ile çalıştığı için (n + (n-1) + (n-2) + ... + 1) işlem yapılır.
* **Big-O:** $O(n^2)$

---

### Soru 3: Time Complexity

* **Best Case:** Dizinin zaten sıralı olması durumu ($O(n)$).
* **Average Case:** Aranan sayının dizinin ortasında olması durumu ($O(n^2)$).
* **Worst Case:** Dizinin tam ters (büyükten küçüğe) sıralı olması durumu ($O(n^2)$).

---

### Soru 4: 18 Sayısı Hangi Case Kapsamına Girer?

Dizi sıralandıktan sonra `[2, 6, 16, 18, 22, 27]` halini alır. **18** sayısı dizinin ortasında yer aldığı için **Average Case** kapsamına girer.

---

## Proje 2

### [7, 3, 5, 8, 2, 9, 4, 15, 6] Dizisinin Insertion Sort'a Göre İlk 4 Adımı

1.  **[3, 7, 5, 8, 2, 9, 4, 15, 6]** -> (3, 7'nin soluna geçer)
2.  **[3, 5, 7, 8, 2, 9, 4, 15, 6]** -> (5, 7'nin soluna geçer)
3.  **[3, 5, 7, 8, 2, 9, 4, 15, 6]** -> (8 zaten büyük, yerinde kalır)
4.  **[2, 3, 5, 7, 8, 9, 4, 15, 6]** -> (2, en başa geçer)

---

## Lisans

Bu proje [MIT](https://choosealicense.com/licenses/mit/) lisansı altındadır.

---

### Hazırlayan:
İhsan Koç
