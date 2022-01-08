# Panel Bulucu
Bu program girilen hedef sitenin admin panelini deneme/yanılma (brute-force) yöntemi ile deneyerek bulur. Çıkan tüm sonuçlar doğru olmayabilir. Çünkü bu program sayfanın içeriğine bakmaz sadece sayfaya girip girmediğine bakar yani HTTP kodu 200 olup olmadığına bakar. HTTP kodları daha fazla bilgi için <a href="https://www.restapitutorial.com/httpstatuscodes.html">buraya</a> tıklayınız.

## Programın İndirilmesi ve Kullanımı
`git clone https://github.com/wolkann/panel-bulucu.git` Yazarak programı kurabilirsiniz.<br>
`cd panel-bulucu`<br>
`python3 panel-finder.py` Yazarak programı çalıştırabilir ve gelen ekranda hedef sitenizi `https://domain.com/` şeklinde yazarak programı başlatabilirsiniz.<br>
<img src="/img/panel.png"/>
