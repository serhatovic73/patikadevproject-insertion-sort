<h1>Proje 1</h1>

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması  
Worst case: Aradığımız sayının sonda olması  
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

<h2>Hadi yapalim</h2>

<strong>Insertion Sort Siralamasi </strong>

<ol>
  <li>En baştaki sayı seçilir => 22</li>
  <li>22 < 27 küçük olduğu için yerinde kalır [22,27]</li>
  <li>27 > 16 büyük olduğu için sağa kayar => [22,16,27]</li>
  <li>16 < 22 küçük olduğu için sola kayar => [16,22,27]</li>
  <li>27 > 2 büyük olduğu için sağa kayar => [16,22,2,27]</li>
  <li>2 < 22 küçük olduğu için sola kayar => [16,2,22,27]</li>
  <li>2 < 16 küçük olduğu için sola kayar => [2,16,22,27]</li>
  <li>27 > 18 büyük olduğu için sağa kayar => [2,16,22,18,27]</li>
  <li>18 < 22 küçük olduğu için sola kayar => [2,16,18,22,27]</li>
  <li>27 > 6 büyük olduğu için sağa kayar => [2,16,18,22,6,27]</li>
  <li>6 < 22 küçük olduğu için sola kayar => [2,16,18,6,22,27]</li>
  <li>6 < 18 küçük olduğu için sola kayar => [2,16,6,18,22,27]</li>
  <li>6 < 16 küçük olduğu için sola kayar => [2,6,16,18,22,27]</li>
</ol>

burada islemimiz 13 adimda basariyla siralanmistir.

<h3> Big O durumu; </h3>

O(n²) (ortalama ve en kötü durum)
O(n) (en iyi durum)

<h4>Time Complexity</h4>
<p>Burada dizi siralandiktan sonra dizi bu  hale gelir <strong>[2,6,16,18,22,27]</strong> 18 de orta kisimda yer aliyor
 yani aradigimiz sayi  average case olmasi gerekiyor.</p>

<h5> [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.</h5>
<p>Bunu buyukten kucuge selection sorta gore duzenleyelim</p>

<ol>
<li>[7,3,5,8,2,9,4,15,6] => En buyuk 15 sayisi birinci siradaki 7 ile yer degisir = > [15,3,5,8,2,9,4,7,6] </li>
<li>[15,3,5,8,2,9,4,7,6] => ikinci en buyuk sayi olan 9, ikinci siradaki 3 ile yer degisir  => [15,9,5,8,2,3,4,7,6]</li>
<li>[15,9,5,8,2,3,4,7,6] => ucuncu en buyuk sayimiz 8 ile 5 yer degisir [15,9,8,5,2,3,4,7,6]</li>
<li>[15,9,8,5,2,3,4,7,6] => 7 ile 5 yer degisir [15,9,8,7,2,3,4,5,6]</li>
<li>[15,9,8,7,2,3,4,5,6] => 6 ile 2 yer degisir [15,9,8,7,6,3,4,5,2]<</li>
...
<li> en son islemimiz bu sekilde olacaktir => [15,9,8,7,6,5,4,3,2]</li>
</ol>
