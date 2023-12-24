<h1 id="proje-1">Proje 1</h1>
<p>[22,27,16,2,18,6]</p>
<p>Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.</p>
<p>Big-O gösterimini yazınız.</p>
<p>Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case’lerden hangisinin kapsamına girer? Yazınız</p>
<ol>
<li>Average case: Aradığımız sayının ortada olması</li>
<li>Worst case: Aradığımız sayının sonda olması</li>
<li>Best case: Aradığımız sayının dizinin en başında olması.</li>
</ol>
<p>[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort’a göre ilk 4 adımını yazınız.</p>
<h1 id="cevaplar">Cevaplar</h1>
<p>Verilen dizi: [22, 27, 16, 2, 18, 6]<br>
Sort türüne göre aşamaları:<br>
<strong>Aşama 1:</strong> [<strong>22</strong>, 27, 16, 2, 18, 6]<br>
-   İlk adımda, dizinin ilk elemanı olan 22 yerinde duruyor.</p>
<p><strong>Aşama 2:</strong> [22, <strong>27</strong>, 16, 2, 18, 6]<br>
-   İkinci adımda, 27’yi alıp onu uygun konuma yerleştiriyoruz. 27, 22’den büyük olduğu için yer değiştirme yapmamız gerekiyor. Bu durumda dizi şu şekilde: [<strong>22, 27</strong>, 16, 2, 18, 6]</p>
<p><strong>Aşama 3:</strong> [16, <strong>22, 27</strong>, 2, 18, 6]<br>
-   16’yı alıp uygun konuma yerleştiriyoruz. 16, 22’den küçük olduğu için yer değiştirmeye gerek yok. Dizi şu hale geliyor: [<strong>16, 22, 27</strong>, 2, 18, 6]</p>
<p><strong>Aşama 4:</strong> [2, <strong>16, 22, 27</strong>, 18, 6]<br>
-   2’yi alıp uygun konuma yerleştiriyoruz. Bu durumda diziyi şu şekilde elde ediyoruz: [<strong>2, 16, 22, 27</strong>, 18, 6]</p>
<p><strong>Aşama 5:</strong> [2, 16, <strong>18, 22, 27</strong>, 6]<br>
-   18’i alıp uygun konuma yerleştiriyoruz. Dizi şu hale geliyor: [<strong>2, 16, 18, 22, 27</strong>, 6]</p>
<p><strong>Aşama 6:</strong> [2, 6, <strong>16, 18, 22, 27</strong>]<br>
-   Son olarak, 6’yı alıp uygun konuma yerleştiriyoruz. Dizi tamamen sıralanmış hale geliyor: [<strong>2, 6, 16, 18, 22, 27</strong>]</p>
<p>Time complexity:<br>
<strong>Best-case</strong>: Aradığımız değerin 2 olması bu algoritmanın best-case’dir. Çünkü daha ilk iterasyonda aradığımız değere ulaşmış oluruz. (En iyi durum)<br>
<strong>Average-case</strong>: Aradığımız değer olan 18 sayısı, Average Case (Ortalama Durum) kapsamına girmektedir, çünkü sıralı bir dizide ortada yer almaktadır.<br>
<strong>Worst-case</strong>: Bu örneğimiz için worst-case, yani en kötü durum senaryosu, aradığımız değerin yani 18’in dizinin en sondaki değer olması durumudur. (En kötü durum)<br>
<em>Worst-case:</em>* Aradığımız değerin dizi içerisinde bulunmaması durumu da worst-case’e örnektir.</p>
<p><strong>[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort’a göre ilk 4 adımı:</strong><br>
<strong>Adım 1:</strong> En küçük elemanı bul ve ilk eleman ile yer değiştir.<br>
-   Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]<br>
<strong>Adım 2:</strong> İkinci en küçük elemanı bul ve ikinci eleman ile yer değiştir.<br>
-   Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]<br>
<strong>Adım 3:</strong> Üçüncü en küçük elemanı bul ve üçüncü eleman ile yer değiştir.<br>
-   Dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]<br>
<strong>Adım 4:</strong> Dördüncü en küçük elemanı bul ve dördüncü eleman ile yer değiştir.<br>
-   Dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]</p>
<p>Bu adımlar, Selection Sort algoritmasının her adımda en küçük elemanı seçip onu sıralı kısmın başına yerleştirdiği temel mantığı göstermektedir. Bu işlem, dizi tamamen sıralanana kadar devam eder.</p>

