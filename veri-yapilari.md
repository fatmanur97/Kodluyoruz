# Proje 1

[22,27,16,2,18,6] 

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.  Average case: Aradığımız sayının ortada olması
2.  Worst case: Aradığımız sayının sonda olması
3.  Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Cevaplar

Verilen dizi: [22, 27, 16, 2, 18, 6]
Sort türüne göre aşamaları:
  **Aşama 1:** [**22**, 27, 16, 2, 18, 6]
    -   İlk adımda, dizinin ilk elemanı olan 22 yerinde duruyor.
    
  **Aşama 2:** [22, **27**, 16, 2, 18, 6]
    -   İkinci adımda, 27'yi alıp onu uygun konuma yerleştiriyoruz. 27, 22'den büyük olduğu için yer değiştirme yapmamız gerekiyor. Bu durumda dizi şu şekilde: [**22, 27**, 16, 2, 18, 6]
    
  **Aşama 3:** [16, **22, 27**, 2, 18, 6]
    -   16'yı alıp uygun konuma yerleştiriyoruz. 16, 22'den küçük olduğu için yer değiştirmeye gerek yok. Dizi şu hale geliyor: [**16, 22, 27**, 2, 18, 6]

  **Aşama 4:** [2, **16, 22, 27**, 18, 6]
    -   2'yi alıp uygun konuma yerleştiriyoruz. Bu durumda diziyi şu şekilde elde ediyoruz: [**2, 16, 22, 27**, 18, 6]
    
  **Aşama 5:** [2, 16, **18, 22, 27**, 6]
    -   18'i alıp uygun konuma yerleştiriyoruz. Dizi şu hale geliyor: [**2, 16, 18, 22, 27**, 6]
   
  **Aşama 6:** [2, 6, **16, 18, 22, 27**]
    -   Son olarak, 6'yı alıp uygun konuma yerleştiriyoruz. Dizi tamamen sıralanmış hale geliyor: [**2, 6, 16, 18, 22, 27**]

Time complexity: 
**Best-case**: Aradığımız değerin 2 olması bu algoritmanın best-case’dir. Çünkü daha ilk iterasyonda aradığımız değere ulaşmış oluruz. (En iyi durum)
**Average-case**: Aradığımız değer olan 18 sayısı, Average Case (Ortalama Durum) kapsamına girmektedir, çünkü sıralı bir dizide ortada yer almaktadır.
**Worst-case**: Bu örneğimiz için worst-case, yani en kötü durum senaryosu, aradığımız değerin yani 18'in dizinin en sondaki değer olması durumudur. (En kötü durum) 
Worst-case: Aradığımız değerin dizi içerisinde bulunmaması durumu da worst-case'e örnektir.

**[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:**
   **Adım 1:** En küçük elemanı bul ve ilk eleman ile yer değiştir.
    -   Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]
    **Adım 2:** İkinci en küçük elemanı bul ve ikinci eleman ile yer değiştir.
    -   Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]
   **Adım 3:** Üçüncü en küçük elemanı bul ve üçüncü eleman ile yer değiştir.
    -   Dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]
 **Adım 4:** Dördüncü en küçük elemanı bul ve dördüncü eleman ile yer değiştir.
    -   Dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]
    
Bu adımlar, Selection Sort algoritmasının her adımda en küçük elemanı seçip onu sıralı kısmın başına yerleştirdiği temel mantığı göstermektedir. Bu işlem, dizi tamamen sıralanana kadar devam eder.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3NTAzMDExNzddfQ==
-->