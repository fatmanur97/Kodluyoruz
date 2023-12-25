<h1 id="proje-2">Proje 2</h1>
<p>[16,21,11,8,12,22]</p>
<ul>
<li>Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.                 -   Big-O gösterimini yazınız.–</li>
</ul>
<h1 id="cevaplar">Cevaplar</h1>
<p>Aşağıda, verilen dizinin merge sort kullanılarak sıralanma aşamalarını adım adım açıklıyorum:</p>
<p>Verilen dizi: [16, 21, 11, 8, 12, 22]</p>
<p><strong>Adım 1: Bölme (Splitting)</strong> Diziyi iki eşit parçaya bölerek başlıyoruz. [16, 21, 11] | [8, 12, 22]</p>
<p><strong>Adım 2: İkili Bölme (Splitting)</strong> Her bir parçayı iki eşit parçaya bölüyoruz. [16] | [21, 11] || [8] | [12, 22]</p>
<p><strong>Adım 3: İkili Bölme (Splitting)</strong> Her bir parçayı tekrar iki eşit parçaya bölüyoruz. [16] || [21] | [11] || [8] || [12] | [22]</p>
<p><strong>Adım 4: Sıralama ve Birleştirme (Merging)</strong> Şimdi, tek elemanlı parçalardan başlayarak sıralama ve birleştirme işlemine geçiyoruz. [16] || [11, 21] || [8] || [12, 22]</p>
<p><strong>Adım 5: Sıralama ve Birleştirme (Merging)</strong> İki elemanlı parçaları birleştiriyoruz. [11, 16, 21] || [8, 12, 22]</p>
<p><strong>Adım 6: Sıralama ve Birleştirme (Merging)</strong> Son olarak, iki sıralı parçayı birleştiriyoruz. [8, 11, 12, 16, 21, 22]</p>
<p>Bu şekilde, merge sort algoritması kullanılarak verilen dizi sıralanmış olur.</p>
<p><strong>Big O Gösterimi:</strong> Algoritma, her seviyede bölme ve birleştirme işlemlerini tekrar ederek sıralama işlemini gerçekleştirir. Her seviyede n elemanının logaritmik sayıda işlemle sıralanması, algoritmanın zaman karmaşıklığını O(n log n) yapar.</p>

