Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

<p>oncelikle dizimizi yariya bolmemiz gerekir ve bu sekilde tumu parcalanana kadar devam etmemiz gerekir</p>

<h2>1.adim</h2>
<p>dizimizi yariya bolelim</p>
<strong>

[16,21,11,8,12,22] => [16,21,11] + [8,12,22]
</strong>

<h2>2.adim</h2>
<p>alt dizileride bolelim</p>
<strong>

[16,21,11] + [8,12,22] => [16] + [21,11] + [8] + [12,22]
</strong>

<h2>3.adim</h2>
<p>hepsi bolunene kadar  bolelim</p>
<strong>

[16] + [21,11] + [8] + [12,22] => [16] + [21] + [11] + [8] + [12] + [22]

</strong>

<h2>4.adim</h2>
<p>simdi ise alt dizileri siralayip birlestirme islemi yapalim</p>
<strong>

[16] + [21] + [11] => [11] + [16] [21] => [11,16] + [21]

[8] + [12] + [22] => [8] + [12] + [22] => [8,12] + [22]

</strong>
<h2>5.adim</h2>
<p>bir sonraki de birlestirelim</p>
<strong>

[11,16] + [21] => [11,16,21]

[8,12] + [22] => [8,12,22]

</strong>

<h2>6.adim</h2>
<p> son islemimizi de yapalim , birlestirelim</p>
<strong>

[11,16,21] + [8,12,22] => [8,11,12,16,21,22]

</strong>

<h2>sonuc</h2>
<p>bu sekilde dizimizi  bole bole  kucukleri ve buyukleri siralayip bitirdik. </p>
<strong>

Sonuc => [8,11,12,16,21,22]

</strong>

<h1>Big O Gösterimi </h1>
<strong>
Burada islemlerler O(n log n) den baska bir durum soz konusu degildir.
Cunku dizi ister sirali veya sirasiz olsun her türlü durumda dizi bole bole devam edecektir ve bu islemler
surekli olmak zorunda merge yapisi geregi.
</strong>
